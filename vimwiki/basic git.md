# Staging git environment 
1. git init = initalize git
2. git remote add origin http...
3. git add . or git add file.txt = stage your file
4. git commit -m "message here" = snapshots the staged files into the repo history, with a message.
5. git push origin main --force
6. git pull origin main --allow-unrelated-histories
7. git push origin main.



git branch -> name of the branch main or master

git branch -m main master (or) git branch -m master main -> to alternate between two branches or create.

git branch -d main/master, to delete one branch


A branch points to the latest commit in its history.
branch name -> main or master


# Changing git repo name
After changing name in github setting do,

git remote set-url origin NEW_URL

git push origin main

# Git pull
Fetches and downloads content from a remote repository.

# Git log
Exiting git log - q
Git log gets the history of commits in a repository.
