# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

 git clone git@github.com:SquirtleSquad1988/git-basics-diagnostic.git

2.What do you do after cloning a repository, before you start making any
changes/additions?

You would want to create a new branch of the repo in order to make changes that
have no potential for interfering with the original code.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch response
git checkout response
or
git checkout -b response
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git status
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

git messages should not be made in the terminal and should be made using atom.
The commit message should have a short summary no more than 50 characters long
then a line separating the summary then after that a body which contains a more
detailed explanation. The commit message should also be no more than 72 columns
long and should be written in the imperative format.

** created branch diagnostic instead of response
** This will be the edit for commit number 2, all other txt unchanged
