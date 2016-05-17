# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:acobrelo/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

First, cd into the new directory, git status to make sure there's nothing that's going to catch you off guard later on, then create a new branch and checkout the new branch before making any changes/additions.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch response
git checkout response
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

You need a header that's brief but descriptive and a summary two lines beneath the header, which can be longer but also must be descriptive and as concise as possible.

7.Should you ever edit published history?

Nope! Rewrite history, risk changing the future. 
