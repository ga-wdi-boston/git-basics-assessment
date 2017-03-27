# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:narichasavanorkejoyce/git-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

// Navigate to the folder containing the cloned Git repo
cd git-diagnostic

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
// Create a new branch called response.
// Switch over to the response branch.
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

1. First line in commit message is a short (less than 50 char) summary of the edit
   (similar to the subject of an email)
2. Ensure there is a one line break after the summary line.
3. Add details about the change, describing how/why you made these edits
   (similar to the body of an email)

-7.Should you ever edit published history?

 No, it is generally not a best practice to edit published history.
 Instead, make another commit and describe why you had to make that edit.
