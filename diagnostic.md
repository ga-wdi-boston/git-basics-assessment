# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
In order to start working on a forked repo locally, it must be cloned to your computer.
The command for this is: git clone git@github.com:andyjzhong/git-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Change directories into that folder and create a new branch before you start making any changes.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
In order to create a new branch called 'response', type git checkout -b response.
To switch to that branch, we type git checkout response.
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
To see the summary of the changes in our working directory, type git status to identify the untracked changes we made.
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
In order to add a file to the staging area, we would use the git add diagnostic.md command.
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

By formatting items for the commit message, is this referring to creating the name/title of the commit and a description of the commit?

-7.Should you ever edit published history?

Nah bro. Bad for documentation.
