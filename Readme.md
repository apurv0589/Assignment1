# Assignment-1 
## Task1 - 15 Git command
### 1. Git Config
#### For Commiting in Git first you have to configure it for user name and user email address with respect to your git account
To configure user and Email Address you can use   
    git config –-global user.name 'name' for user name
    git config –-global user.email'email address' for Email address

#### To check configured user and Email Address you can use    
    git config –-global user.name for user name    
    git config –-global user.email address' for Email address

### 2. Git remote add origin
#### This command is use to connect with the specific repository in which you want to make commit.
for this you have use    
    git remote add origin https://github.com/username/repositoryname.git

### 3. Git Status
#### This command is use to check the status of the files in working directory.         
The status of the file can be     
    Changes not staged for commit:      
    Changes to be committed:   
Changes not staged for commit means you need to add that file in staging area with git add 'file name' command.      
Changes to be committed means the file is in staging area and changes need to cimmit by using git commit -m'message'.    

### 3. Git add    
#### This command is use to add the file in staging area. This is the first step heeds to be done if any changes made in the file/files.   
The command is     
        git add 'file name' to add specific file in staging    
        git add . to add all the files of current working directory in stagging    

### 3. Git commit
#### This command is use for commiting the changes and making file ready to push to repository from staging.    
The command is    
        git commit -m 'message for commit'     

