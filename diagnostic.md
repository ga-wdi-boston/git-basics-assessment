# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:Maggicorp/git-diagnostic.git

```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Create a new branch

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch response, then git checkout response. Or git checkout -b response
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

Your commit message should have a title and a description

-7.Should you ever edit published history?

You should not go back and edit published history, as it will just make it more confusing for people who you are sharing it with.   If you want to make a change you should make it in a new commit.  Or, if you want to change a commit message before you publish that is probably a good idea as well, but you should not go back after you have published and alter the past.
