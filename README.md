# yolov4-deepsort
### HEEEEELP : 

1.
	```git submodule add <repo> <dir>```
						OR
	```git submodule update --init```

3. check ```git remote -v``` and if different, change using: ```git remote set-url origin <url>```
5. ```git checkout <branch>```
6. MAKE CHANGES
7. ```git add```
8. ```git commit```


#### REMOVE
1.`git submodule deinit -f -- a/submodule`    # removes the dir
2. `rm -rf .git/modules/a/submodule`
3. `git rm -f a/submodule`