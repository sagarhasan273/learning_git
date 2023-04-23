## <p align="center">Git Bash Command</p>

### Configuring Username and Email in git:
$ git config --global user.name sagarhasan273

$ git config --global user.name

$ git config --global user.email sagarhasan273@gmail.com

$ git config --global user.email

### To Open VsCode:

$ code .

### Init Command:

$ git init 

$ ls -lart

$ git status

$ git commit -m "Initial commit" [Good to use it]

$ git config --global core.editor "code --wait"

### Untracked:

$ git add index.html

$ git add -A [To add all]

$ git commit -m “Initial commit” [Good to use it]

### If git commit create a problemPress I and write “INITIAL COMMIT” + Esc + : + w + q

### Unmodified & Modified:

$ git checkout index.html [if mistakenly gets updated

$ git checkout -f

### Staged:

$ git log [show all commit messeges]

$ git log -p -1

$ git diff [compare with your saved file and after editing file]

$ git diff --staged [ will only show changes to files in the "staged" area.]

$ git commit -a -m "adding waste.html"

$ git rm --cached waste.html [remove from staged area]

$ git rm waste.html [to delete]

$ git commit -a -m "deleting waste.html"

$ mkdir foldername

$ touch 

### .gitignore

/log/mylog.log

*.log

### Create a new repository on the command line

### echo "# learning-git" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/sagarhasan273/learning-git.git

git push -u origin main

### push an existing repository from the command line

git remote add origin https://github.com/sagarhasan273/learning-git.git

git branch -M main

git push -u origin main

git pull origin main

### Branch:

$ git branch main

$ git branch

$ git checkout main

$ git merge main

$ git checkout -b mainlite

### Other:

$ explorer filename

$ start filename

### If you failed to push some refs to:
$ git pull --rebase origin main/master
$ git push -f origin [branch-name]
