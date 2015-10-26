#<span style="color:steelblue"> GitHub Tutorial </span>
**Github is like a storage container, which saves your code & projects on the cloud(internet)**  

* Github visiually keeps track of code 
* Requires git
* Easy to work with a team or partner 
*  **_Super easy to share files with others_** 

_by Christian Fernandez_

---
# Git vs. GitHub
1. **Git is a version control, which means it manages multiple tasks and files.**  
  * Git does not require Github to work
  * has a "snap shot method" - takes pictures of code
  * runs in the terminal
  * **<span style="color:red">_has its own commands_ </span>**
  * **<span style="color:red"> _every command starts with git, when you initiate git in the terminal_ </span>**
  * Link git to github using the command <span style="color:red">(git colne (ssh key to your repository))</span>
  * you can use git in this terminal at this website after singing up with <span style="color:red">GITHUB</span>opening your IDE(INTERGRATED DEVELOPMENT ENVIORNMENT) https://c9.io
  * **<span style="color:red">NOTE: TO SIGN UP WITH GITHUB; 1ST) MAKE A GITHUB ACCOUNT | 2ND) GO TO c9.io AND AT THE TOP RIGHT WILL BE A CAT SYMBOL. CLICK IT!!!   | 3D) TYPE IN YOUR GITHUB ACCOUNT INFO</span>**
  
 
2. **Github works with git to share files, projects, repositories and directories**  
  * Github only saves the code that is **<span style="color:red">PUSHED</span>** from git
  * Must have an account at https://github.com/ in order to use github 
  * On the github website you make your respository to hold and save all code 
  * You can make new repositories in github for different projects and to keep projects organized
  * can link to git by copying and pasting your ssh key to git with git clone 
  

---
# Initial Setup
##To begin using GitHub you must 1st make an account at https://github.com/**  
## This section will teach you how to setup your new repo
1) You should see **(<span style = "color:green">+New repository</span>)** on the right side of the page after signing in  
2) To make a new repository(repo) to save and share projects, codes, files, etc: You have to first make a directory(folder) on the c9 terminal  
3)After making the directory on the c9 terminal _(mkdir folder name)_  go to github.com and sign in  
4) When you are signed in you should see the **(<span style = "color:green">+New repository</span>)** button. Click it then name it the exact same name as your directory from **git**  
5) After naming your <span style ="color:green">repo</span> You will see a few options appear. In the <span style="color:blue"> Quick setup</span> section you will see HTTPS & SSH  
6) You can select HTTPS or SSH.  However I recommened SSH because it's more secure, better protected, and impossible to hack without the key code  
7)If you selected HTTPS you will have to type in your e-mail and password everytime you want to make changes to your file or code, and it is easy to hack because all a person would need is your e-mail and password!!  
8)  To make an e-mail and password type the command ( **git config** ). Then type (**user.e-mail**) then (**user.password**)  
9) After selecting SSH. <span style="color:red">**Copy & Paste** these 2 lines from the section that says **(…or push an existing repository from the command line)**, one line at a time into git in this order:</span> <span style="color:teal">** git remote add origin git@github.com:(your account)/GitHubTest.git</span> then <span style="color:teal">git push -u origin master</span>**  
10) Everything should be set up now so go back to git in the c9.io terminal






---
# Repository Setup

1) After making your repo with **SSH**, you can now make as much repos as you like  
2) To use git in the c9 terminal you have to type this command in once you are in the correct directory: <span style="color:red"> **git init**</span>
3) Git Init tells the terminal that you want to use git so from now on, all commands will have to use git  
3) To save your code onto github.com: you have to type in these 3 commands: <span style="color:red"> **git add(file name) git commit -m "2 words explaining what you did" git push**</span>  
4) <span style="color:red">**git add**</span> - creates a stage around the file so that git can see it  
5) <span style="color:red">**git commit -m "msg goes here"**</span> - allows you to **_quickly_** explain what you have done in your code or what a piece of code does  
6)<span style="color:red">**git push**</span> - pushes all of your saves and commits onto your repo in GitHub  
7) The repo in your GitHub is your **Local Repo**. This means that it is only on your machine and only you have access to it  
8) A **Remote Repo** is an online repo in which other people can view your repo and suggest changes to your ocde to make it better  
9) To use this remote repo you have to fork another person's repo then copy their SSH key with git clone  
10) Only if you want to see other peoples' projects and make suggestions to improve one's code






---
# Workflow & Commands
## All commands in git must start with _git_  
**The git work flow is like:**  
1) In your terminal you go to the directory that has git initiated  
2) The repo allows you to edit files in git  
3) Then you save your work (git add)  
4) Then add a short msg about what you did (git commit -m)  
5) Send your changed and saved work to your repo on github ( git push)  
##Here are a few commands that will make navigating git a lot easier  
* <span style = "color:red">**git init**</span> - brings you into git  
* <span style = "color:red">**git status**</span> - will show you all the files that have been changed and if the file is **red** then it as not been added
* <span style="color:blue">**TIP** : when done typing in code. Type in git status in the command line and your file should appear **RED**, this means you have not put a stage on your file (git add). After doing git add, type in git status again and the file should be green this time. This means it is ready to be committed and pushed  </span>
* <span style = "color:red">**git add**</span> - creates a stage for written code or project, so that it can be tracked(the file name should be green after you git add)  
* <span style = "color:red">**git commit -m "msg"**</span> - lets you write a short msg that summerizes the thing you did or changes you have made  
* <span style = "color:red">**git config**</span> - allows you to set up your email (user.email) and password (user.password)  
* <span style = "color:red">**git push**</span> - pushes all save files and commits onto github  
* <span style = "color:red">**git pull**</span> - allows you to save changes from another repo  
* <span style = "color:red">**git help**</span> - for more clarification on a certian command


