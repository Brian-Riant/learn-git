# Git is a version control system

--records the changes of the project in a repository

## Table of Contents

- [Creating Snapshots](#create-snapshots)
- [Browsing History](#browsing-history)
- [Branching & Merging](#branching-merging)
- [Collaboration](#collaboration)
- [Rewriting History](#rewriting-history)

## Functions

-being able to quckly revert back to the original
-corabollation is made posible

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

     ```bash  
     git config --global user.name "Brian-Rinat"
     git config --global user.email brainriant@gamil.com
     git config --global core.editor "code--wait" /*sets vscode as the default editor for git*/
     git config --global -e /*opens config file*/ 
     git config --global core.autocrlf [set to'true' for windows 'input' for mac and Linux ]
     ```
--Note: end of lines of windows are '\r' carriage return or '\n' and '\n' linefeed
--Note: core.autocrlf is --> carriage return line fit

   ```bash
    git config --help
    git config -h /*for a short help
   ```

## creating snapshots

### initializing a repository
>
> git init
>

### Staging files
>
>git add file1.js
>git add file1.js file2.js
>git add *.js
>git add .
>

### viewing the status
>
>git status    --fullstatus
>git status -s  --short status
>

### committing the satged files
>
>git commit -m "message" --commits with a one-line message
>git commit  --opens the default editor to type a long message
>

### skipping the the staging area
>
>git commit -am "message" --
