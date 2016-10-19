# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
First thing you do is hit the clone button. Then you go into your terminal, go
to that directory, and then type "git clone" and the paste the key you got from
the clone button you clicked on github
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

You check the git status to see what is already in there and if there are any
things that have not been committed.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
you go to the directory then type "git checkout -b response" and you should be
switched to that new branch
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
You type in 'git status'
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
You type in "git add diagnostid.md"
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

You need a "Title" and a "description"
