# Introduction to Git

## Objective

Understand what Git is, how a repository works, and the difference 
between a local and a remote repository.

---

## Important Concepts

### Git

A distributed version control system.
It allows you to record all changes made to a project.

### GitHub

A service that hosts Git repositories in the cloud.
It facilitates project sharing and teamwork.

### Repository

A collection of files along with the complete change history stored by Git.

### Local Repository

This is the copy of the project that exists on your computer.

### Remote Repository

This is the copy of the project hosted on GitHub.
By default, Git uses the name **origin** to refer to the remote repository.

### git clone

Creates a local copy of the remote repository.

It also:
- downloads all files
- Download the complete history
- Create the `.git` folder
- Configure the remote `origin`

### `.git` Directory

Contains all the information Git needs to manage the project.

Some important folders are:
- objects
- refs
- hooks
- logs

And some important files:
- HEAD
- config

### ~/.gitconfig

Global user configuration.

Example:
- name
- email

### .git/config

Repository-specific configuration.

Example:
- Remote URL
- Origin
- Remote branches

---

## Lab Completed

- Git Installation
- User Configuration
- Repository Cloning
- Exploring the `.git` Folder

---

## Commands Used

```bash
git config
git init
git clone
git status
git branch
git remote -v
cat HEAD
cat config
ls -la
```

## What I Learned

In this lab, I understood that Git and GitHub are different tools:
Git manages the project history on my computer, while
GitHub hosts a remote copy of the repository.

I learned that the `git clone` command not only downloads the project 
files, but also its entire history and creates the `.git` folder, 
which contains the information necessary for Git to manage the repository.

I also understood the difference between the user's global 
configuration (`~/.gitconfig`) and the repository-specific 
configuration (`.git/config`).

Furthermore, this lab allowed me to continue practicing using the 
Linux terminal and familiarize myself with the directory structure 
and hidden files.
