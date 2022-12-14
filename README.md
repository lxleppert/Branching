## Git and Git Branching Cheat Sheet

Categories of git commands, and practice with branching
Practice with m erging and merge conflicts.

### Basic commands
* `git init` - initialize current directory with repository
* `git add .` - add all new or changed files in current directory to git index, staging them for commit
* `git commit -m "some message"` - commit staged changes to local repository

### Info commands
* `git status` - show status of current working directory
* `git log` - list commit history
* `git log --oneline` - list commit history (compact)

### Branch commands
* `git branch` - list local branches, highlight current branch
* `git branch [branchName]` - create `branchName`
* `git checkout branchName` - switch to branch `branchName`
* `git checkout -b otherBranch` - switch to branch `otherBranch`, creating it if it doesn't exist

### Remote commands
* `git remote add origin someUrl` - connect local repo to remote repo url as `origin`
* `git push origin branchName` - push local commits to remote repo into branch `branchNme`
* `git pull origin branchName` - pull remote branch `branchName` into local current branch

### Other commands
* `git help` - list subcommands and options
* `git help config` - show for `git config`
* `git config -l` - list local git configuration settings

