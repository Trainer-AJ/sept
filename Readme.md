HI This is line 1

want to show it on boards..........


```sh
# start git
 git init --initial-branch=main

# login to Github / Remote Repo
 git config user.email <your-email-of-github>

 git config user.name <your-username>

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



