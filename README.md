# Learning Git/ Github #
Git is a Distributed Version Control System. Whereas Github hosts GIT Repositories.
## Steps to work on Git ##
**Step 1: Make the folder a Git Repository**  
`git init` (Create a .git folder which identifies that it's a git repository.)  
**Step 2: Check the Status**  
`git status`  
**Step 3: Add the files to Stagging Area**  
`git add <file_name>/ .` (. is for add all the files)  
**Step 4: which Files are ready to push to github**  
`git commit -m "message"`  
**Step 5: Push the files to github**  
`git push origin <branch_name>`  
  
## Additional Steps ##
Before Push to github we need to set the branch and destination(remote repo).  
### Branching ###
**1. Check Branch**  
`git branch`  
**2. Set Branch**  
`git branch -M main` (-M means Rename. Only needed for first time.)  
**3. Create a new Branch**  
`git branch <branch_name>`  
**4. Merge the Branch**  
Want to merge a sub_branch to main branch.  
We should present in the main branch then following  
`git merge <branch_name>`  
**5. Delete Branch**  
`git branch -d <branch_name>`  
### Set Remote Repo ###
Create a repo in github account. Copy the url and apply it in following code   
`git remote add origin <url>`  