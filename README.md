# Git and GitHub Commands

This repository contains detailed information and examples of various Git and GitHub commands. It's designed to help both beginners and experienced developers understand and use version control effectively.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started with Git](#getting-started-with-git)
  - [Installing Git](#installing-git)
  - [Basic Git Commands](#basic-git-commands)
- [Git Configuration](#git-configuration)
  - [Setting Up User Information](#setting-up-user-information)
- [Working with Repositories](#working-with-repositories)
  - [Creating a Repository](#creating-a-repository)
  - [Cloning a Repository](#cloning-a-repository)
- [Branching and Merging](#branching-and-merging)
  - [Creating and Switching Branches](#creating-and-switching-branches)
  - [Merging Branches](#merging-branches)
- [Collaboration with GitHub](#collaboration-with-github)
  - [Forking a Repository](#forking-a-repository)
  - [Creating a Pull Request](#creating-a-pull-request)
- [Additional Resources](#additional-resources)

## Introduction

Git is a powerful version control system that helps developers manage changes to their codebase over time. GitHub is a web-based platform that uses Git and provides additional collaboration features.

## Getting Started with Git

### Installing Git

To install Git, visit the [official Git website](https://git-scm.com/download) and download the appropriate version for your operating system.

### Basic Git Commands

- `git init`: Initialize a new Git repository.
- `git status`: Show the status of changes in the working directory and staging area.
- `git add <filename>`: Stage changes for commit.
- `git commit -m "Commit message"`: Commit staged changes with a message.

## Git Configuration

### Setting Up User Information

Set your user name and email address:
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

