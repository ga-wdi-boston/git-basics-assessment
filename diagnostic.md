# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:eliottenos/git-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Create a branch

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git checkout -b response

This will create the new branch and enter it in one command
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

Commit messages should be detailed and clear to read.  Close your editor to commit
message

-7.Should you ever edit published history?

 No, you shoudnt edit history once it has been published.  It is important to make
 a clear, detailed commit message.
