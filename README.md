# git-cheat-sheets



GIT CONFIG

Edit git config file to change [core] or [remote "origin"]
 ```javascript
#subl .git/config
 ```

—————————————————————————

git stash

 ```javascript
#git stash apply
 ```

—————————————————————————

roll back one commit

 ```javascript
#git reset --hard commit-hash
 ```

—————————————————————————

see only the last commit made

 ```javascript
#git log -1
 ```

—————————————————————————

#different uses to revert changes to files


##checkout
use git checkout when you have not added files.

##revert
use git revert when a files have been committed
```javascript
#git revert commit-hash
```
note: use the commit-hash you wast to revert

##reset
removes all the changes made from files and logs

```javascript
git reset —hard commit-hash
```
note: cannot revert this



—————————————————————————
to look into a history of a file
 ```javascript
gitk “directory/filename.ext"
```


