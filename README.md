# Git Lesson Collaboration

We are learning the mechanics for using git on our own. These are the same mechanics for colaborating with other people.
Playing with Git conflict resolution

Make a conflict on master

## Branching Commands

Show you everything that is going on
`git log --oneline --all --decorate --graph`

### Remove/reconcile changes between remote and local

`git fetch --prune`

### Remove branch from local workspace

`git branch -d <name>`

### Show branches

`git branch -a`

## Merging

- pull request merging branches on the github interface

- `merge <branch>:` merges the `<branch>` *into* current branch

- PR's only neeeds to be done once. Any new changes do not require a new PR

## Removing unwanted changes from commits

This will rollback commits up to the specific commit

`git reset --hard <commit_hash>`

## Collaborators and Conflicts

You can lock the master branch so that all changes to master come in as pull request
This is change that was made in a different branch. I am making this change because I locked the master branch

Conflicts will happen depending on the order of what gets merged

## Rebase and Cherry pick
When you want to update your branch with another, withou merging. For example updating your branch with bug fixes

- `rebase`: general change to history

- `cherry-pick` : 