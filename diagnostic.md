# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
<!-- git@github.com:lcurran/git-basics-diagnostic.git -->
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

```sh
<!-- cd move into the newly created repo -->
```

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
<!-- git branch response, git checkout response -->
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

```sh
<!-- You are required to have a header, followed by an empty paragraph and
 then the body of your commit message. -->
```

7.Should you ever edit published history?

```sh
<!-- If you are working on a public repository with other developers, then no
you should never go back and alter published commits, because they might
be working on something that involves that piece of code -->
```
