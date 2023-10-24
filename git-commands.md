# **Git Commands**



| Command | Description |
| --- | --- |
| `git status` | List all new or modified files |
| `git diff` | Show file differences that haven't been staged |
| `git init` | Create an empty Git repository or reinitialize an existing one |
| `git clone` (followed by web URL or SSH key) | Create a local instance of a project |
| `git branch` | List existing branches |
| `git branch mysamplebranch` | Create a new branch |
| `git checkout mysamplebranch` | Switch to work on a different branch |
| `git switch mysamplebranch` | Switch to work on a different branch |
| `git branch -m newnamebranch` (have to be on the branch you want to rename while executing this command) | Rename branch |
| `git branch -m myoldbranch mynewbranch` (rename not currently checked out branch) | Rename branch |
| `git branch -d <branch name>` | Delete local branch |
|  `git add .` (adds all changed files) or `git add <file>` (adds a file of your choice)<br>`git commit -m 'some message'`<br>`git push` | Push changes to remote repository |
|  `git push -u origin <local-branch>` | "Uploading" a local branch for the first time |
| `git push -f origin <sample-branch>` | Force a push |
| `git fetch origin`<br>`git merge origin` | Pull updates from a remote repo to my local repo |
| if you encounter "Your local changes to the following files would be overwritten by merge" when tried to use `git merge origin`, use<br>`git stash push --include-untracked`<br>`git stash drop` | Stashes your changed file and then deletes using drop, so your changes are removed and repo is overwritten by the pulled changes |
| `git merge --abort` | Revert a pull |
| `git reset --hard origin/main` | Overwrite inconsistencies, beware your changes will be lost |
