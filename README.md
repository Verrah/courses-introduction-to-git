# Introduction to Git for Data Science

This course is an introduction to version control with Git
for data scientists
who know just enough about the Unix shell
to run simple commands and edit text files.

## Step 0: Learner Profiles

Please see the [DataCamp Learner Profiles][profile-site] for details.

- [Anya][profile-anya] has been using Subversion on the Unix command line for years,
  but has never used Git.
  This course will show her the similarities and differences between the two.

- [Jasmine][profile-jasmine] has never used version control,
  and has only just completed DataCamp's "Introduction to the Unix Shell".
  Most of the ideas in this course will be new to her.
  She will be disappointed to discover that Git doesn't handle Microsoft file formats cleanly.

- [Thanh][profile-thanh] has used Git from inside RStudio,
  but has never branched or merged.
  This course will show him what's going on under the hood when he does a commit,
  and how to collaborate with colleagues through GitHub.

[profile-anya]: https://github.com/datacamp/learner-profiles#anya
[profile-jasmine]: https://github.com/datacamp/learner-profiles#jasmine
[profile-thanh]: https://github.com/datacamp/learner-profiles#thanh

## Step 1: Concept Map

![Basic Git Concepts](img/git.png)

## Step 2: Summative Assessment

1. Clone the Git repository whose URL you have been given.
2. View the changes made in the most recent commit.
3. Create a new branch called `rewriting-conclusion` and switch to it.
4. In that branch, remove every occurrence of the word "not" from the last paragraph of the file `report.txt`.
5. Commit your changes with the log message "Correcting conclusions".
6. While still in that branch, pull in the content of the `rewriting-intro` branch from the repository you cloned.
7. Merge the changes in that branch with the changes you just made,
   keeping your changes to the last paragraph
   and all of their changes to the other paragraphs.
8. Push the merged to a newly-created branch called `rewriting-conclusion` in the repository you cloned.

## Step 3: Formative Assessments

### Looking at history

Go into the directory `regional` and look at its history.

1. What is the log message of the very first commit?
2. Who made that commit?

### Credit and blame

1. Go into the directory `regional`.
2. Who was the last person to change the first line of the file `central.csv`?

### Viewing differences

1. Go into the directory `regional`.
2. How many lines were changed in the file `northern.csv` in the most recent commit?
3. What files were added in the second-most-recent commit?

### Turning a project into a repository

1. Go into the directory `report`.
2. Use `git init` to initialize Git in that directory.
3. Add all of the files in that directory and its sub-directories to the newly-created repository
   with "Starting to use Git" as the log message.

### Creating a new repository

1. Create a new Git repository called `thesis` inside your home directory.
2. Add these three files (replacing "[your name]" with your name in each case):
   - `README.md` containing the sentence "PhD thesis of [your name]."
   - `LICENSE.md` containing the sentence "Copyright (c) [your name]".
3. Add and commit those two files (and *only* those two files) with the log message "Initializing."

### Saving changes

1. Go into the directory `regional`.
2. Add a line containing the data shown below to the file `eastern.csv`.
3. Commit your change with the log message "Adding September's data."

```
2017,9,30,27,11
```

### Undoing changes

1. Go into the directory `regional`.
2. Undo the most recent *two* commits.

### Listing branches

1. What branches are there in the directory `regional`?
2. Which of these branches are you currently on?

### Comparing branches

1. Go into the directory `regional`.
2. Compare the contents of the `master` branch with the `analysis` branch.
3. Which files contain differences?


### Creating branches

1. Go into the directory `regional`.
2. Create a new branch called `reporting`.
3. Delete the file `reporting.sh` in that branch and commit your changes
   *without* affecting any other branch.

### Merging without conflicts

1. Go into the directory `regional`.
2. Merge the branch `update` into the branch `master`
   using "Consolidating work" as the log message.

### Merging with conflicts

1. Go into the directory `regional`.
2. Merge the branch `update` into the branch `master`.
3. Resolve the conflicts to keep all of the lines containing the word "KEEP".
4. Commit the reconciled version with the log message "Integrating changes".

### Cloning repositories

Clone the repository `file:///home/thanh/work`
to create a repository called `work` in your home directory.

### Exploring remotes

1. Go into the repository `regional`.
2. Which of the following is *not* a remote repository for `regional`?

### Pulling in changes

1. Go into the repository `regional`.
2. Pull changes from the `master` branch of the remote `upstream` into the `master` branch of your repository.

### Pushing changes

1. Go into the repository `regional`.
2. Delete the file `temporary.csv`.
3. Commit your change with the log message "Getting rid of temporary file".
4. Push your change to the remote repository `upstream`.

### Resolving remote conflicts

1. Go into the repository `regional`.
2. Pull changes from the `master` branch of the remote `upstream` into the `master branch of your repository.
3. Resolve the conflicts in `report.txt` to keep all of the lines containing the word "KEEP".
4. Commit your resolution with the log message "Integrating changes".

## Step 4: Course Outline

1. Topic
   1. Sub-topic

The datasets are:

- `filename`: description

## Step 5: Course Overview

### Course Description

### Learning Objectives

- objective

### Prerequisites

- [Introduction to the Unix Shell for Data Scientists][course-shell-intro]

[course-shell-intro]: https://www.datacamp.com/courses/intro-to-unix-shell
[profile-anya]: https://github.com/datacamp/learner-profiles#anya
[profile-jasmine]: https://github.com/datacamp/learner-profiles#jasmine
[profile-site]: https://github.com/datacamp/learner-profiles
[profile-thanh]: https://github.com/datacamp/learner-profiles#thanh
