# Assignment-1 
## Task1 - 15 Git command
### 1. Git Config
#### For Commiting in Git first you have to configure it for user name and user email address with respect to your git account
#### To configure user and Email Address you can use   
    git config –-global user.name 'name' for user name
    git config –-global user.email'email address' for Email address
    
![image](https://user-images.githubusercontent.com/52498255/194310817-259af903-ac8e-4600-876f-cafd1049c62c.JPG)
#### To check configured user and Email Address you can use    
    git config –-global user.name for user name    
    git config –-global user.email address' for Email address   
![image](https://user-images.githubusercontent.com/52498255/194311560-84ac80ef-ee23-4f2c-a3cf-f7c8f8364767.JPG)

### 2. Git remote add origin
#### This command is use to connect with the specific repository in which you want to make commit.
#### for this you have use   
    git remote add origin https://github.com/username/repositoryname.git
![image](https://user-images.githubusercontent.com/52498255/194311976-3d9eea74-ebf5-4283-b4c4-58cc6d3ddc69.JPG)

### 3. Git Status
#### This command is use to check the status of the files in working directory.         
#### The status of the file can be   
    Changes not staged for commit:
    Changes to be committed:   
Changes not staged for commit means you need to add that file in staging area with git add 'file name' command.
![image](https://user-images.githubusercontent.com/52498255/194312280-8cb3b900-cb72-42e2-abe0-33c2e5c5cfdc.JPG)
Changes to be committed means the file is in staging area and changes need to cimmit by using git commit -m'message'.   
![image](https://user-images.githubusercontent.com/52498255/194312493-4ad6b62a-0c19-4b10-b3d4-08a044aa2af5.JPG)

### 4. Git add    
#### This command is use to add the file in staging area. This is the first step heeds to be done if any changes made in the file/files.   
#### The command is    
    git add 'file name' to add specific file in staging    
    git add . to add all the files of current working directory in stagging    
![image](https://user-images.githubusercontent.com/52498255/194312710-892533d6-d326-401d-94f6-6a1a8c268fd5.JPG)

### 5. Git commit
#### This command is use for commiting the changes and making file ready to push to repository from staging.    
#### The command is    
    git commit -m 'message for commit'  
![image](https://user-images.githubusercontent.com/52498255/194313366-3291efb2-1d0d-4a4f-9e18-7b885912f401.JPG)

### 6. Git push origin main   
#### This command is use push the file in the repository.
#### The command is    
    git push origin main   
![image](https://user-images.githubusercontent.com/52498255/194313603-f3b4ba68-4d79-4aa7-81dc-b02225165575.JPG)


### 7. Git branch   
#### This command is use check all available branches in repository.
#### The command is    
    git branch   
![image](https://user-images.githubusercontent.com/52498255/194313891-88123ff6-1f1f-4ced-85a8-d4e5181316eb.JPG)


### 8. Git branch 'branch name'   
#### This command is use to create new branch. New branch automatically copy all the containt of main branch.    
#### The command is    
    git branch 'branch_name'   
![image](https://user-images.githubusercontent.com/52498255/194314036-89d183b8-328f-47e8-91f9-3f9a721f33db.JPG)


### 9. Git branch -d 'branch name'   
#### This command is use delete the branch.
#### The command is    
    git branch -d 'branch_name'   
![image](https://user-images.githubusercontent.com/52498255/194314226-c1ce8028-fc8a-454e-9a75-70413b1449ca.JPG)

### 9. Git checkout 'branch name'   
#### This command is use to change from the current working branch to other branch. 
#### The command is    
    git checkout 'branch_name'    
![image](https://user-images.githubusercontent.com/52498255/194314458-ea573093-77b9-4da2-a268-480142a63ac0.JPG)

### 9. Git merge 'branch name'   
#### This command is use to copy the commits from other branch to current working branch .
#### The command is    
    git merge 'branch_name'   
![image](https://user-images.githubusercontent.com/52498255/194314699-8e5c5c45-b024-461e-9d3f-31ae128a2eaf.JPG)

### 10. Git log   
#### This command is used when we want to check the log for every commit in detail in our repository.
#### The command is   
    git log   
![image](https://user-images.githubusercontent.com/52498255/194314843-b2277f02-37c8-49d4-8174-c412b76b2c1b.JPG)   
    

### 11. Git clone   
#### This command is use to import the files of a project from the remote repository of some other developer to our local system.    
#### The command is    
    git clone 'repository url'
![image](https://user-images.githubusercontent.com/52498255/194315029-5407dceb-0abe-4416-a483-f215f92463e6.JPG)

    

### 12. Git init  
#### This command is use to initialise the git repository.
#### The command is    
    git init 'repository name'   
![image](https://user-images.githubusercontent.com/52498255/194315229-342b407f-6fb5-4dc2-8aa0-c6be4f94974f.JPG)

### 13. Git diff  
#### we can find the differance between two branches by using this comman.
#### The command is    
    git diff 'branch 1' 'branch 2'   
![image](https://user-images.githubusercontent.com/52498255/194315514-57fc5355-5cf0-429d-9d02-22fdab058c9f.JPG)
    

### 14. Git reset  
#### This command unstages the file, but it preserves the file contents.    
#### The command is    
    git reset 'file name'   
![image](https://user-images.githubusercontent.com/52498255/194315734-98d1a0e3-f168-4e67-83ef-98fdcfe3172a.JPG)
    

### 15. Git pull  
#### The git pull command first runs ‘git fetch’ which downloads the content from the specified remote repository and then immediately updates the local repo to match the content.    
 #### The command is    
    git pull origin main 
![image](https://user-images.githubusercontent.com/52498255/194315895-eedfbd81-e9b4-4da5-a0c5-092db1ef90ef.JPG)
    
