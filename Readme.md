# Assignment-1 
## Task1 - 15 Git command
### 1. Git Config
#### For Commiting in Git first you have to configure it for user name and user email address with respect to your git account
#### To configure user and Email Address you can use   
    git config –-global user.name 'name' for user name
    git config –-global user.email'email address' for Email address
#### To check configured user and Email Address you can use    
    git config –-global user.name for user name    
    git config –-global user.email address' for Email address

### 2. Git remote add origin
#### This command is use to connect with the specific repository in which you want to make commit.
#### for this you have use   
    git remote add origin https://github.com/username/repositoryname.git

### 3. Git Status
#### This command is use to check the status of the files in working directory.         
#### The status of the file can be   
    Changes not staged for commit:
    Changes to be committed:   
Changes not staged for commit means you need to add that file in staging area with git add 'file name' command.      
Changes to be committed means the file is in staging area and changes need to cimmit by using git commit -m'message'.    

### 4. Git add    
#### This command is use to add the file in staging area. This is the first step heeds to be done if any changes made in the file/files.   
#### The command is    
    git add 'file name' to add specific file in staging    
    git add . to add all the files of current working directory in stagging    

### 5. Git commit
#### This command is use for commiting the changes and making file ready to push to repository from staging.    
#### The command is    
    git commit -m 'message for commit'   

### 6. Git push origin main   
#### This command is use push the file in the repository.
#### The command is    
    git push origin main    


### 7. Git branch   
#### This command is use check all available branches in repository.
#### The command is    
    git branch    


### 8. Git branch 'branch name'   
#### This command is use to create new branch. New branch automatically copy all the containt of main branch.    
#### The command is    
    git branch 'branch_name'    


### 9. Git branch -d 'branch name'   
#### This command is use delete the branch.
#### The command is    
    git branch -d 'branch_name'    

### 9. Git checkout 'branch name'   
#### This command is use to change from the current working branch to other branch. 
#### The command is    
    git checkout 'branch_name'        

### 9. Git merge 'branch name'   
#### This command is use to copy the commits from other branch to current working branch .
#### The command is    
    git merge 'branch_name'     

### 10. Git log   
#### This command is use push the file in the repository.
#### The command is    
    git push origin main

### 11. Git clone   
#### This command is use push the file in the repository.
#### The command is    
    git push origin main

### 12. Git init  
#### This command is use to initialise the git repository.
#### The command is    
    git init 'repository name'      

### 13. Git diff  
#### This command is use push the file in the repository.
#### The command is    
    git push origin main   

### 14. Git reset  
#### This command is use push the file in the repository.
#### The command is    
    git push origin main   

### 15. Git pull  
#### This command is use push the file in the repository.
#### The command is    
    git push origin main 
