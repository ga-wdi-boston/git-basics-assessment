# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
To clone the repository you use: git clone git@github.com:JaimeGaribaldo7/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

After you clone the repo, you should make a new branch and switch over to that
branch.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
To create a new branch, you use: git branch response. After you created the branch, you switch over to it by using: git checkout response.
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
To see what changes we made, you use: git log. this will show us a list of the
commits that we made.
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
To add the file to the staging area, you use: git add diagnostic.md.
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

The two formatting items you need to make up the commit message are: a subject
and a body.
