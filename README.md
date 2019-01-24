## Add sth.....
# Basic
- git add [filename]
- git commit -m '[your commit message]'
	- [commit message template](https://gist.github.com/adeekshith/cd4c95a064977cdc6c50) 
- git push
- git pull

# Merge
- Auto merge 
	- use 'git pull' to auto merge (But usually failed)
- Merge manually
	```
	<your code>
	<<<<<<<<<<< HEAD
	================
	<pull from git>
	>>>>>>>>>>> [commit number]
	</code>
	```
# Branch
- Creat new branch: git branch [branchname]
- Show all branch: git branch
- Switch branch: git checkout [branchname]
- Delete branch: git branch -d [branchname]
- Merge two branch: git merge [branchname]
- Cancel merge two branch: git reset --hard HEAD~
- Rebase two branch: git rebase --continue
- Cancel rebase two branch: git rebase --abort

# Another topic
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
	
	
