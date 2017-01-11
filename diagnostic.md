# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.


```sh
You fork it then copy and paste your SSH with git clone into your terminal:
$ git clone git@github.com:farrahj99/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

You utilize the command cd to create a storage place for the fork and clone...
For this instance: cd git-basics-diagnostic

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
We use git branch response and then we switch to that branch with
git checkout response
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
We utilize git status to see a summary of changes in our working directory.
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
We stage a file by using the command: git add <filename>. In this case:
git add diagnostic.md.
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

You would do git status to make sure it turns green, then git commit
and lastly git push origin response. 
