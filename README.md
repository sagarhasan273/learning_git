![Screenshot of my project](https://github.com/sagarhasan273/learning_git/blob/master/git_command.png)



## <p align="center">Git Bash Command</p>

### Configuring Username and Email in git:

``` css
   git config --global user.name sagarhasan273
   ```
```
   git config --global user.name
   ```

```
   git config --global user.email sagarhasan273@gmail.com
```
```
   git config --global user.email
```
### Init Command:
```
   git init 
```
```
   ls -lart
```
```
   git status
```
[Good to use it]
```
   git commit -m "Initial commit"
```
```
   git config --global core.editor "code --wait"
```
### Untracked:
```
   git add index.html
```
[To add all]
```
   git add -A 
```
[Good to use it]
```
   git commit -m “Initial commit” 
```
### If git commit create a problemPress I and write “INITIAL COMMIT” + Esc + : + w + q

### Unmodified & Modified:
[if mistakenly gets updated]
```
   git checkout index.html 
```
```
   git checkout -f
```
### Staged:
[show all commit messeges]
```
   git log 
```
```
   git log -p -1
```
[compare with your saved file and after editing file]
```
   git diff 
```
[ will only show changes to files in the "staged" area.]
```
   git diff --staged 
```
```
   git commit -a -m "adding waste.html"
```
 [remove from staged area]
```
   git rm --cached waste.html
```
[to delete]
```
   git rm waste.html 
```
```
   git commit -a -m "deleting waste.html"
```

### .gitignore

/log/mylog.log

*.log

### Create a new repository on the command line

### echo "# learning-git" >> README.md
```
   git init
```
```
   git add README.md
```
```
   git commit -m "first commit"
```
```
   git branch -M main
```
```
   git remote add origin https://github.com/sagarhasan273/learning-git.git
```
```
   git push -u origin main
```
### push an existing repository from the command line
```
   git remote add origin https://github.com/sagarhasan273/learning-git.git
```
```
   git branch -M main
```
```
   git push -u origin main
```
```
   git pull origin main
```
### Branch:
```
   git branch main
```
```
   git branch
```
```
   git checkout main
```
```
   git merge main
```
```
   git checkout -b mainlite
```
### Other:
```
   explorer filename
```
```
   start filename
```
### If you failed to push some refs to:
```
   git pull --rebase origin main/master
```
```
   git push -f origin branch-name
```
### To see a list of all branches in the repository:
```
   git branch -a
```
###  To switch to a branch:
```
   git checkout my-branch
```
