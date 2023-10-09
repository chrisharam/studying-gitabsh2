# studying-gitabsh2

## How to save new updated files?
 -1 Changes : storing data as changes to the base version
 -2 Snapshots : storing data as snapshots

## What is Snapshots?  ***Three states in git***
stage fixes - modified files(working directory)  
commit - staged(staging area that can be used for place to write new things and delete)  
checkout the project - commited(a final submit of git directory that you edited)

------------------------------

## shell commands
```sh
$ git config --list : shows each level overidden
$ git init : initializes a repository in an existing directory
$ git status: checking repository
$ git add [file_name]: adding a new file to be staged(editting mode) 
$ git add . : adding all files to be staged
$ git rm -cached [file_name] : unstaging a file
$ nano .gitignore : ignoring a file permantly
$ git commit -m "commit message that you want to leave" : commit
```

--------------------------------------

## Git config : First-time Setup
 -1 System level : affects all ueses and repositories
 -2 Global level : affects all repositories
 -3 local level : specific to the current repository

these three levels are overridden values in the previous level like this,
system -> global -> local
 ------------------------------

## staged level(editing mode) caution
if you don't save the newest version, there can be some errors like untracked files.
so you must save and check the new edited files and version before commit!












 
