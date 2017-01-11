# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:akgoode/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

First you change directory into the cloned repository, and then create a new branch and move to it using "git checkout -b <new branch name>".

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
The command to create a new branch is 'git branch response'.  To switch to the new branch we use 'git checkout response'.  These can be combined with 'git checkout -b response'.
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
We use the command 'git status'.
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
We use the command 'git add diagnostic.md'.
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

We need a title with the actions taken in this commit written in the imperative form.  In addition we need a summary of changes written in longer form in the body of the commit message.  In WDI, we avoid using the -m function in the terminal so we can use our text editor to create longer messages.
