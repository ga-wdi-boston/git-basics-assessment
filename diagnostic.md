# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:spw5235/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

First, you create a branch (e.g. git branch response).  Next, you move to the branch using the checkout command (e.g. git checkout response).  After this, you start working.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
To create a new branch use the 'branch' keyword: git branch response

To switch to that branch use the 'checkout' keyword: git checkout response
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

The first formatting item is the title/subject line.  It provides a generalization of what changes are made (written in imparative).

The second line is the body line.  It provides a more detailed account of what changes were made with a commit.

The formatting items for a git commit are often compared to that of an email, with the first line being the subject and the body being more detailed text related to the text of the emails.
