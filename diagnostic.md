# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.  We just forked a repo on GitHub and want to start working on it locally.
    What command do we use to do that? Use the correct URL for your fork of this
    repository in your answer.

    git clone git@github.com:msyao-github/git-basics-diagnostic.git

2.  What do you do after cloning a repository, but before starting work?

    Add a remote (git remote -v) to the cloned repository.

3.  What command do we use to create a new branch? Name this branch `response`
    in your answer.

    git checkout -b _______
    ______ is the branch name

4.  We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

    git log

5.  We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use? Suppose the change is in the current working
    directory and named `diagnostic.md`.

    git add diagnostic.md

6.  Should you ever edit published history?

    You could edit published commits but you should avoid (never) do that
    because it will show the edited commits as new commits and will be
    confusing to other developers viewing the commits.
