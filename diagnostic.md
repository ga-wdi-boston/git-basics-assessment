# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
<!-- git@github.com:kellye2010/git-diagnostic.git -->
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

<!-- You then change directories to ensure that you are now in the repository you've cloned. You know that you are in the right repository and ready to continue if the repository you are in is now labeled "(master)". Next you create a branch from this repostory (labeled what you need to label the branch as), and "checkout" that newly created branch.  -->

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
<!-- git checkout -b branchName -->
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
<!-- git status -->
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
<!-- git add diagnostic.md -->
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

<!-- You need a detailed description (but not the code itself) of the changes you've made and why.-->

-7.Should you ever edit published history?

 <!-- No, the published history is HISTORY for reason to reference past versions. -->
This is just an added space for change
