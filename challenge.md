![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Write your answers inside this file, where it's indicated by the comments.

1. We just forked a repo on GitHub.com and want to start working on it locally. What command do we use to do that?

We enter clone followed by the SSH link provided on our forked repository.

2. OK, we just wrote some code. What command could we use to see a list of all the changes that have been made since the last commit?

We can enter git status in the command line to see all of the changes.

3. We want to see more info about a specific commit, specifically who created the commit and when it was done. What command would one use?

We would use the command: git log for a full history on different commits including the time, person who committed and comments made with the commit.

4. We are tasked with working on a new feature. And want to seperate our work from others in the project. What you we do? What git command would one use?

We would create a new branch. You can create and switch to that new branch by entering git checkout -b followed by the name of the new branch. It would look like: git checkout -b <name_of_new_branch>. This way our changes would be seperated from the work of others.


5. I want to add a file to the staging area. What git commit would I use?

You would use git add followed by the name of the file. So use: git add <name_of_file>


6. I've been working on a branch, add-directories, to implement a feature. The feature is done and you need to add your changes into the master branch. What git command should I use?

You can switch back to the master branch by entering checkout master. Then you would enter the command: git merge add-directories. This would merge all of the changes committed in the add-directories branch into the master branch.

<hr>

You're done! Refer back to README.md.
