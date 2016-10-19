# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:kiraamaa/git-basics-diagnostic.git

```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Change directory to move into the the cloned directory. Then create a new branch (usually named response) and check it out.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
Create branch: git branch response
Switch to branch: git checkout response

You could also use one command of git checkout -b response to make a branch and check it out in sequence.
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
I'm a little confused about the way the question is worded so here are a few answers:

The command ls shows the files that have been changed and that exist within the working directory.
The command cat, followed by the name of the file containing the new code, shows the full text transcript of the code, which you could examine to see your changes.
The command diff --, followed by the name of the file containing the new code, shows the deletions and insertions made to an existing file, and thus could be used as a summary of all changes to the code.

```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

Subject line and body, separated by a blank line.
