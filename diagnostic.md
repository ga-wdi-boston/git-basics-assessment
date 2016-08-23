# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:tuckyeah/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

After cloning a repo, you should make sure that you have changed into the repo folder. Then, ideally, you should create a new branch for your work and switch
to that branch, using 'git checkout -b <branch_name>'

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch response
git checkout response

(or do both at once using 'git checkout -b response')
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git status will show us the files that have been modified but not staged, as
well as any files that we have staged.

git diff will show you all changes between the last commit and the current state of the files.
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
<!-- Remove this comment and place your answer here. -->
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

<!-- Remove this comment and place your answer here. -->
