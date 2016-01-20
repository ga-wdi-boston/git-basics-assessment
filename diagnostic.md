# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.  We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the correct URL for your fork of this
repository in your answer.

git clone git@github.com:kpie89/git-basics-diagnostic.git

2.  What do you do after cloning a repository, but before starting work?

git init and create a new branch

3.  What command do we use to create a new branch? Name this branch `response`
in your answer.

git checkout -b <response>

4.  We just wrote some code. What command do we use to see a summary of the
changes in our working directory?

git log

5.  We want to prepare a change for a commit by adding a file to the staging
area. What command do we use? Suppose the change is in the current working
directory and named `diagnostic.md`.

git add diagnostic.md

6.  Should you ever edit published history?

YOU BETTA NOT. No, you should never rewrite history.
