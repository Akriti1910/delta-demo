# delta-demo
This is a demo for Git &amp; GitHub class..
# Teacher
Shradha Khapra

# Student
Akriti Singhal

# To clone a file from the github to local terminal
git clone "copy the HTTPS file link from GitHub"

# To see the status of our file
git status

# To add a new or changed file onto git staging area
git add "file_name" or git add . --> meaning add all the files

# To commit - it is the record of the change
git commit -m "some msg"

# To push - upload local repo content to github also
git push origin main
# origin means kaha ham bhejna chah rhe hai sari files
# main means it is the branch name - will study later

# init command - used to create a new git repo
git init

# When we want our already existing projects to be pushed onto a new repo, copy the link of that repo and type the following command 
git remote add origin "link"

# To check if it is working fine
git remote -v

# To create a new branch
git checkout -b "new branch name"

# To navigte or to change the directory from one branch to another
git checkout "branch name"

# To delete a branch
git branch -d "branch name"

# To join/merge a branch in the main 
git difference "branch name" -- to compare commits, branches, files & more

git merge "branch name" -- to merge 2 branches

# To create a pull request (PR) - it lets u tell others about the changes u have pushed to a branch in a repo on GitHub
git pull origin main -- this lets us bring back the changed file from github to our local system

# Fixing mistakes
# Case 1 - stages changes - meaning we added the file but forgot to commit
git reset "file name"
git reset

# Case 2 - commited changes (for one commit)
git reset HEAD~1

# Case 3 - commited changes (for many commits)
git reset <-commit hash->
git reset--hard <-commit hash->

# I added something to show in my CPS 847 project