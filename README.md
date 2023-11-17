# DemoRepo
Git n github tutorial
<br>
Author - Anushka Murade

# GIT AND GITHUB

# Four cases after making clone -
Untracked : new files that git doesn’t yet track
Modified : changed
Unmodified : unchanged
Staged : file is ready to be committed

# 1.) Create a repo on github

# 2.) Commands to run in terminal and check 
git –version 
git config --global user.name “[firstname lastname]”
git config --global user.email “[valid-email]” 

# 3.) Create a new folder in ur computer and then clone the repo in that folder
Clone : git clone [url of repo]
To check the status of the repo : git status
 
# 4.) Modifying file in your computer
After modification :
Add : git add [filename]  (->adds file to staging area)
Alternative to add all the changes to the staging area together : git add .
Commit : git commit -m “Some message”
Upload the changes of local repo(computer) to remote repo(github) : git push origin main or git push origin [branchname]

# 5.) To create a new git repo after creating folder locally : init commands
adds .git file : git init 
Create a repo
git remote add origin [link]
To verify remote : git remote -v
Push : git push origin [branchname]

# 6.) Branches
To verify branch : git branch
To rename branch : git branch -M [newname/main]
To navigate : git checkout [branchname]
To create new branch : git checkout -b [newbranchname]
To delete branch : git branch -d [branchname] 
 
# 7.) Merging branches or Direct Pull requests on github 
To compare commits,branches,files,more : git diff [branchname]
To merge 2 branches : git merge [branchname]

# 8.) Pull request (used to fetch and download content from remote repo and immediately update the local repo) : git pull origin main

# 9.) Undoing changes :
Case 1 : staged changes
git reset [filename]
git reset
Case 2 : committed changes (for one commit)
git reset HEAD~1
Case 3 : Committed changes (for many commits)
git reset [commithash]
git reset –hard [commithash]


git log gives details and it has hash code of each commit


# WORK FLOW : Create Github Repo -> clone -> changes -> add -> commit -> push
