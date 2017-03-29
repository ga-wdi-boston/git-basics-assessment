# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
<!-- Copy the SSH file and clone it into the diagnostics folder using the command: git clone git@github.com:mlynnes/git-diagnostic.git -->
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

<!-- Check to see that the repo is where you want it to be and create a new branch to work on it locally -->

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
<!-- To create a new branch with the name response use the command: git checkout -b response. This also switches you to that branch but to switch back to the master you could use: git checkout master -->
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
<!-- git log -->
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
<!-- git add diagnostic.md -->
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

<!--The first line should be looked at like a subject line of an email and the rest of the text like the body. Write clear messages stating what you have changed in detail.  -->

-7.Should you ever edit published history?

 <!-- No. It is not in best practice to do so. If you make a mistake, work on making changes locally and make new commits. -->
