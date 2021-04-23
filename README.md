# Hacking The Github Stats
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fxdvrx1%2Fhacking-the-github-stats&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=PAGE+VIEWS&edge_flat=false)](https://hits.seeyoufarm.com)

The [GitHub Stats](https://github.com/anuraghazra/github-readme-stats) 
is an external service to display your ranking based on commits, PRs,
issues etc. You just simply need the URL and change the details,
include it in your GitHub profile and you're done.

If you don't have any idea how it works, it is an external web app
that uses GitHub data (through its API) to generate your rank. 
You don't need to install anything, you just simply get the URL
of the app, change the details so that it's referring to your account
and you're done.

```
https://github-readme-stats.vercel.app/api?username=[yourusername]
```
make sure you include your private repos, `&count_private=true`.

Now, in order for you to display this in your profile,
if ever you don't have one, make sure you create one.
Create a repository with the same name as your username.
It is a special repository that will appear in your profile.

so mine is: `xdvrx1/xdvrx1`

Make sure that you initialize it with the `README.md`, if not,
you should create one also.

Add description about you and this, of course, you must change
the details:

```
<p align="left"> <img src="https://github-readme-stats.vercel.app/api?username=[yourusername]&theme=tokyonight&show_icons=true&hide_border=true&count_private=true&include_all_commits=true" /> </p>
```
It's now embedded in your GitHub Profile! You can still change 
the settings. Refer to the details [here](https://github.com/anuraghazra/github-readme-stats).

## App Stat Computation Breakdown
The breakdown of the components:

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
Much more, this should not be interpreted as spam.

But remember, the stats of GitHub can be misleading
even if a software developer is good enough.

If you only use GitHub to code and code, you
would not have a good standing. GitHub
encourages non-code use, always remember that.
It's just like it can be used as Google Docs.
That's the point.

If you really feel that you deserve that rank,
then go for it.

## Commits
Make sure that you turn on 
private commits in the API, as was
instructed above, so that you can simply
create a diary, for example. It will generate 
a lot of commits.

Another option is to simply create a tutorial website,
even if it is not tech-related. Don't you know
that the markdown is really for blogging back then?
(Don't get me wrong, blogging is still relevant today.)
It simplifies everything, even a tutorial website.
Markdown is the default markup language of GitHub,
particularly for the README file.

Or, if you are a writer writing stories, do that in
GitHub. Others were already using GitHub for
laws articles, to-do lists, music compositions,
itineraries etc.

You can check 
[this](https://github.com/xdvrx1/github-pages-tutorial)
out if you are not familiar
with GitHub Pages.

## Contributed To
The `Contributed To` component as part of the 
computation is when you create pull requests
and are merged to the `main` branch. 

It's not always about submitting
proposed changes in a code base,
even simply changing something at the 
README file of others will do. What I did was 
a pull request to add a Page View on a README file.
If you click the README file of others, then click
the edit button, it will automatically create a fork.
Then, edit the file and create a pull request.

## Your Stars 
Take note, this is not the stars on GitHub when you
leave a star to an external repo. This is the star
that you received from your original repos.

## Followers
You don't need to be famous to have followers.
All you need is the initiative to follow others too.
It's just like building a linkedin network. 

The simple rule is trying to reach out: follow others
that will follow you back and for those who followed
you, follow them back. The chances are high if
you follow those who are willing to follow others too.
My example is myself, I
am not even a famous, but I already have more 
than 1k followers.
And even though the weight is just .45, 
you still need an audience for your projects.
That's really a good reason to pursue this.

When I started doing these things, I was shocked
when I visited my Google Analytics for my site.
The web traffic was good.

And now, I realized one more thing: even if
others don't follow back, just continue following
more and more. Remember, others are paying
for their page to be promoted on other
sites, the act of following others is just
like an advertisement also: others will
know your content. The only difference
is that you don't pay following
others but with the same advertisement 
effect.

Just don't overdo it much on GitHub, because
it will appear on the dashboard of your
followers and if you follow, say, more
than 200 without a gap, their dashboard
will be clogged with that and all
the other necessary information for them
will be removed automatically. They will
be annoyed by that, for sure.
