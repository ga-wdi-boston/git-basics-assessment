![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Write your answers inside this file, where it's indicated by the comments.

1. We just forked a repo on GitHub.com and want to start working on it locally. What command do we use to do that?
git clone with the SSH URL

2. OK, we just wrote some code. What command could we use to see a list of all the changes that have been made since the last commit?
git diff

3. We want to see more info about a specific commit, specifically who created the commit and when it was done. What command would one use?
git log

4. We are tasked with working on a new feature. And want to seperate our work from others in the project. What you we do? What git command would one use?
create a new branch with the command
git checkout -b sandbox-name


5. I want to add a file to the staging area. What git commit would I use?
use the git add command


6. I've been working on a branch, add-directories, to implement a feature. The feature is done and you need to add your changes into the master branch. What git command should I use?
change to the master branch using:  git checkout master
and then run a merge command:  git merge sandbox-name

<hr>

You're done! Refer back to README.md.
