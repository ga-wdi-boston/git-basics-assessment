# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
https://github.com/donpowers/git-diagnostic
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

you clone it

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git checkout -b response
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

The first line should be a like a subject line in an email...Fixed bug in
the howManyDays()

Use bullet type items to explain in more detail what was changed.

 - fixed array index problem when incorrect day was given

-7.Should you ever edit published history?

 No. I think this would mess things up. Not sure what a better practice should be

found this on the web...
However, keep two important details in mind:

Amend only works with the very last commit. If you notice your mistake only after adding another commit, amend won't help you much.
Amend rewrites the commit history in your repository: the old commit is replaced by a completely new one (a new and different commit object). This makes it very important that you don't amend (= rewrite) commits that you've already published to a remote repository! Because in that case, your colleagues might have already based their work on this commit - which you would try to replace using "amend".
