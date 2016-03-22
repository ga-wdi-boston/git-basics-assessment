# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.  We just forked a repo on GitHub and want to start working on it locally.
    What command do we use to do that? Use the correct URL for your fork of this
    repository in your answer.

    ```sh
    git clone git@github.com:MichaelB167/git-basics-diagnostic.git
    ```

2.  What do you do after cloning a repository, but before starting work?

    initialize git if it's not already with the command git init. then create a working branch with the command git branch <branchName>

3.  What command do we use to create a new branch? Name this branch `response`
    in your answer.

    ```sh
    git branch response
    ```

4.  We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

    ```sh
    git status or if you want to see specific changes git diff
    ```

5.  We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use? Suppose the change is in the current working
    directory and named `diagnostic.md`.

    ```sh
    git add diagnostic.md
    ```

6.  Should you ever edit published history?

    ```sh
    No because you will create merge conflicts for people downstream.
    ```
