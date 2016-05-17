# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:SarahHartwick/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Change directory into the cloned repository and then create and checkout a new
branch if you choose to do so.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch response
git checkout response

OR

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

The commit message should have a brief heading summarizing the changes made,
as well as a more detailed description two lines beneath it (can include
bullet points here if desired.)

7.Should you ever edit published history?

Git gives you the ability to edit published history if you feel it is
necessary for clarity and efficiency when working with others.

For example if you committed too many changes in one commit and it becomes
confusing, you are able to split these commits, amend commit messages and even
reorder commits to reflect the clearest picture of your version history.
