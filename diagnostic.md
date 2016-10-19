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

Go into the cloned repo and create a branch with a new name to work on locally.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
Create a branch by doing:
  git branch [branch-name]

Switch to that branch by doing:
  git checkout [branch-name]

You can also do this in one step by doing:
  git checkout -b [branch-name]


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

Once you do 'git commit' you will be prompted to enter a title and commit message to explain the changes you mad. 
