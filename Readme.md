HI This is line 1


```sh
# start git -- in the local
 git init --initial-branch=main

# login to Github / Remote Repo
 git config user.email <your-email-of-github>

 git config user.name <your-username>

## Online Repo aka remote 
>> git remote add origin https://github.com/Trainer-AJ/sept.git
>> AWS DevOps  git remote -v
origin  https://github.com/Trainer-AJ/sept.git (fetch)
origin  https://github.com/Trainer-AJ/sept.git (push)

# The Git add command adds a change in the working directory to the staging area. 
 git add foldername filename

# Run  git status to check 

### NOTE: FOR EVERY CHANGE THAT YOU NEED TO STORE.... RUN GIT ADD AGAIN !!!
>> git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Readme.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Readme.md

# git commit: The git commit command captures a snapshot of the project's currently staged changes. Committed snapshots can be thought of as “safe” versions of a project—Git will never change them unless you explicitly ask it to.
git commit -m "Meessage here"

# PUBLISH CHANGES
# GIT PUSH REMOTE-NICKNAME BRANCH-NAME
>> git push origin main  
```

## git branch
> Git branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your change
**chnages stays on selected branch**
- Chnages Made in branch-1 doesn't show under Main branch
- Real World : Main / Master holds Prod Code
- branching startegy



