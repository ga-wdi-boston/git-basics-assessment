# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git remote add origin <https://github.com/user_name/repo_name>
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

create a feature branch, in this case, 'response'

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch 'response' creates the branch. git checkout 'response' switches to the branch. This can be done in one command with git checkout -b 'response'
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git status
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add 'diagnostic.md'
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

The first line in the commit message is the concise title of the commit.
After skipping a line in the message file, the second item is the description
of the commit, explaining what was changed and why.

-7.Should you ever edit published history?

 Published history on GitHub should never be changed. All updates should take
 place through git commit messages.
