## Basic Git Cheat Sheet

| Command | Description |
| --- | --- |
| git init | Initialize an existing directory as a Git repository |
| git clone https://git@github.com/[username]/[repository-name].git | Create a local copy of a remote repository|
| git status | show modified files in working directory, staged for your next commit |
| git add [file] | add a file as it looks now to your next commit (stage) |
| git diff | diff of what is changed but not staged |
| git diff --staged | diff of what is staged but not yet commited |
| git commit -m “[descriptive message]” | commit your staged content as a new commit snapshot |

### Create branch and rename branch 

| Command | Description |
| --- | --- |
| git branch | list your branches. a * will appear next to the currently active branch |
| git checkout -b [branch_name] | create new branch and switch this branch |
| git push [alias] [new_branch_name] | transmit new branch to remote repository |
| git checkout | switch to another branch |
| git branch -m [new_branch_name] | rename branch name |
| git push [alias] -u [new_branch_name] | transmit branch that renamed |
| git push [alias] -delete [old_branch_name] | delete old branch from remote |

### Sharing & Updating

| Command | Description |
| --- | --- |
| git push [alias] [branch] | Push a branch to your remote repository |
| git push -u origin [branch name] | Push changes to remote repository (and remember the branch) |
| git pull] | Update local repository to the newest commit |






