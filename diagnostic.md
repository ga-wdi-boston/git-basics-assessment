# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
We navigate in terminal ot the folder where we want to store our local copy of
the directory then type:
git clone git@github.com:treep78/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

We must first move into the repository with:
cd git-basics-diagnostic

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git checkout response
git branch response
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

The first is to use action verbs in a command tense such as "add", "change", and "remove" as appose to saying "added" or "changed". The second is a good description of what was done. This is helped by idealy making only a single change per commit. An example of a commit message in this format might be "add responses to diagnostic.md questions". This allows yourself and other's to see what you've changed at a glance rather than having to go through the changes manually.
