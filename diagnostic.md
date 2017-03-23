# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone https://github.com/conorjennings/git-diagnostic.git
```

2.What do you do after cloning a repository, before you start making any
changes/additions?
Change into the new directory from the clone command
 cd git-diagnostic/


3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
I used the following to ensure i go into the correct branch:
git checkout -b response

The other approach is 2 steps as follows:
git branch response
git checkout response

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git status

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

git add <fileName>

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

git commit <nameOfFile>
This will then open Atom and I can put in the relevant checkin comments. Then hit save and exit out to return the command prompt in terminal. From a formating, comment, the assignment(project) number and what has changed in this commit.

-7.Should you ever edit published history?

The only way i can think of is if you needed to check back out an older commit (to get back to say working code) to then work on it again. But that next commit should be a new commit and not overwriting the earlier check in. So I can't see why you'd edit published history.
