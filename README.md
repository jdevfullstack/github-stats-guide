# Hacking The Github Stats
The [GitHub Stats](https://github.com/anuraghazra/github-readme-stats) 
is an external service to display your ranking based on commits, PRs,
contribution etc.

There is the computation for that:

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
