# aliases

Here be aliases, mostly for git.

## cb

Change branch. Takes 1 parameter, the branch to change to. Fetches remote branches first.

## nb

Create new branch. Takes 1 parameter, the branch to create. Pushes to remote.

## gc

Git commit all local changes. Takes 1 parameter, the message to include.

## gcp

Git commit and push all local changes. Takes 1 parameter, the message to include. Pulls remote changes before pushing to reduce merge conflicts.

## msi

Creates a mob branch based on the current branch including local changes. Requires [mob.sh](https://mob.sh) to be installed. 