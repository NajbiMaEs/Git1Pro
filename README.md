# Basic Commands
## To create a directory
```shell
mkdir
```

## To delete a directory
```shell
rmdir
```

## To navigate
```shell
cd
```

## To compare the changes
```shell
git diff
```

## To find files, folders and inside files
```shell
find
```

## To create and edit text files
```shell
nano
```

## To get the status of the computer
```shell
git status
```

# Github w/examples

## For initial configuration
```shell
git config --global user.name "NajbiMaEs"
git config --global user.mail 2009090@upy.edu.mx
```

## To start project from zero or clone
```shell
From zero:
git init
git cd "GameCode"

Clone:
git clon NajbiMaEs-00@host/path/to/repository
```
## For basic workflow to stage and commit
```shell
git add README.md

git commit -m "firstcommit"
```

## To push to a remote repository
```shell
git push -u origin main
```

## Branches
```shell
To create: 
git checkout -b sandboxbranch

To delete:
git checkout -d texturesbranch

To commit:
git push -u origin sandboxbranch

To merge:
git merge gamebranch
```

## Gitflow
```shell
git flow init

git flow feature start gamebranch
```
