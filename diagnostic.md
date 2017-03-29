# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
to work on this repo locally, we clone it onto our desired directory by using the
command: git clone git@github.com:TronB/git-diagnostic.git

```

2.What do you do after cloning a repository, before you start making any
changes/additions?

type in the command: git status, to see if there are any files that have been
modified

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
You can type in git checkout -b response to both create the response branch as
well as switching over to that specific branch. To JUST create a branch, you
would input the command: git branch *NAME YOUR BRANCH HERE*. Additionally,
if you want to ONLY switch branches you would type: git checkout *ENTER BRANCH HERE*

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

There should be a commit message that says you can use the command:
git reset HEAD <file name(s)> to bring the committed files back to the unstaged
status AND show a list of the modified files that are currently waiting to be
committed

-7.Should you ever edit published history?

You should not as a best practice. If there are multiple people working on
the same repo, this will become problematic for everyone else
