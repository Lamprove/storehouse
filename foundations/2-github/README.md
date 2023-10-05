# Git & Github

One of the essential tools we'll be using is **Git**, a version control system, along with **GitHub**, a web-based platform for Git repositories. In this README, we'll introduce you to the concepts of Git and GitHub, and how to use them effectively for your projects.

Use this page as an introduction to concepts, and refer back to this when needed.

## What is Git?

Git is a distributed version control system designed to help you track and manage changes to your code. It allows you to create snapshots of your code called "commits", which serve as checkpoints in your project's history. This makes it easy to collaborate with others, revert to a previous version of your code, and keep your work organised.

## What is GitHub?

GitHub is a web-based platform that provides hosting for Git repositories, making it easy to share and collaborate on projects. It offers additional features such as issue tracking, pull requests, and project management tools that can help streamline your workflow.

## Basic Git Commands

Here are some essential Git commands that you'll frequently use when working with Git:

*   `git init`: Initialises a new Git repository in the current directory
*   `git clone`: Creates a copy of a remote repository on your local machine
*   `git add`: Adds files to the staging area, in preparation for a commit (to add all files, use `git add *`)
*   `git commit`: Creates a new commit with your changes
*   `git status`: Shows the status of your working directory, including any changes made
*   `git log`: Displays a log of all commits in the repository
*   `git diff`: Shows differences between the working directory and the latest commit
*   `git pull`: Fetches changes from a remote repository and merges them with your local branch
*   `git push`: Pushes your local changes to a remote repository
*   `git branch`: Lists all branches in the repository and shows the current branch
*   `git checkout`: Switches to a different branch or commit
*   `git merge`: Merges changes from one branch into another
 

Your turn to try! Run this command in your terminal:
```
git status
```
You should see something similar to this: 
```
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
```

This means you haven't made any changes to your code on this branch. 

Now, delete this next phrase in the README.md file: (delete me)

Save the file, then run ```git status``` in your terminal again. You should now see something like this: 

```
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
```

This shows that you've modified the README.md file. To 'stage' your changes (get them ready to commit), run:
```
git add README.md
```
If you run ```git status``` again, you will see:
```
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
```
Now you can commit the changes to this file. This means that you are wanting to set these changes to your local copy of the repo (just on your computer/codespace). To commit this file locally:
```
git commit -m 'Changed README.md'
```
The '-m' and subsequent message is necessary to commit your file successfully. By doing this, you are adding a note with the commit, so that others can follow the changes, giving a brief indication of what was changed with the commit. In future commits, you might be changing and committing multiple files, so a short one line summary of these changes is all that is needed here. 

If you want to make these changes live to the cloud version of your repo (in Github itself, so that others can view the changes), you will need to run:
```
git push
```  
Now you can view your changes in the Github version of your repo!

Follow these same steps as you work through this course. Remember to commit often to ensure that 1. Your work is not lost and 2. Changes that relate to each other are tracked regularly.


