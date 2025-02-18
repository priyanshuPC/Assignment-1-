// these commands are for creating new branches 
git branch feature1 

git branch feature2

// these commands for making some changes in branch 
git checkout feature1 
git add .
git commit -m "changes"
git push origin feature1 

// for merging branch
git checkout main 
git merge feature1 

// pull changes from remote
git pull origin main

// git log and status

git log 
git status

// revert and reset 

git revert 7b9d2f060458d0eab03f0083f936dff9a4b87adb

git reset --hard 7b9d2f060458d0eab03f0083f936dff9a4b87adb
