# yolov4-deepsort
### Submodule for covid-people-graph project

First initialize submodule.

1. `git submodule add https://github.com/pdncovid/yolov4-deepsort submodules/yolov4-deepsort`
						OR
`git submodule update --init`
	
2. check ```git remote -v``` and if different, change using: ```git remote set-url origin <url>```
3. ```git checkout covid-people-graph```
4. MAKE CHANGES
5. ```git add```
6. ```git commit```


#### REMOVE

1. `git submodule deinit -f submodules/yolov4-deepsort/`    # removes the dir
2. `rm -rf .git/modules/submodules/yolov4-deepsort`
3. `git rm -f submodules/yolov4-deepsort/`
