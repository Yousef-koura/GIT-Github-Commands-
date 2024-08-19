# Git & Github Commands  
   
How to clone the project repository from github to vs code:
    1- git clone https://github.com/  # is used to Copy a GitHub repository to your local machine.
    2- git status                     # is used to Check the status of your working directory and staging area.
    3- git add (file name)            # is used to Stage specific files to be committed.
    4- git commit -m "Updated"        # is used to Commit your staged changes with a descriptive message.
    5- git push origin main           # is used to Push your committed changes to the main branch on GitHub.

How to upload your project to github:
    1- create a new project in github
    2- cd (folder name)                   # navigate to folder in terminal
    3- git init                           # is used to iInitialize a new Git repository in your project folder.
    4- git add .                          # is used to Stage all files in your project folder for the first commit.
    5- git commit -m "Updated"            # is used to Commit the staged files with a message.
    6- git remote add origin project url  # is used to Link your local repository to the GitHub repository.
    7- git branch                         # is used to Check the current branch (by default, it's often master).
    8- git branch -M main                 # is used to Rename the default branch from master to main.
    9- git push -u origin main            # is used to Push your project to the main branch on GitHub.

How to add branch to github:
    1- git branch                                # is used to List all branches in your repository.
    2- git checkout -b (branch name)             # is used to Create and switch to a new branch.    
    3- git push origin (branch name)             # is used to Push the new branch to GitHub.
    4- git checkout (branch name)                # is used to switch between branches.
    5- git push origin (branch name)             # is used to Push changes to a specific branch.
    6- git add .                                 # is used to Stage all changes in the current branch.
    7- git diff (branch name)                    # is used to cCompare changes between branches.
    8- merge contents:
        --> git merge (branch name)              # is used to Merge the specified branch into your current branch.
        --> git push origin (branch name)        # is used to Push the merged changes to GitHub.
    9- git branch -d (branch name)               # is used to Delete a branch locally.
    
Pull Request: 
