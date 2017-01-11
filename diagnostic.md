# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:doremaxime/git-basics-diagnostic.git```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Open the repo and git checkout -b response to create&work from that branch.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
"git checkout -b response" However, there is a way to command it in two fold where you create it and then command it to go into the branch but why not just kill two birds with one stone?```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git status```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

Title and message. As a little plus I will add that in the title use action rather than doing. By that I mean say 'make loop for age var' instead of 'made llop for age var' for example.
