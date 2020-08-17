1:Adding files of certain type:
git add *.extension   

2:Adding all files including hidden files:
git add -A

3:Removing files from stagging area:
git reset HEAD <file>

4:Ignore the files:
First create .gitignore file.
Then add the file you want to remove to that file.
Then add and commit .gitignore
And you are good to go...
========================

----> Branches ---->
1:Listing all branches
git branch

2:Adding a branch
git checkout -b <branch_name>

3:Changing branches
git checkout <branch_name>

4:Merge a branch
git merge <branch_name>

5:Remove a branch
git branch -d <branch_name>
=========================

