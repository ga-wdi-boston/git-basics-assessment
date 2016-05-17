# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

git clone git@github.com:erinsul/git-basics-diagnostic.git

2.What do you do after cloning a repository, before you start making any
changes/additions?

Create a new branch to isolate your changes.

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

To create the branch   git branch response
To switch to the brance    git checkout response

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

git status

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

git add diagnostic.md

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

A short summary line of the change followed by a blank line, followed by more a
more detailed message.

7.Should you ever edit published history?

You can, but it is extremely dangerous because content can be lost, so do only
with caution. (I am honestly not sure if this was one of those things that we
were given as a ruleto "never" do for now, but when we are smarter, better
programmers we canattempt with caution.) (Or maybe I am misunderstanding this
question!)
