# Hacking The Github Stats
The [GitHub Stats](https://github.com/anuraghazra/github-readme-stats) 
is an external service to display your ranking based on commits, PRs,
contribution etc. You just simply need the URL and change the details,
include it in your GitHub profile and you're done.

If you don't have any idea how it works, it is an external web app
that uses GitHub data (through its API) to generate your rank. 
You don't need to install anything, you just simply get the URL
of the app, change the details so that it's referring to your account
and you're done.

```
https://github-readme-stats.vercel.app/api?username=[yourusername]
```
make sure you include your private repos, include `&count_private=true`.

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

## Rationale
This is not to cheat an app or to fake something. 
Remember, the stats of GitHub can be misleading
even if a software developer is good enough.

If you really feel that you deserve that rank,
then go for it.

## Commits
Commits are very easy to generate, simply create a private repo
named `test` so that it will look like you are testing GitHub
or any bug. Now, make sure that you turn on 
private commits in the API. Then you want to have say 2k
to 3k commits,
it does not mean you are coding, simply create a file
and for every change, even just a single letter, click commit.
That's the purpose of this hacking.

## Contributions
Contributions to repos are actually your repos and
repos of others when you create pull requests even
if they simply closed them. But of course, you can't create
spam. So, in order to achieve this, you want to focus
on a pull request even simply changing something at the 
README file of others. What I did was add a Page View.
If you click the README file of others, then click
the edit button, it will automatically create a fork 
(your copy of that particular repo) (we'll return to
forking later to generate stars).

## Forking Repos & Your Stars 
You can generate more stars by forking several repos
and placing the star for each fork.

Take note, this is not the stars in GitHub when you
leave a star to an external repo. This is the star
that you received from your forked repos and original
repos, your star to your own repo
or forked repo is counted also.
So, say, you fork 1k repos and you star them
by yourself, you will still have 1k stars and
it's part of the computation.

My suggestion is that you fork those small and
medium-sized projects. For one, it will
benefit them because those big projects,
they will simply ignore it. Plus, raising
an issue or a pull request in a big project
will be tedious. And the chances are high
if you want to change something even in the README
that it will be accepted.

## Followers
You don't need to be famous to have followers.
All you need is the initiative to follow others too.
It's just like building a linkedin network. 

The simple rule is try to reach out: follow others
that will follow you back and for those who followed
you, follow them back. The chances are high if you
look at those followers of a user even though
they are not actually famous or their profile is
not even good or they have also that kind of initiative.
Even though the weight is just .45, still
you need an audience to your project.


