# Git – Quick Reference
## Repository Initialization
`git init`
> Initialize a Git repository in the current working directory.

`git init -b <branch-name>`
`git init --initial-branch=<branch-name>`
> Set the initial branch name. `master` by default if not specified.
<br>

`git clone <repository> [<directory>]`
> Clone a remote repository to either the specified directory or (if not specified) a new directory under the current working directory.

`git clone <repository> -o <remote-name>`
`git clone <repository> --origin <remote-name>`
> Set the remote name to keep track of the upstream repository. `origin` by default if not specified.

## Repository Configuration
`git config user.name <name>`
> Set the name of both the author and the committer.

`git config user.email <email>`
> Set the email of both the author and the committer.
<br>

`git config author.name <name>`
> Set the name of the author.

`git config author.email <email>`
> Set the email of the author.
<br>

`git config committer.name <name>`
> Set the name of the committer.

`git config committer.email <email>`
> Set the email of the committer.

## Branching
`git branch [--list] [--all]`
> List the existing branches.
<br>

`git branch <branch-name>`
> Create a branch.

`git switch -c <branch-name>`
`git switch --create <branch-name>`
> Create a new branch and switch to it.

`git switch <branch>`
`git checkout <branch>`
> Switch to the specified branch.
<br>

`git branch -m <old-branch> <new-branch-name>`
> Rename a branch.

`git branch -m <new-branch-name>`
> Rename the current branch.
<br>

`git branch [<branch>] -u <upstream>`
> Set the upstream branch.

## Updating
`git status`
> Show the working tree status.
<br>

`git add [<file>]`
`git add [<directory>]`
> Add the specified object to the index.

`git add -A`
`git add --all`
> Update the index with all files in the entire working tree.
<br>

`git commit`
`git commit -m “<message>”`
> Record changes to the repository.

`git commit -a`
`git commit --all`
> Stage all modified and deleted files but not new files.

`git log`
> Show commit logs.
<br>

`git merge <branch>`
> Merge the specified branch into the current branch.

## Remote
`git fetch`

`git pull`

`git push`
