# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

To work with the repo locally, we git clone the given fork using the ssh key. Ex: git@github.com:cpstrillvt93/git-basics-diagnostic.git


2.What do you do after cloning a repository, before you start making any
changes/additions?

Before making any changes/additions, we create a new branch to make our changes on.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

git checkout - b response. We should now be in that folder and ready to open it.

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

git diff to see the changes and git status to see where its at in the process


5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?


git add diagnostic.md

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

1. file name. 2.Git push origin
