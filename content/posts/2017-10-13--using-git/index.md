---
title: Using Git 
cover: photo-1451324119451-db0ac857463c.jpg
category: "hacktoberfest"
author: wwcodepdx
---

## Git
Git is one of the best version controlling system in this world. It helps us to track and maintain anything you want based on versions . Mostly it is used by the code developers to maintain different versions of their work. It tracks all your work based on something called **commit-id** which is nothing but a randomly generated hash value.

With Git you can create a repository(repository is something where we store our code and git helps us to maintain all the history with a possibility to change our code easily) anywhere and just install git and start using it for easy versioning of your code.

Lets start with some basic commands.

Step 1: Install git in your workstation

Step 2: Create a directory and go inside the directory 

  type command **git init** 
  
  it will create a new git repository

Step 3: Now if you want to add a file to your repo just create a file inside the same directory, add some text and save it
 
  type command **git add file-name** 
  
  it will add your file to something called staging and not yet committed to your repo
  
Step 4: Once you have added the file now you have to commit your file to your repo 

  type command **git commit -m "your message"** 
  
  this will commit your changes to your local repo
  
Step 5: Now if you want to see your commit 

  type the command **git log **
   
  this will show your commit history with the commit id assigned to that commit

Step 6: Now if you want to push the code to any remote repository you can do that by setting the remote and pushing the code           to that repo.

  type the command **git remote add origin repo-url**
  
  this will set the remote repo for your code.
  
  type the command **git push origin master** 
  
  this will push your changes to the remote repo 
  
