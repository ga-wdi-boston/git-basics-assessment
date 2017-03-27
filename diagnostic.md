# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone https://github.com/kqngo/git-diagnostic.git
"```

2.What do you do after cloning a repository, before you start making any
changes/additions?

```sh
we need to change our working dirctory into the root of the repo we cloned
we need to create and switch to a response branch
"```

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch response
git checkout response
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

need to have 1) the title (summary of changes), and 2) a description of changes made.

-7.Should you ever edit published history?

Published history is used for auditing and tracking, and should not be tampered/edited in any way.
