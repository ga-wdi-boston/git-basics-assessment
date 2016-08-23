# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:DanielJRaine/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

git status #makes sure everything worked correctly.  Generally running git status after each git command is not a bad idea.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch response
git checkout response

git checkout -b response  #this will do both in one step
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git status #this will tell you which files was modified
git diff #this will show you more in depth what changes were made
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

```sh
Subject  #should be capitalized, short, in present tense/imperative.
         #separated by a blank new line
Body     #tells more detail the intention and the 'why' of the commit
```
