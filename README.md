### Common Git commands
+ Configuring Git identity:  
`git config --global user.name "John Doe"`  
`git config --global user.email johndoe@example.com`  
+ View Git configuration:  
`git config --list --show-origin`  
+ Create new git:  
`mkdir <git_name>`  
+ Init a new Git repo:  
`git init`  
+ Adding a file to staging mode:  
`git add <file_name>`  
+ Adding all files to a local Git repository:  
`git add .`  
+ Commit a file in staged mode to a project:  
`git commit -m "Initial project1 files"`  
+ Commit a file in staged mode to a project, while allowing future undo:  
`git commit --amend -m "an updated commit message"`  
+ Store changes on database without commit:  
`git stash --all -m "my work at at iss53"`  
+ Show stash changes:  
`git stash list`  
+ Return working on stash changes:  
`git pop --index <index_ID>`  
+ Show who is the commit parent:  
`git cat-file -p <commit_ID>`  
+ Revert a committed file to a staged mode:  
`git restore --staged <file_name>`  
+ Discard changes of specific file in the working directory:  
`git restore <file_name>`  
+ Clone a repository:  
`git clone <URL>.git`  
+ Displays the state of the working directory and the staged snapshot:  
`git status`  
+ Show information about the past 5 commits:  
`git log -5`  
`git log -n 5`  
+ Show information about which files were committed and the number of lines that were added or deleted:  
`git log --stat`  
+ Show information about commit in a single or one line:  
`git log --pretty=oneline`  
+ Show all branches:  
`git branch -ra`  
+ Viewing git remote repository:  
`git remote`  
`git remote -v`  
+ Creating a new remote Git repository:  
`git remote add <name> <url>`  
+ Deleting a remote Git repository:  
`git remote rm <name>`  
+ Rename a remote Git repository:  
`git remote rename <old-name> <new-name>`  
+ Inspect a remote Git repository:  
`git remote show upstream`  
+ Git Ignore synatx:  
	https://github.com/github/gitignore  
	https://www.atlassian.com/git/tutorials/saving-changes/gitignore  
+ Pushing a file to a local Git repository:  
`git push`  
+ Pushing a file to a remote Git repository:  
`git push <remote-name> <branch-name>`  
+ Pushing a file to a remote Git repository including local tags:  
`git push <remote> --tags`  
+ Show the last commit of files:  
`git show <Commit_ID>`  
+ Show changes between two commits:  
`git diff [1stCommitID] [2ndCommitID]`  
+ Revert to previous commit state:  
`Git checkout [commitID]`  
+ Revert to the master state:  
`git checkout master`  
+ Download the content of a remote Git repository, without changing local repository working state:  
`git fetch <remote>`  
+ Download the content of a specific branch from a remote Git repository, without changing local repository working state:  
`git fetch <remote> <branch>`  
+ Download the content of a remote Git repository:  
`git pull <remote>`  
+ List tags in a repository:  
`git tag`  
+ Search for a specific TAG Pattern:  
`git tag -l "v1.8.5*"`  
+ Create an Annotated Tags:  
`git tag -a v1.4 -m "my version 1.4"`  
+ Create a tag to an existing commit:  
`git tag -a v1.0 <first_7_letters_of_a_commit>`  
+ Show a specific tag description:  
`git show v1.4`  
+ Delete an existing tag:  
`git tag -d <tag_name>`  
+ Create a new branch, without switching to the new branch:  
`git branch <branch_name>`  
+ Show Git branch pointers:  
`git log --oneline --decorate`  
+ Switch to a specific Git branch:  
`git checkout <target_branch_name>`  
+ Create a new branch and switch to the new branch:  
`git checkout -b <branch_name>`  
+ Merge a Git branch into the main Git repository:  
`git checkout <main_repository_name>`  
`git merge <branch_name>`  
+ Show diff between commits:  
`git diff <commitID1> <commitID2>`
