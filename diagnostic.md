# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.  We just forked a repo on GitHub and want to start working on it locally.
    What command do we use to do that? Use the correct URL for your fork of this
    repository in your answer.

    ```sh
    <!-- git clone <ssh> (in whatever folder you want the local repo to be in) git branch <new branch name to work in> -->
    ```

2.  What do you do after cloning a repository, but before starting work?

    <!-- create a new branch and then switch to it. Or is this where creating a remote comes in, becuase I think I'm still way off on understanding that. I thought a git clone <ssh> creates a remote for you? -->

3.  What command do we use to create a new branch? Name this branch `response`
    in your answer.

    ```sh
    <!-- git branch response -->
    ```

4.  We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

    ```sh
    <!-- git diff -->
    ```

5.  We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use? Suppose the change is in the current working
    directory and named `diagnostic.md`.

    ```sh
    <!--git add diagnostic.md or git add . to add everything in a directory but that's a probably a bad habit. atom really doens't like me using contractions--unless I use two.-->
    ```

6.  Should you ever edit published history?

    ```sh
    <!-- I'm not entirely clear on what that means...but the answer is no. I think you don't want to edit anything published, only changes made in your own fork, otherwise your messing with someone else's published work. Though shame on them for giving you permission to right? -->
    ```
