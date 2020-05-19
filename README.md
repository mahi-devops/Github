# To configure your name and email address on Gitbash
```
git config --global user.name "Reddy Maheswar"
git config --global user.email "9618714521m@gmail.com"
```
# Note
```
1. Add our repository (Central repository) to our local machine using the below command.
  - git clone URL OF THE REPOSITORY
2. Our Local Machine consists of 3 Areas.
    i.    Working area
    ii.   Staging/Index area
    iii.  Local Repository
3. what ever we add, remove and update a file locally, Git keeps that in working area.
4. The files that we want to commit must be staged using the below command.
  - git add GitLearning.txt (git add will move the files from working area to staging area)
5. The commit command commit the files from staging area to Local repository.
  - git commit -m "some useful message"
6. Now push the files commited to central repository using below command. 
The best practice before pushing the files to central repository is do git pull and then push.
  - git push
  
  
```
# git add
```
1. To stage the files from working area to staging area.
2. We might modify 10 files but we want to update only 5 files, so we will stage only that files and do commit.
3. Instead regular filename we can use regular expressions
    - *.txt, *.java
```
# git commit
```
It picks all files from staging and commits to local repositroy.
```
# origin
```
Origin is the logical name mapped to remote remote repository URL.
git push origin master - it pushes the files to remote repository.
master is nothing but branch.
```
# pulling changes from remote
```
To deal with less conflicts, always we have to work on latest copy.
```
# ** Difference between git pull and git push
```
git pull does fetch and merge, means it merges to local repository.
git fetch only fetched and it won't merge. To merge it first do git fetch and then git merge
```
# To check the commit history
```
git log
```
# To check what changes we were added in a commit
```
git show COMMITID
```
