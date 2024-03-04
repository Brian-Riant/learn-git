# Git is a version control system

--Records the changes of the project in a repository

## Table of Contents

- [Creating Snapshots](#create-snapshots)
- [Browsing History](#browsing-history)
- [Branching & Merging](#branching-merging)
- [Collaboration](#collaboration)
- [Rewriting History](#rewriting-history)

## Functions

-Being able to quckly revert back to the original
-Corabollation is made posible

## Types of version control systems

--**Centralised** version control e.g version and teamfoundation
--**distributor**version control e.g. git and mercurial

## app to use

-**termianl** or the command line iterface
-**Gitkraken** GUI, github desktop and sourcetree

## Settings configuration

## Level of configuration

--- **System**- all users
--- **Global** - all repositories of the current user
--- **Local** - For the current repository

 ```git config --global user.name "[username]"```
 ```git config --global user.email [email address]```
 ```git config --global core.editor "code"``` /*sets vscode as the default editor for git*/
 ```git config --global -e``` /*opens config file*/ 
 ```git config --global core.autocrlf``` [set to'true' for windows 'input' for mac and Linux ]

--Note: end of lines of windows are '\r' carriage return or '\n' and '\n' linefeed
--Note: core.autocrlf is --> carriage return line fit

 ```git config --help```
 ```git config -h ``` /*for a short help

## creating snapshots

### initializing a repository


```git init```


### Staging files

```git add file1.js```
```git add file1.js file2.js```
```git add *.js```
```git add .```


### viewing the status

```git status```    --fullstatus
```git status -s``` --short status


### committing the satged files

```git commit -m "message"``` --commits with a one-line message
```git commit```  --opens the default editor to type a long message


### skipping the the staging area

```git commit -am "message"``` --

### Removing files

```git rm file1.js``` _Removes from working directory and staging area_
```git rm --cached file1.js```  _Removes from staging area_

### Viewing the staged/unstaged changes

```git diff``` _show  unstaged changes_ 
```git diff --staged``` _show staged changes_
```git diff --chached``` _same as the above_

### Viewing the history

```git log``` *Full history_
```git log --oneline```*summary_
```git log --reverse```*list the commits from the oldest to the newest_


### viewing a commit

```git show 92a2ff``` _show a given commit_
```git show HEAD``` _show the last commit_
```git show HEAD-2```_Two steps before the last commit_ 
```git show HEAD:file.js``` _shows the version of file.js stored in the last commit*


