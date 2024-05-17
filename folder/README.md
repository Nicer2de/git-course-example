# Example Git Repository

We are learning how to make commits.

1. make some changes.
2. get add -- "stage" the changes that we want to persist to our git history
3. git commit -m "adding ..." -- creates a commit

We are about to make a commit without best practices.

goodbye

docs

repositories, branches, commits, tags

# created the repo locally
local repository -> "remote" repository (git add remote <name> <URL>)

# created the repo remotely
git clone <URL>

# create a branch locally
git checkout <branch>
git checkout -b <new_branch>
git add ...; git commit -m "..." (several times)
git push --set-upstream origin <new_branch>
git pull [origin <new_branch>]

# create a new branch remotely
using the Github UI to create <branch>
git fetch --all
git checkout <branch>