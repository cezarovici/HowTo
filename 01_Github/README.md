
## Github commands

### To initialize GitHub Repository in your local machine project folder:
```
git init
```
### To get the status of files::
```
git status
```

### create a new repository on the command line
```
echo "# HowTo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:cezarovici/HowTo.git
git push -u origin main
```
### push an existing repository from the command line
```
git remote add origin git@github.com:cezarovici/HowTo.git
git branch -M main
git push -u origin main
```
### To configure Username and Password::
```
git config –global user.name "user-name”
git config –global user.email "email-id"
```
### To clone the repository to your local machine:

```
git clone git@github.com:cezarovici/name-of-project.git
```
### To add a single file to GitHub:
```
git add file-name
```
### To add all the modified file to GitHub:
```
git add .
git add -A
```
### To commit the changes to GitHub:
```
git commit -m “commit-message”
```
### Get the latest code from the main branch
```
git pull
```
### To pull the latest code from a particular branch
```
git pull branch-name
```
### To list all the branches including local and remote:
```
git branch -a
```
### To delete a branch
 ```
git branch -d branch-name
```
### To discard changes of a particular file
```
git checkout -- file-name.txt
```
### Merging branch (active branch):
```
git merge branch-name
```
### Merging to a target branch
```
git merge source-branch target-branch
```
### Stash your changes
```
git stash
```
### Remove stash
```
git stash clear
```
### Show difference
```
git diff source-branch target-branch
```
### To view the log/changes
```
git log
```
### Detailed view of log/changes:
```
git log --summary
```
### Brief view of log/changes
```
git log --online
```
### Get the help:
```
git help
```
### To go back to the previous commit/changes
```
git reset --hard
```
### List stashed files
```
git stash list
```
### Come out of stash (write working from the top of stash stack):
```
git stash pop
```
### Going back to HEAD:
```
git reset --soft HEAD
```
### Going back to the commit before HEAD:
```
git reset --soft HEAD^
```
### Equivalent to "^":
```
git reset --soft HEAD~1
```
### Going back two commits before HEAD
```
git reset --soft HEAD~2
```
### To set the current tag to v0.0.1
```
git tag -a v0.0.3 -m “version 0.0.3”
```
### To delete the file from your working directory:
```
git rm file-name
```
### To show the metadata and content changes of the specified commit
```
git show commit-name
```
### To delete a branch
```
git branch -d branch-name
```
### Search the working directory for "add()":"
```
git grep "add()"
```
### List of branches:
```
git branch
git branch --list
```
### Undo the changes
```
git log --oneline
git revert commit-id
```
### To delete a file forcefully:
```
git rm -rf file-name
```
### To get the Git version
```
git branch
git branch --list
```