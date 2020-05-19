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
  - git push
```
