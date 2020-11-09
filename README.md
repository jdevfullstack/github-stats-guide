# Hacking The Github Stats
The [GitHub Stats](https://github.com/anuraghazra/github-readme-stats) 
is an external service to display your ranking based on commits, PRs,
contribution etc. You just simply need the URL and change the details,
include it in your GitHub profile and you're done.

If you don't have any idea how it works, it is an external web app
that uses GitHub data (through its API) to generate your rank. 
You don't need to install anything you just simply get the URL
of the app, change the details so that it's referring to your account
and you're done.

```
https://github-readme-stats.vercel.app/api?username=[yourusername]&show_icons=true
```
now when you want include your private repos, include `&count_private=true`.

The weight and the components involve how they generate the rank:

```
  const COMMITS_OFFSET = 1.65;
  const CONTRIBS_OFFSET = 1.65;
  const ISSUES_OFFSET = 1;
  const STARS_OFFSET = 0.75;
  const PRS_OFFSET = 0.5;
  const FOLLOWERS_OFFSET = 0.45;
  const REPO_OFFSET = 1;
  ```
this is directly from the code of the app itself, so 
you want to focus on `commits` and `contrib`.

## Commits
Commits are very easy to generate, simply create a private repo
named `test` so that it will look like you are testing GitHub
or any bug. Now, make sure that you turn on the include
private commits in the API. Then you want to have say 2k
to 3k commits,
it does not mean you are coding, simply create a file
and for every change, even just a single letter, click commit.

## Contributions
Contributions to repos are actually your repos and
repos of others when you create pull requests even
if they simply closed them. But of course, you can't create
a spam. So, in order to achieve this, you want to focus
on a pull request even simply changing something at the 
README file of others. What I did was adding a Page View.
If you click the README file of others, then click
the edit button, it will automatically create a fork 
(your copy of that particular repo) (we'll return to
forking later to generate stars).


