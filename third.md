# Junior Git Intro

Welcome to the Junior Git Intro guide. This document will help you get started with Git and version control.

## Table of Contents

1. Introduction to Git
2. Setting Up Git
3. Basic Git Commands
4. Working with Branches
5. Merging and Rebasing
6. Collaborating with Others
7. Best Practices

## 1. Introduction to Git

Git is a distributed version control system that helps you track changes in your code and collaborate with others.

## 2. Setting Up Git

To set up Git, follow these steps:

1. Download and install Git from [git-scm.com](https://git-scm.com/).
2. Configure your Git username and email:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

## 3. Basic Git Commands

Here are some basic Git commands to get you started:

- `git init`: Initialize a new Git repository.
- `git clone <repository-url>`: Clone an existing repository.
- `git status`: Check the status of your working directory.
- `git add <file>`: Stage changes for commit.
- `git commit -m "message"`: Commit staged changes with a message.

## 4. Working with Branches

Branches allow you to work on different features or fixes simultaneously. Use the following commands to manage branches:

- `git branch`: List all branches.
- `git branch <branch-name>`: Create a new branch.
- `git checkout <branch-name>`: Switch to a different branch.
- `git merge <branch-name>`: Merge changes from one branch into another.

## 5. Merging and Rebasing

Merging and rebasing are ways to integrate changes from one branch into another. Use `git merge` to combine changes and `git rebase` to apply changes on top of another branch.

## 6. Collaborating with Others

To collaborate with others, you can use remote repositories. Here are some commands to help you:

- `git remote add <name> <url>`: Add a remote repository.
- `git fetch <remote>`: Fetch changes from a remote repository.
- `git pull <remote> <branch>`: Pull changes from a remote branch.
- `git push <remote> <branch>`: Push changes to a remote branch.

## 7. Best Practices

- Commit often with meaningful messages.
- Use branches to manage different features or fixes.
- Regularly pull changes from the remote repository to stay up-to-date.
- Review changes before merging or rebasing.

Happy coding!
