# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone https://github.com/joaufi/git-basics-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

'git status' to ensure a clean working directory.
AND/OR 'git checkout <branch>' if a feature or dev branch exists so you
  are not modifying the master branch directly. If a feature or dev branch
  does not exist make one with 'git checkout -b <branch>'

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
git branch response
git checkout response
<OR>
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

Add a summary of your commit (50 chars or less)!

Add a further description of your commit in 72 - 80 chars width
Be sure to add a blank line between the summary and description!
Use imperative verbs (so 'create', 'add', 'initialize') instead
  of past-tense verbs.
Write as much as you want in your description! As long as it helps
  describe what you did.
Try to use concise, easy to follow language. These commit messages
  are for you as well as others!
