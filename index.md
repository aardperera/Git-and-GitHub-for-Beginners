# Git & GitHub for Beginners

<p align="justify">This is just an introduction about Git and GitHub for those who might be interested in. 
Whether you are an absolute beginner or experienced, you will be guided through images and clear instructions.</p>

## Content
1. What is Git?
2. Install Git
3. Getting Started with Git
4. Git Glossary
5. Git Commands
6. Platforms
7. What is GitHub?
8. Git Vs GitHub

## What is Git?

![Git-image](https://github.com/aardperera/Git-and-GitHub-for-Beginners/blob/gh-pages/images/download.png)

**Git** is an example of a _distributed version Control System_ which is originally created by Linus Torvalds in 2005 and commenly used for open source and commercial software development. 

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

## GET STARTED WITH GIT
Here is a basic overview of how Git works:

1. Create a "repository" with a git hosting tool
2. Copy (or clone) the repository to your local machine
3. Add a file to your local repo and "commit" (save) the changes
4. "Push" your changes to your main branch
5. Make a change to your file with a git hosting tool and commit
6. "Pull" the changes to your local machine
7. Create a "branch" (version), make a change, commit the change
8. Open a "pull request" (propose changes to the main branch)
9. "Merge" your branch to the main branch

## Git Glossary
When we learn how to work using Git, We have met some new terms like 'repo', 'branch', 'clone' and 'master' etc. It's very important to know those terms and what they exactly do. Therefore, follow the below link for more information. 

[Find Git Glossary here!](https://git-scm.com/docs/gitglossary)

## Git Commands

### _The Essential and Basic Git Commands every developer must know._

git init                    

git add file.js<br>
git add *.js<br>
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

You can easily follow the below link to get more help on Git Commands. 

[Help on Git Commands!](https://git-scm.com/docs/git)

## Platforms

_**Places to host git repository**_

- GitHub
- GitLab
- Bitbucket
- SourceForge

## What is GitHub?
![GitHub-image](https://github.com/aardperera/Git-and-GitHub-for-Beginners/blob/gh-pages/images/download%20(1).png)


**GitHub** is a Git repository hosting service that provides a web-based graphical interface. 

<p align="justify"> 
It is the world largest coding community. When you publish a piece of code or a project on GitHub, it gets a lot of attention. Programmers may find source codes in a variety of languages and make and track modifications using Git, a command-line interface. GitHub allows everyone on a team to work on a project from anywhere while facilitating cooperation. You can also look at prior versions that were made at a different time.
GitHub is a platform for project managers and developers to collaborate, track, and update their work in order to keep projects transparent and on track.Packages can be shared privately, within the team, or publicly to the open-source community.
</p>

## GET STARTED WITH GITHUB

For beginners, click on to [GitHub Site](https://github.com/) and create an account.

![GitHub-signup](https://github.com/aardperera/Git-and-GitHub-for-Beginners/blob/gh-pages/images/github%20account.png)

Next, if you intend to use a local computer, then, in your terminal, make yourself known to Git by setting up your user name in each repository. To do that, follow this command:

git config --global user.name "<your_name_here>"

After that, share your email address with Git.

git config --global user.email "<your_email_address>"

You’re now ready to use both Git and GitHub!

## Git Vs GitHub

![Git-vs-GitHub](https://github.com/aardperera/Git-and-GitHub-for-Beginners/blob/gh-pages/images/git_vs_github2.jpg)

Finally, let's see the differences between Git & GitHub!

Git & GitHub are not the same thing.
- Git is a software, that can be installed directly on to the system whereas GitHub is hosted on the cloud.
- Git can be used offline and does not need an internet connection to use unless we need to access the GitHub whereas GitHub cannot be used offline and needs an internet connection.
- Git is something independent and can be used without GitHub whereas GitHub has nothing to do unless we make repositories in Git.
- Git is focused on version control and code sharing while GitHub is focused on centralized source code hosting.
- Git doesn't have a GUI while GitHub provides an easy to use GUI.

**_I hope the above information would be helpful for you to understand and get an idea about Git & GitHub!_**


### Further Refer:
- [Introduction to Git & GitHub](https://drive.google.com/file/d/1jSoPCAY99KJFmnjuZQAIu-wqRn_UCZj-/view)
- [Git & GitHub for Beginners-crash course](https://www.youtube.com/watch?v=RGOj5yH7evk&t=1122s)
- [Git Tutorial](https://www.youtube.com/watch?v=8JJ101D3knE&t=863s)

**Get Started and Learn more!**

**As a next step, start using Git and try to create GitHub projects and start contributing to open source projects!**


> _**"Live as if you were to die tomorrow. Learn as if you were to live forever." - Mahatma Gandhi**_

**If you have any suggesions for improvements,**
[**let me know!**](https://www.linkedin.com/in/ranjana-perera/)