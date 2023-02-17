# git-custom-commands

## Commands

### `git done`

:hammer: Workflow: Working on a local branch, pushing to GitHub, and merging the PR. We want the updates to our main branch, and want to remove the clutter of the old local branch where we did all the work.

:memo: Steps:
1. Note the current branch
2. Note the main branch
3. Checkout the main branch
3. Pull any updates
4. Hard delete the previous branch 

### `git append`

:hammer: Workflow: We thought we had finished the work and pushed it to GitHub. But then we discover a typo, bug, etc and want to fix it, include it in the last commit and then force push the updates to GitHub.

:memo: Steps:
1. Add the most recent changes into the last commit cleanly
2. Force push to GitHub (`origin`)
