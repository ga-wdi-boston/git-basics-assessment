![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Write your answers inside this file, where it's indicated by the comments.

1. We just forked a repo on GitHub.com and want to start working on it locally. What command do we use to do that?
After forking the repo into our own account, we must copy the SSH link from our forked copy and use the command "git clone <url>" in the directory that we wish to add the repo to.

2. OK, we just wrote some code. What command could we use to see a list of all the changes that have been made since the last commit?
We would use the git status command to check any changes made, which will show changes that need to be added and/or committed.

3. We want to see more info about a specific commit, specifically who created the commit and when it was done. What command would one use?
Git log is used which will show all the commits made, by who, and the comment that was added along with the commit.

4. We are tasked with working on a new feature. And want to seperate our work from others in the project. What you we do? What git command would one use?
We would create a separate branch using the git branch -b <branch name>.

5. I want to add a file to the staging area. What git commit would I use?
To add a file, git add <file name> is used.

6. I've been working on a branch, add-directories, to implement a feature. The feature is done and you need to add your changes into the master branch. What git command should I use?
To add changes from one branch into another branch (master), you must be in the master branch and then use git merge <branchname> (in this case git merge add-directories) that will then add the changes made in add-directories into the master branch.

<hr>

You're done! Refer back to README.md.
