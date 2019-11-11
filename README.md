# O'Reilly Git Collaboration

We are learning the mechanics for using git on our own. These are the same mechanics for colaborating with other people.
Playing with Git conflict resolution

Make a conflict on master

## Branching Commands

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

## Collaborators and Conflicts

You can lock the master branch so that all changes to master come in as pull request
This is change that was made in a different branch. I am making this change because I locked the master branch

Conflicts will happen depending on the order of what gets merged
