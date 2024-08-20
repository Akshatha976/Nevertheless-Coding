## Git Hidden Folder
## (backtick learn)
There is hidden folder called `.git` which tells you that your project is git repo

If we wanted to create a new project we would create the folder and then initialize that repo using `git init`

```
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch Readme.md
# make changes to Readme.md
code Readme.md
git status
git add Readme.md
git status
# shows 2 items here
# new file: Readme.md
# new file: gittutorials
# We definitely don't want to commit gittutorials, so will reset and add only Readme.md file and then commit
git reset
git commit  -m "add readme file"
```

```
git init
```



## Cloning

We can clone in three ways : HTTPS, SSH, GitHub CLI

Since we are using GitHub codespaces we will create a temporary directory in our workspaces

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```


```sh
git clone https://github.com/Akshatha976/gittutorials.git
```

## commits

```sh
git commit
```

Set the global editor

## Git Config filegit
the git config file is what stores your global configurations for git such as email, name, editor and more
```
git config --global core.editor emacs
```

## branches

## Remotes

## Stashing

## Merging

## Add

When you want to add all files (Staged) to be commit 

```
git add Readme.md
git add .
```

## Reset

Reset allows to move Staged changes to Unstaged
This is useful when you want to revert all files from Staging

```
git add .
git reset
```

> git reset will revert git add .

# Make a commit and commit message without opening an editor
```sh
git commit -m "add another exclamation"
```

## Log
git log will show  recent git commits to the git tree

## Push
when we want to push a repo to our remote origin

```sh
git 
```


## git commits 