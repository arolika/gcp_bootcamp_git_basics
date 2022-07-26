# gcp_bootcamp_git_basics
GCP Bootcamp Git Basics

#GIT


##What is version control (VCS)?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. So ideally, we can place any file in the computer on version control.


##Why use it?
A Version Control System (VCS) allows you to revert files back to a previous state, revert the entire project back to a previous state, review changes made over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a VCS also means that if you screw things up or lose files, you can generally recover easily. 

##What is a repository?
A repository a.k.a. repo is nothing but a collection of source code.


If you consider a file in your Working Directory, it can be in three possible states.
1. It can be staged. Which means the files with the updated changes are marked to be committed to the local repository but not yet committed.
2. It can be modified. Which means the files with the updated changes are not yet stored in the local repository.
3. It can be committed. Which means that the changes you made to your file are safely stored in the local repository.


* <b>git add</b> is a command used to add a file that is in the working directory to the staging area.
* <b>git commit</b> is a command used to add all files that are staged to the local repository.
* <b>git push</b> is a command used to add all committed files in the local repository to the remote repository. So in the remote repository, all files and changes will be visible to anyone with access to the remote repository.
* <b>git fetch</b> is a command used to get files from the remote repository to the local repository but not into the working directory.
* <b>git merge</b> is a command used to get the files from the local repository into the working directory.
* <b>git pull</b> is command used to get files from the remote repository directly into the working directory. It is equivalent to a git fetch and a git merge .


![](/Users/A119398573/Downloads/Staging.jpg)

## How to check if Git is installed on my machine
You can run the following command in your terminal:

```$ git --version```

## How to set up my credentials

Every Git commit will use this information to identify you as the author.

```$ git config --global user.name "YOUR_USERNAME"```

```$ git config --global user.email "example@telekom.com"```

To check the info you just provided:

```$ git config --global --list```

## Authentication methods

Follow this [link](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-configure-GitLab-SSH-keys-for-secure-Git-connections)
to learn how to set up SSH keys in GitLab.

## Full tutorial

https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/

