# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
Clicked the fork button in the git UI. copied the URL: git@github.com:joehsuLM/git-diagnostic.git. On my local device, 'cd' to ~/wdi/diagnostics/ and use the command: `git clone git@github.com:joehsuLM/git-diagnostic.git`
```

2.What do you do after cloning a repository, before you start making any
changes/additions?

cd into the newly cloned directory, 'git-diagnostic'

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
this can be done with a one line command: `git checkout -b response`
```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
`git diff`
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

need a subject line (line 1) and a description of the changes (line 3)

-7.Should you ever edit published history?

 No, rather new updates should be made via subsequent pushes. [adding some text for a 2nd commit.]
