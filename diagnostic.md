# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone https://github.com/ga-wdi-boston/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

cd into your new repo, create a new branch if necessary then checkout into the new branch.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch <branch name>, in this case it will be git branch response. to switch over to your new branch use the checkout command (git checkout <branch>)```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git status will give you info on all the files in your repo, including any modifications like your fresh code.
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md - this will stage diagnostic.md file```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

git commit will open up atom allowing you to add a short message for your commit, this consist of a subject line, similar to an email, and the body of the message.
