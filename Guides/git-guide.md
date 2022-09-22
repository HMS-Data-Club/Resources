
# Getting Started with Git & Github

## Objective of this document

This document will provide you with resources and tutorials to get you started with Git and GitHub. We will provide details on how to get access to the Data Club’s files and get them on your local computer so you can edit and work with them.

## What is Git / GitHub

Git is a file version control system that helps you keep track of any changes you make to specific documents (e.g., code). This a much more elegant solution than copying a file over and over and changing the name to things like: file_version1, file_version2, file_final, file_finalVersion, file_final_finalVersion …

*Watch [this video](https://www.youtube.com/watch?v=2ReR1YJrNOM) to get a little more of an introduction to Git.*

GitHub is an online service that allows you to share Git repositories with other people. You can either Pull an existing repository to you machine and start working on it yourself, or you can Push any of your repositories (or changes made to someone else’s) to GitHub to share them with others (or even yourself if you have multiple computers).

*Watch [this video](https://www.youtube.com/watch?v=w3jLJU7DT5E) to see how GitHub can help distribute code safely between many people without causing issues.*

For the purpose of our Data Club, we will use GitHub primarily to share code with you (i.e., you pull code from our GitHub to your local machine) and there is no need for now to learn how to push any changes back or merge them with changes from others.

## Install Git and setup your credentials

1. Follow the [instructions here](https://github.com/git-guides/install-git) to install Git or a Git client on your computer. If you are unfamiliar with using the command line, [Github Desktop](https://desktop.github.com/) can be a good place to start. 

2. It is reccomended for you to setup your local username and email address before using Git, and in some cases is required. This does not need to match GitHub (we’ll do that next). You will need to use a terminal window for this (Command Prompt in Windows or Terminal on Mac). You can also use the Terminal window in RStudio if you prefer (different from the Console window)

    `git config --global user.name "First Last"`
    
    `git config --global user.email "me@email.com"`

*Watch detailed instructions in [this video](https://www.youtube.com/watch?v=yDntCIs-IJM) if needed*

## Create a Github Account

If you do not have one already go to [github.com](github.com) and register for a new account. We recommend you use a personal email address to sign up as your GitHub is seen as a personal asset. However, with an academic email you can unlock more features so **once registered you can add your Harvard or other .edu email address to get educational benefits as a [student](https://education.github.com/discount_requests/student_application) or as a [teacher/researcher](https://education.github.com/discount_requests/teacher_application)**.

## Integrate Git /GitHub with RStudio

The nice thing about RStudio is that it has an integrated Git user interface that makes it very easy to use both Git and GitHub.

To get a copy of the first Data Club GitHub repository in RStudio do the following:

1. Click `File` → `New Project`
2. Select `Version Control` → `Git`
3. For the URL choose: <https://github.com/HMS-Data-Club/Fall-2022.git>
4. You can choose the name of the project directory, but we advice something like `DataClub_2022Fall`
5. Choose the folder in which you want to store the R project and Git (depends on how you organize your files)
6. Click `Create Project`
7. Check the `Files` tab to see if you have successfully created the project

*Whenever you are working in an RStudio project that has a dedicated Git repository, you can interact with Git through the Git tab (same pane as Environment tab)*

## Resources:

 - [A good git reference book](https://git-scm.com/book/en/v2)
 - Git desktop environments:  <https://desktop.github.com/> and those from <https://git-scm.com/downloads> 
 - [RStudio and git guide](http://www.r-bloggers.com/rstudio-and-github/) 
 - A great [interactive site](https://learngitbranching.js.org/) for learning Git 
 - A useful git [cheat sheet](http://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf) 
 - [Software Carpentry's git lessons](http://swcarpentry.github.io/git-novice/) 
 - Github's [Git guides](https://github.com/git-guides)

