## Learning Git/ Github ##
Git is a Distributed Version Control System. Whereas Github hosts GIT Repositories.
### Steps to work on Git ###
**Make the folder a Git Repository**  
Step 1: >> git init (Create a .git folder which identifies that it's a git repository.)  
**Check the Status**  
Step 2: >> git status  
**Add the files to Stagging Area**  
Step 3: >> git add <file_name>/ . (. is for add all the files)  
**which Files are ready to push to github**  
Step 4: >> git commit -m "message"  
**Push the files to github**  
Step 5: >> git push origin <branch_name>  
  
### Additional Steps ###
Before Push to github we need to set the branch and destination(remote repo).  
#### Branching ####
**Check Branch**  
>git branch  
**Set Branch**  
>git branch -M main (-M means Rename. Only needed for first time.)  
**Create a new Branch**  
>git branch <branch_name>  
**Merge the Branch**  
Want to merge a sub_branch to main branch.  
We should present in the main branch then following  
>> git merge <branch_name>  
**Delete Branch**  
>> git branch -d <branch_name>  
#### Set Remote Repo ####
>> git remote add origin <url>  