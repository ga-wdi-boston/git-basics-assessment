# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:noobiwankenoobi/git-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

You make sure you move into the correct directory and that it says (master) next to it.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
I like to create a branch and move to it in the same command.
We use:
git checkout -b <branchname> to do that
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
we use:   git status
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
We use:   git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

Capitalize the subject line. Limit it to 50 characters.
I think you should limit the width of your commit message overall to 72 characters.
I've also read that you should separate the subject line from the body with a blank space.

-7.Should you ever edit published history?

No, you should never manually edit published history
