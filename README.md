# DemoRepo
Git n github tutorial
<br>
Author - Anushka Murade

# GIT AND GITHUB

# Four cases after making clone -
Untracked : new files that git doesn’t yet track<br>
Modified : changed<br>
Unmodified : unchanged<br>
Staged : file is ready to be committed<br>

# 1.) Create a repo on github

# 2.) Commands to run in terminal and check 
git –version <br>
git config --global user.name “[firstname lastname]”<br>
git config --global user.email “[valid-email]”<br>

# 3.) Create a new folder in ur computer and then clone the repo in that folder
Clone : git clone [url of repo]<br>
To check the status of the repo : git status<br>
 
# 4.) Modifying file in your computer
After modification :<br>
Add : git add [filename]  (->adds file to staging area)<br>
Alternative to add all the changes to the staging area together : git add .<br>
Commit : git commit -m “Some message”<br>
Upload the changes of local repo(computer) to remote repo(github) : git push origin main or git push origin [branchname]<br>

# 5.) To create a new git repo after creating folder locally : init commands
adds .git file : git init <br>
Create a repo<br>
git remote add origin [link]<br>
To verify remote : git remote -v<br>
Push : git push origin [branchname]<br>

# 6.) Branches
To verify branch : git branch<br>
To rename branch : git branch -M [newname/main]<br>
To navigate : git checkout [branchname]<br>
To create new branch : git checkout -b [newbranchname]<br>
To delete branch : git branch -d [branchname]<br>
 
# 7.) Merging branches or Direct Pull requests on github
To compare commits,branches,files,more : git diff [branchname]<br>
To merge 2 branches : git merge [branchname]<br>

# 8.) Pull request (used to fetch and download content from remote repo and immediately update the local repo) : git pull origin main

# 9.) Undoing changes :
Case 1 : staged changes<br>
git reset [filename]<br>
git reset<br>
Case 2 : committed changes (for one commit)<br>
git reset HEAD~1<br>
Case 3 : Committed changes (for many commits)<br>
git reset [commithash]<br>
git reset –hard [commithash]<br>


git log gives details and it has hash code of each commit<br>


# WORK FLOW : Create Github Repo -> clone -> changes -> add -> commit -> push
