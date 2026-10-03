# Lab 4 Notes

## Question 1
`--global` means the Git configuration applies to all repositories for my user account on this computer. If I leave it out, the configuration applies only to the current repository.

## Question 2
The `.git` directory appeared because it is a hidden directory that stores Git's repository information, including the commit history, configuration, and other data Git needs to track the project.

## Question 3
Git was offering to track roughly six top-level files or folders. `Safe Exam Browser.app` looked like something I did not write myself because it is an application rather than my lab work.

## Question 4
After creating `.gitignore`, `.DS_Store` disappeared from the untracked files, and the files inside `.venv` were also ignored. The files matching the patterns in `.gitignore` were no longer shown by `git status`.

## Question 5
`.gitignore` should be committed because it is part of the project's configuration. It tells Git which files and folders should be ignored, so keeping it in the repository makes the same rules available to anyone working on the project.

## Question 6
`README.md` moved from the “Untracked files” section to “Changes to be committed.” In the three-places model, this means I moved it from the working directory into the staging area with `git add`.

## Question 7
Git printed a summary showing that 137 files changed, with 21,573 insertions. The commit also listed the files that were added to the repository.

## Question 8
The first seven characters of my commit hash are `365a1d3`. They are the short form of the commit's unique hash, which Git uses to identify and refer to that specific commit.