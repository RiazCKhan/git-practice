# How to GIT quick save

### Notes

HEAD
- indicates the head of the current branch

### Practice

[] Generic code v1.1
- git add

[] Generic code v1.2
--- task: see difference between index file and HEAD
- git status : display paths that have differences between index file and HEAD 
- git diff <path/filename> : view changes relative to index, i.e., staging area 4 next commit

[] Revert
--- task: create GC v1.3 and Revert GC v1.2
- git status : check if file has been added || staged
- git restore --staged <file> : to unstage a file
- git restore <file> : restore file to HEAD, i.e., previous version
 
[] Branching
--- task: create a branch
- git branch : current branch highlighted by green ' * '
- git branch --show-current 
- git checkout -b <branch name> : creates and switches to new branch
- git branch <insert branch> : creates new branch
- git checkout <insert branch name> : switches to new branch

[] Commit Typo
--- task: edit commit message before push
- git log : see log of all commit messages
- git --amend : use vim text edit to change commit message


revert ALL generic code