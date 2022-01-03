# Here is some Basic Github Commands

## Here I will describe every part individually and I will add some basic Commands which will Help you to manage basic uses of github

### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
|1. `git init` | To create a local git repository for us in our store folder.This will help to manage the git commands for that particular repository  |
|2. `git clone ssh://git@github.com/[username]/[repository-name].git` | To Create a local copy of a remote repository in your device |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
|1. `git status` | To see all the files that have been added and modified and ready to be commmitted and files which are untracked |
|2. `git add [filename.txt]` | To add a specific list of files to staging area |
|3. `git add .` | To add all new and changed files to the staging area |
|4. `git commit -m "Your-commit-text"` | To commit our changes and providing a message to remember for future reference |
|5. `git rm -r [file-name.txt]` | To remove a file (or folder) |

### Create Branch and Merge Them 

| Command | Description |
| ------- | ----------- |
|1. `git branch` | To see all the branches present and current branch that we are working on |
|2. `git branch -a` | To list all branches |
|3. `git branch [branch name]` | To create a new branch |
|4. `git branch -d [branch name]` |To delete a branch |
|5. `git push origin --delete [branch name]` | To Delete a remote branch |
|6. `git checkout -b [branch name]` | To Create a new branch and switch to it |
|7. `git checkout -b [branch name] origin/[branch name]` | To Clone a remote branch and switch to it |
|8. `git branch -m [old branch name] [new branch name]` | To Rename a local branch |
|9. `git checkout [branch name]` | To switch to a branch |
|10. `git checkout -` | To Switch to the branch last checked out |
|11. `git checkout -- [file-name.txt]` | To Discard changes to a file |
|12. `git merge [branch name]` | To Merge a branch into the active branch |
|13. `git merge [source branch] [target branch]` | To Merge a branch into a target branch |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
|1. `git push origin [branch name]` | Push a branch to your remote repository |
|2. `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
|3. `git push` | Push changes to remote repository (remembered branch) |
|4. `git push origin --delete [branch name]` | Delete a remote branch |
|5. `git pull` | Update local repository to the newest commit |
|6. `git pull origin [branch name]` | Pull changes from remote repository |
|7. `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
|8. `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
|1. `git log` | View changes |
|2. `git log --summary` | View changes (detailed) |
|3. `git log --oneline` | View changes (briefly) |
|4. `git diff [source branch] [target branch]` | Preview changes before merging |

