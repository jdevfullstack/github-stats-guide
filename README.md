# Hacking The GitHub Stats

*`updated July 26, 2024`*

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fxdvrx1%2Fhacking-the-github-stats&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=PAGE+VIEWS&edge_flat=false)](https://hits.seeyoufarm.com)

The [GitHub Stats](https://github.com/anuraghazra/github-readme-stats) is an 
external service that displays your ranking based on commits, PRs, issues, 
etc. You simply need the URL, change the details to refer to your account, 
include it in your GitHub profile, and you're done.

## How It Works
- GitHub Stats is an external web app that uses GitHub data (through its API) 
  to generate your rank.
- No installation is required; just get the URL of the app, change the details 
  to refer to your account, and you're done.
  
  ```
  https://github-readme-stats.vercel.app/api?username=[yourusername]
  ```

## Displaying in Your Profile
1. Create a repository with the same name as your username (e.g., `jdevfullstack/jdevfullstack`). 
   This special repository will appear in your profile.
2. Initialize it with a `README.md` file, or create one if it doesn't exist.
3. Add a description about yourself and include the following code, replacing `[yourusername]` with your GitHub username:
   ```html
   <p align="left"> <img src="https://github-readme-stats.vercel.app/api?username=[yourusername]&theme=tokyonight&show_icons=true&hide_border=true&count_private=true&include_all_commits=true" /> </p>
4. The stats are now embedded in your GitHub Profile! You can still change the 
   settings. Refer to the details [here](https://github.com/anuraghazra/github-readme-stats).

## App Stat Computation Breakdown
This is the latest computation and the factors involved:

- **Commits**: 16.67%
- **Pull Requests (PRs)**: 25%
- **Issues**: 8.33%
- **Reviews**: 8.33%
- **Stars**: 33.33%
- **Followers**: 8.33%

Refer to the code for detailed information: [calculateRank.js](https://github.com/anuraghazra/github-readme-stats/blob/master/src/calculateRank.js)

## Rationale
This is not about tricking the system or creating fake 
contributions. It is important to understand that GitHub 
statistics can sometimes be misleading, even for highly 
skilled developers.

If you only use GitHub for coding, your profile might not 
fully reflect your abilities. GitHub encourages a variety 
of activities beyond just coding, such as participating in 
discussions, reviewing code, and contributing to 
documentation.

Think of GitHub as more than just a coding platform—it's a 
collaborative space similar to Google Docs. Engaging in 
diverse activities on GitHub can provide a more accurate 
representation of your contributions and skills.

If you believe you deserve a higher rank, actively 
participate in the community and showcase your full range 
of abilities. This is why we have this *unofficial* ranking.

## Commits
If you did create your own instance of the app
[like this](https://github.com/anuraghazra/github-readme-stats?tab=readme-ov-file#deploy-on-your-own),
make sure you turn on private commits 
in the API `include_all_commits=true`. 
If you are privately coding, professionally or personally,
that will be counted.

Another option is to create a tutorial website, tech or non-tech. 
Markdown, originally designed for 
blogging, simplifies creating content. It is the default 
markup language for GitHub, especially for README files.

If you are a writer, consider writing your stories on 
GitHub. Many people use GitHub for various purposes, such 
as legal articles, to-do lists, music compositions, and 
itineraries.

Additionally, you can generate commits by:

- Contributing to documentation for open-source projects.
- Participating in discussions and issue tracking.
- Creating and maintaining wikis.
- Managing project boards and tasks.
- Uploading design assets or artwork.
- Sharing research notes or academic papers.

For more information on creating websites with GitHub, 
check out 
[this tutorial](https://github.com/xdvrx1/github-pages-tutorial) about GitHub Pages.

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
than 1k followers (as of this writing).
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

## More Of My Content
- [jdevfullstack Profile](https://github.com/jdevfullstack)
- [jdevfullstack Repos](https://github.com/jdevfullstack?tab=repositories)
- [jdevfullstack Projects](https://github.com/jdevfullstack-projects)
- [jdevfullstack Tutorials](https://github.com/jdevfullstack-tutorials)
