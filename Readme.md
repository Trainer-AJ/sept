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

-------------------------------

  Id     Duration CommandLine
  --     -------- -----------
   1        0.067 git --version
   2        0.024 cd .\Downloads\
   3        2.693 git clone https://github.com/Trainer-AJ/az-400-codes.git
   4        0.014 cd .\az-400-codes\
   5        0.097 git init --initial-branch=main
   6        0.059 git config user.name dubai
   7        0.065 git config user.email
   8        0.066 git config user.email dubai@ajsepthotmail.onmicrosoft.com
   9        0.066 git add .\Readme.md
  10        0.065 git status
  11        0.071 git add .\README.md
  12        0.043 git status
  13        0.122 git commit -m "v1 : read only copy of my code which is stored locally"
  14        0.164 git log
  15        0.050 git remote -v
  16        0.064 git remote add origin https://dubai-nov24@dev.azure.com/dubai-nov24/Project-1/_git/P…
  17        0.038 git remote -v
  18     1:22.150 git push origin main



