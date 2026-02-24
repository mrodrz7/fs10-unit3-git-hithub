# Git Lesson

- version control system created by Linus Torvals in 2005
- allows multiple developers to contribute to the same codebase
- that codebase or poject is called a repository (repo for short)

## First Time Git Setup

- to see your git config, use the command `git config --global --list`
- to set your username, use `git conifg user.name --global "first last"`
- to set your email, use `git config user.email --global "email@here.com"`

## How to use Git

- **in the folder in which you intend to create a project** initialize a new git repository
- initialize a new repository using `git init` command
- to check the status of the repo, use `git status` command
- in order to tracj files, use `git add <name of file>` to track a file
    - if you want to add all of the files at once, use `git add .`
- if you would like to unstage a file, you can use `git rm --cached <name of file>` to do so
- if you are ready to commit, use the `git commit -m "your commit message here"`

## Git Lingo

- branch - a timeline of your code at any given point
- the default branch is called the `main` branch or `master`
- commit - a snapshot of your code at a specific point in time

## Git Stages

- [ ] tracking
    - a way for us to decide which files git will track in its repo
- [ ] staging
    - a way for us to decide what will become a commit
- [ ] commiting

## Git Log Explained

- commit hash - unique value describing our commit
- main/master (or other) - name of the branch on which the commit resides
- HEAD - think of it as eyes - it points to what our eyes are looking at 
- author of the commit
- date the commit occurred
- commit message