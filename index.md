# Git & GitHub for Beginners
<p align="justify">This is just an introduction about Git and GitHub for those who might be interested in. 
Whether you are an absolute beginner or experienced, you will be guided through images and clear instructions.</p>

In the words of Mahatma Gandhi:
> _**"Live as if you were to die tomorrow. Learn as if you were to live forever."**_

[**About me**](https://www.linkedin.com/in/ranjana-perera/)

## What is Git?

![Git-image](https://github.com/aardperera/Git-and-GitHub-for-Beginners/blob/gh-pages/images/download.png)

**Git** is an example of a _distributed version Control System_ which is commenly used for open source and commercial software development. 

It is,
- Free
- Open Source
- Super Fast
- Scalable
- Branching/Merging

First let's see what is a **version control system** and why we need it.  <br>
<p align="justify"> 
It just tracks and manages all the changes and modifications to source code over time in a special database called 'Repositary'. It is a software tool that helps to software development teams to work faster and smarter with the confidence that any version can be recoverd at any time. Developers can review project history to find out which changes were made who made the changes, when were the changes made, why were changes needed. Without a version control system, for a single developer, it's already a challenge to keep track of multiple copies of a single project. Now imagine developers collaborate as teams on the same project, each developer has to email it or any other method to pass to others and then manually merge the changes.So the situation becomes worse. Therefore, using a version control system is a best practice for high performing software development teams.</p>

The Version Control System is also categorized into two parts. 
1. Centralized - all team members connect to a central server to get the latest copy of the code and share the changes with others. But the problem is, if the server goes offline, team members cannot collaborate and have to wait until server comes back online. 
2. Distributed - every team member has a copy of the projects on their machine. If the server is offline, they can synchronized their work directly with others.

There are many ways to use Git. We can use git on **the command line** , **code editors & IDEs** , **graphical user interface**

## Install GIT

![Install Git](https://github.com/aardperera/Git-and-GitHub-for-Beginners/blob/gh-pages/images/gitinstall.png)

[Install Git from here!](https://git-scm.com/downloads)


## Git Commands

_The essential Git commands every developer must know._

git init                    

git add file.js
git add *.js
git add .

git status

git commit

git rm --cached file.js

git diff

git log

git checkout master

git branch newBranch

git merge newBranch

git branch --merged

_There are so many Git commands. If you are starting out, Don't worry too much about memorizing these commands instead try to understand how they work._

You can easily follow the below link to get more help on Git 

[Help on Git Commands!](https://git-scm.com/docs/git)