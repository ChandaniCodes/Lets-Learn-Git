# Lets-Learn-Git
Learning Git


Git Command which I used

To check git version
* git --version 

**Set your username**
* git config --global user.name "username"

**Set your email address**
* git config --global user.email "useremail"
**
To change your text file**
* git config --global --edit

**To make directory**
* mkdir directoryName

**To change directory**
* cd directoryName

** To initialize a new, empty repository**
* git init

**To show the files** 
* ls
* ls -a

**To check the status of ur repo**
* git status

**To move it to the staging area**
* git add filename
      or
* git add .

**what change you made to your project**
* git commit -m "message"

**For displaying the history of a repository**
* git log

**To remove a file or group of files from a Git repository**
* git rm --cached filename 
  ex- git rm --cached hello.cpp 


* git checkout hashkey
   ex-  git checkout 40862deda781a8a4386fa4c4cba

**To make branch**
* git branch branchname
  -> git branch dev

**To move into another branch**
* git checkout branchname
  -> git checkout dev
      or
 * git checkout -b branchname

**To merge the branch**
 * git merge branchname

**To make gitignore file**
 * touch .gitignore

**To connect your local repository to the remote server**
 * git remote -v

For creating a local copy of a central repository
 * git remote add origin https://github.com/ChandaniCodes/Lets-Learn-Git.git
 * git remote -v
  -> origin  https://github.com/ChandaniCodes/Lets-Learn-Git.git (fetch)
  -> origin  https://github.com/ChandaniCodes/Lets-Learn-Git.git (push)
  
 *  git branch -M main
 *  git push -u origin main

**To push the code **
 *  git pull
 *  git push -u origin dev
    
