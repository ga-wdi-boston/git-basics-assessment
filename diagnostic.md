# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.  We just forked a repo on GitHub and want to start working on it locally.
    What command do we use to do that? Use the correct URL for your fork of this
    repository in your answer.

    ```sh
    git clone git@github.com:rdelvallej32/git-basics-diagnostic.git
    ```

2.  What do you do after cloning a repository, but before starting work?

    You create a new branch by checking out of master branch.

3.  What command do we use to create a new branch? Name this branch `response`
    in your answer.

    ```sh
    git checkout -b response
    ```

4.  We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

    ```sh
    git log
    ```

5.  We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use? Suppose the change is in the current working
    directory and named `diagnostic.md`.

    ```sh
    The first command to prep a change for a commit is the 'add .' command.
    If it is in the current working directory, then it is 'add diagnostic.md'.
    Once added, you need to commit after it has been staged by typing 'commit'
    ```

6.  Should you ever edit published history?

    ```sh
    You shouldn't edit published history because it could prove useful to
    reference back to it in case some projects/code starts to go haywire after
    that point in time. It can be a tool to reference what the developer did
    at that time to aid with bug fixes.
    ```
