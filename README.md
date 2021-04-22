# Basic Commands
##Create a directory
```shell
mkdir
```

##Delete a directory
```shell
rmdir
```

##Navigate
```shell
cd
```

##Compare the changes
```shell
git diff
```

##Find files, folders and inside files
```shell
find
```

##Create and edit text files
```shell
nano
```

##Get the status of the computer
```shell
git status
```

#Github w/examples
##Initial configuration
```shell
git config --global user.name "NajbiMaEs"
git config --global user.mail 2009090@upy.edu.mx
```

##Starting project from zero or clone
```shell
From zero:


Clone:
git clon NajbiMaEs-01@host/path/to/repository
```
##Basic workflow to stage and commit
```shell
git add README.md

git commit -m "firstcommit"
```

##Push to a remote repository
```shell
git push -u origin main
```

##Branches
```shell
Create: 
git checkout -b sandboxbranch

Delete:
git checkout -d texturesbranch

Commit:


Merge:
git merge gamebranch
```

##Gitflow
```shell
git flow init

git flow feature start gamebranch
```
