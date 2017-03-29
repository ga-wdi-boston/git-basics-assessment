# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
We clone the repo in Github first, and then go to the diagnostics folder within wdi and use the command "git clone git@github.com:xiangcatherine/git-diagnostic.git"
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Make a new branch, so that you're not making changes to the master.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
Make a new branch using the command "git checkout -b response"
This command both creates a new branch and switches to it.
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
We use the command "git status"
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
We use the command "git add diagnostic.md"
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

A short summary and a more detailed explanatory message of what was done and why. 

-7.Should you ever edit published history?

 No.
