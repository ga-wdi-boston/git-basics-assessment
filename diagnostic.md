# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:sstone72389/git-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

ensure you are in the correct directory and create a new branch

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?
```sh
Either: git branch response, git checkout response
or all in one: git checkout -b response
```
4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
I am not 100% as to the context of this question. To see the changes on the commit,
you would use git log. To use the cmd line to view actual changes you can
concatenate.
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

Top line (essentially a subject line), that is a simple breifing of the commit.

below this: you provied an explanation for your changes. Can be as long as needed
but a best practice would be to keep it concise and as short as possible given
that is possible. Make it easier for your colleagues to follow along.

-7.Should you ever edit published history?

No you should not.
