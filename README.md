# Git-Github-practice
This repository is for practicing git commands

NOTE: when pushing changes on command line interface instead of password you must use a Personal Acces Token.

## Basic commands
1- Used to link your email to your commits. (needed to update a remote repo on Github from your local repo)
```
git config --global user.email "your_email@example.com"
```
2- Also used to link your github name to your commits.
```
git config --global user.name "yourname"
```
3- Cloning a repository
```
git clone https://github.com/Myname01/repo-name.git
Cloning into 'repo-name'...
```
```
Username for 'https://github.com': Myname01
Password for 'https://Myname01@github.com': (use a valid Personal Access Token)
```
4- Used to initialize a new Git repository (create a subfolder .git) and a new main branch
```
git init
```
5- shows the working tree status
```
git status
```
