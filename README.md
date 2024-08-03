# The GitHub Stats Guide

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
1. Create a repository with the same name 
   as your username (e.g., `jdevfullstack/jdevfullstack`). 
   This special repository will appear in your profile.
2. Initialize it with a `README.md` file, or create one if it doesn't exist.
3. Add a description about yourself and include the following 
   code, replacing `[yourusername]` with your GitHub username :
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
contributions. Remember, GitHub Stats can sometimes 
be misleading, even for highly skilled developers.

If you only use GitHub for coding, your profile might not 
fully reflect your abilities. GitHub encourages a variety 
of activities beyond just coding, such as participating in 
discussions, reviewing code, and contributing to 
documentation.

Think of GitHub as more than just a coding platform — 
it's an interactive space similar 
to any other social media. Engaging in 
diverse activities on GitHub can provide a more accurate 
representation of your contributions and skills.

If you believe you deserve a higher rank, actively 
participate in the community and showcase your full range 
of abilities. This is why we have this *unofficial* ranking.

## Commits
If you did create your own instance of the app like
[this](https://github.com/anuraghazra/github-readme-stats?tab=readme-ov-file#deploy-on-your-own),
make sure you turn on private commits 
in the API `include_all_commits=true`. 
For sure, if your private commits are massive, 
like you are privately coding, professionally or personally,
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

- contributing to documentation for open-source projects
- participating in discussions and issue tracking
- creating and maintaining wikis
- managing project boards and tasks
- uploading design assets or artwork
- sharing research notes or academic papers

For more information on creating websites with GitHub, 
check out 
[this tutorial](https://github.com/jdevfullstack/github-pages-tutorial) about GitHub Pages.

## Pull Requests
Pull requests are a great way to contribute to projects and 
generate activity on your GitHub profile. They are not 
limited to coding; you can create pull requests for various 
types of contributions : 

- **Documentation**: Improve or add documentation for 
  projects. This can include README files, wikis, or 
  tutorials.
- **Design**: Contribute design assets, such as logos, 
  icons, or UI/UX improvements.
- **Translations**: Help translate project documentation 
  into different languages.
- **Bug Reports**: Identify and document bugs, and propose 
  fixes or improvements.
- **Community Management**: Suggest improvements for 
  community guidelines, code of conduct, or contribution 
  guidelines.
- **Educational Content**: Add educational resources, such 
  as example projects, code snippets, or learning materials.

By contributing in these ways, you can create meaningful 
pull requests that benefit the community and enhance your 
GitHub profile.

## Your Stars 
Take note, this is not the stars on GitHub when you
leave a star to an external repo. This is the star
that you received from your original repos.

So keep on creating quality content on GitHub, 
code or non-code !

## Followers
You don't need to be famous to have followers. All it takes 
is the initiative to follow others. It's similar to building 
a LinkedIn network.

Be proactive: follow others who are likely to follow you 
back, and reciprocate by following those who follow you. The 
chances are high if you follow those who are also looking to 
build their network. For example, I am not famous, but I 
have more than 3k followers.

In the past, when I started doing this, 
I was surprised by the increase in web traffic to
my site, as shown by Google Analytics.

Remember, even if some don't follow back, keep following 
more people. This act is like free advertisement: others 
will become aware of your content. Unlike paid promotions, 
following others costs nothing but has a similar effect.

However, don't overdo it on GitHub. Following too many 
people in a short period can clutter your followers' 
dashboards, potentially annoying them. Be mindful and 
considerate in your approach.

## More Of My Content
- [jdevfullstack Profile](https://github.com/jdevfullstack)
- [jdevfullstack Repos](https://github.com/jdevfullstack?tab=repositories)
- [jdevfullstack Projects](https://github.com/jdevfullstack-projects)
- [jdevfullstack Tutorials](https://github.com/jdevfullstack-tutorials)
