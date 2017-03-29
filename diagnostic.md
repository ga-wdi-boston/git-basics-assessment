# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Check to make sure the repository is where i want it and not inside of another repository.
Then create my own branch.

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

I need to specify the file or directory i want to commit. The commit message
needs to have a subject line, first word capitalized, that succinctly describes
the changes I made. Next is a blank line. On the next line I can go into greater
detail about the commit if I need to.
-7.Should you ever edit published history?

 I dont think that would be a good practice, and it seems like it should be
 avoided. Maybe a commit would be discarded retrospectively if its on a branch
 that is no longer in use. A commit could be deleted if I noticed a big mistake
 in it right after I made it. I would like to learn more about common work flow
 and best practices.
