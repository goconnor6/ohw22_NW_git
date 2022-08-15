# Git exercise for OHW22 NW satetllite

We'll use this repository as the sand box for practicing using Git and GitHub.

- Make sure everyone's comfortable with the basics:
  - create a repository on GitHub
  - git clone
  - git add
  - git commit
  - git push
- We'll then try out the fork-branch-pull request workflow:
  - fork (on GitHub)
  - clone (to your own machine): `git clone FORKED_REPO`
  - set remote (on your own machine): `git remote add REMOTE_NAME REPO` (e.g. `git remote add upstream upstream_repo.git`)
  - create a branch (on your own machine): `git checkout -b BRANCH_NAME`
  - make changes add/commit/push (to your own fork): `git push` (git will suggest something if something doesn't already exist)
  - create a pull request, or "PR" (on GitHub)
  - merge the PR (on GitHub)
  - pull down the changes (on your own machine): `git pull REMOTE_NAME BRANCH_NAME`
