# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
~/wdi/diagnostics $ git clone git@github.com:modularjon/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

git status to check for a clean working directory

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
In one command: git checkout -b response

In two: git branch response
        git checkout response
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git diff to see the changes within the files in the directory. git status to see an overview of unstaged changes to files.
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

A capitalized short summary, and some more detailed explanatory text describing the changes you made in the imperative, specifically what, why and how.

7.Should you ever edit published history?

<!-- Remove this comment and place your answer here. -->
