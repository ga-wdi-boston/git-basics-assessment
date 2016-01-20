# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.  We just forked a repo on GitHub and want to start working on it locally.
    What command do we use to do that? Use the correct URL for your fork of this
    repository in your answer.

    ```sh
    Once you forked it first you want to navigate your way to the correct folder and use the command `git clone <ssh link copied from github.>`
    ```

2.  What do you do after cloning a repository, but before starting work?

    ```sh
    You would want to first cd into the repository and from there create a new branch that is seperate from the master branch.
    ```

3.  What command do we use to create a new branch? Name this branch `response`
    in your answer.

    ```sh
    there are two ways of doing it:
    1. git branch <name of branch>
        -but this does not checkout the branch
    2. git checkout -b <name of branch>
        - this checks out the branch and creates a new at the same time
    ```

4.  We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

    ```sh
    After staging and committing the changes with messages, you can use `git log`to see the history of changes.
    ```

5.  We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use? Suppose the change is in the current working
    directory and named `diagnostic.md`.

    ```sh
    git add diagnostic.md
    ```

6.  Should you ever edit published history?

    ```sh
    You should never edit a published history, it will have serious reprecussions if you do.
    ```
