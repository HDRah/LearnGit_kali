# Useful notes in git

## Basic command
1. git add
2. git add *
3. git commit -m "comments"
4. git diff # this is used to observe the difference
5. git status
6. git reset HEAD filename  
 # this is to undo the mistakenly added files, while the modification will still exist, it just becomes not added
7. git checkout -- filename  
 # this can undo the modification to the most recent commit/add (such undo includes deletion)
8. git log # this is to see the modification history
9. git rm filename  
 # this can delete file, followed by git commit -m ''

## Version control

1. git reset --hard + the version you want to go  
 # one can use HEAD^ to go to the previous version quickly. also can be HEAD^^, ..., HEAD~100
2. git log can see the current and previous version id 
3. git ref lof can see all modification
