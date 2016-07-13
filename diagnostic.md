# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
navigate to the directory you want the repo to be inside of

git clone git@github.com:jordanallain/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

git status to make sure you have cloned the repo properly

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git checkout -b response

this will create a new branch and move to it with the same line of code

you can also just create a branch with git branch response
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git diff
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

A title for the commit that should be short but should summarize the commit

A commit body that goes into more detail of what the commit changed
