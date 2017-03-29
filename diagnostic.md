# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
we should use the command: git clone git@github.com:jbeltrami/git-diagnostic.git>
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

You create a new branch using: git checkout -b <name of your branch>

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git checkout -b response would create a new branch and switch you to that branch
at the same time.
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

Create a title in one line, skip the next line and start writing your message on
the third line. should always be able to describe what changes happened in that
file in an imperative way.

-7.Should you ever edit published history?

 As a good practice, one should always create a new branch, work and commit
 on that branch, before pulling it back to the origin repository. If you make
 any changes, make sure you commit, explaning what those changes were.
