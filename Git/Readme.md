# Git

## Topics covered
- [Git](#git)
  - [Topics covered](#topics-covered)
  - [What is git?](#what-is-git)
  - [Git Installation](#git-installation)
    - [Linux Users](#linux-users)
    - [Windows Users](#windows-users)
  - [Simple commands](#simple-commands)
    - [cd (change directory)](#cd-change-directory)
    - [ls (list)](#ls-list)
    - [mkdir (make directory)](#mkdir-make-directory)
  - [Git commands](#git-commands)
    - [Git config](#git-config)
    - [Git init](#git-init)
    - [Git Status](#git-status)
    - [Git add](#git-add)
    - [Git commit](#git-commit)
    - [Git log](#git-log)
    - [Git diff](#git-diff)
    - [Git reset](#git-reset)
    - [Git clone](#git-clone)
    - [Git pull](#git-pull)
    - [Git push](#git-push)
## What is git?
Git is a version control system, built to ease the work of developers and their team work.

Generally Git helps with:
- managing data backups and version archiving.
- Sharing codes and versions in a team of more than 2 developers.


## Git Installation

### Linux Users
```
sudo apt install git
```
### Windows Users
You can install git for windows from [this address](https://git-scm.com/download/win) Based on your OS.

## Simple commands 

### cd (change directory)
```
cd ./desktop
cd ../
cd /
cd ~
```
### ls (list)

```
ls
ls -a
ls -l
```
### mkdir (make directory)

```
mkdir foo
mkdir foo/foo1
```

## Git commands

### Git config
Set your personal data across your entire system 
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
### Git init
Initializes a local git repository in the present directory.
```
git init
```

### Git Status
Gives status of staging area, unstaged changes and the active branch.
```
git status
```

### Git add
Adds Unstaged changes to staging area.
```
git add
git add -a
```

### Git commit
Commits staged changes to local repository.
```
git commit -m "S.TH TO REMEMBER WHAT YOU DID!"
git commit -a //add and commit in one line command
```

### Git log
Get a log of commits made by users with detail.
```
git log
```

### Git diff
Shows differences between current stage and last commit.
``` 
git diff
```
### Git reset 
Unstage an staged file
```
git reset [file name]
```
undo a commit and return it to staged area.
```
git reset --soft Head^1
```
undo a commit and remove.
```
git reset --hard Head^1
```

### Git clone
Clone a remote project to your local system.
```
git clone [Repo http address]
git clone https://github.com/Ali-H1/Advanced-Programming-TA.git
```

### Git pull
Get the latest changes from remote repository and store it in local.
```
git pull
```

### Git push
Send the committed data in local repository to remote repository.
```
git push
```
