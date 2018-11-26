# Git Commands -- version control. 

### Get the git version.
* `git --version`

### Get the default user name and email.
* `git config user.name`
* `git config user.email`

### Set the default user name and email.
* `git config --global user.name "Som Shubham Sahoo"`
* `git config --global user.email "somshubhams@gmail.com"`

### Some folder cmd option
* `mkdir "folder name"` -> make a new directory
* `rmdir "folder name"` -> remove the directory
* `ls` -> list the directory
* `cd ..` -> come out from one directory
* `cd foldername` -> go into the directory

### Initialize The Git
* `git init`

### Check Git repository
* `git status`

### Git add files and folder
* `git add filename/foldername`
* `git add .`  will add all the changes 

### View changes mnade in git repo
* `git diff filename`

### Git commit files
* `git commit -m "Your commit msg"`

### To add a remote named 'origin' to your repository:
* `git remote add origin <URLFROMGITHUB>`
* `git remote set-url origin <URLFROMGITHUB>`

### To push the changes to a branch
* `git push origin branchname`

### View remote addresses
* `git remote -v`

### Pull in changes
* `git pull origin branchname`

## Forks And Clones

### git clone
* `git clone <PROJECTURL>`

### when you fork from a origin and want to add the url
* `git remote add upstream <ORIGIN_PROJECT_URL>`

### View remote connections
* `git remote -v`

### create a new branch
* `git branch branchname`
### checkout to a new branch 
* `git checkout branchname`
### create a branch and checkout
* `git checkout -b branchname` -> -b is for a new branch
### Rename a branch
* `git branch -m new-name`-> from the same branch
* `git branch -m old-name new-name`-> from the old branch
* `git push origin :old-name new-name`-> push the changes to rename

### List the branches
* `git branch`

### See changes to the remote before you pull in
* `git fetch --dry-run`


### Delete a local branch
* `git branch -d branchname`

### Delete a remote branch
* `git push origin --delete branchname`

### Merge Locally
* `git merge branchname`-> to make a merge checkout the target branch

### To pull from the original upstream:
* `git pull upstrem branchname`