# Git and GitHub Handbook <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Git](#git)
  - [What is Git?](#what-is-git)
  - [Why use Git?](#why-use-git)
  - [How to use Git?](#how-to-use-git)
- [GitHub](#github)
  - [What is GitHub?](#what-is-github)
  - [Why use GitHub?](#why-use-github)
  - [How to use GitHub?](#how-to-use-github)
- [Git Commands](#git-commands)
  - [Basic Git Commands](#basic-git-commands)
- [GitHub Commands](#github-commands)

## Git

### What is Git?

Think of Git as a **library** for your code. Just like a library keeps track of all the books (versions of your project), Git helps you manage and track changes to your code. It allows multiple authors (developers) to work on different books (features) at the same time without losing their work.

### Why use Git?

Using Git is like having a **notebook** where you can jot down your thoughts (code changes) without worrying about losing previous notes. If you make a mistake, you can easily flip back to an earlier page (previous version) and correct it. This makes collaboration smoother, as everyone can write in their own notebooks without interfering with each other.

### How to use Git?

To start using Git, follow these steps:

1. **Install Git**: Download and install Git on your local machine, just like you would get a library card to access the library.
2. **Create a Git Repository**: Navigate to your project directory in the terminal and run `git init`. This is like setting up a new shelf in the library for your project.
3. **Track Changes**: Use Git commands to track changes, commit your code, and push updates to a remote repository, similar to adding new books to your library shelf.

## GitHub

### What is GitHub?

GitHub is like an **online library** where you can store and share your code with others. It provides a platform where multiple authors can collaborate on the same book (project) and read each other's notes (code).

### Why use GitHub?

GitHub is popular because it offers a **community bulletin board** where developers can post updates, ask questions, and review each other’s work. It has features like pull requests (suggestions for changes) and issues (to-do lists), making it easier for teams to work together.

### How to use GitHub?

To use GitHub, follow these steps:

1. **Create an Account**: Sign up for a free GitHub account.
2. **Set Up a Repository**: Create a new repository on GitHub for your project, similar to reserving a section of the library for your book.
3. **Push Code**: Use Git commands to push your local code to the GitHub repository, like putting your completed book on the library shelf for others to read.

## Git Commands

### Basic Git Commands

Here are some essential Git commands explained with analogies:

1. **Initialize a Repository**:

   ```bash
   git init
   ```

   This is like putting a new empty notebook on your desk, ready for you to start writing.

2. **Add Changes**:

   ```bash
   git add .
   ```

   Think of this as collecting all your notes (changes) and putting them into a folder, preparing them for review.

3. **Commit Changes**:

   ```bash
   git commit -m "Your commit message"
   ```

   This is like saving a chapter of your book. You write a summary (commit message) so you can remember what changes you made.

   For example, if you added a new character to your story, your commit message could be “Added a new character.” or if you work as a UX designer and you made some changes to the design of a website, your commit message could be “Updated website layout.”

4. **Check Status**:

   ```bash
   git status
   ```

   This is like checking the table of contents of your notebook to see what chapters (files) are completed and what still needs work.

5. **View Commit History**:

   ```bash
   git log
   ```

   Imagine flipping through the pages of your notebook to see all the chapters you’ve written so far.

## GitHub Commands

In addition to Git commands, here are some GitHub-specific commands explained with analogies:

1. **Clone a Repository**:

   ```bash
   git clone <repository-url>
   ```

   This is like photocopying a book from the library so you can read and annotate it at home.

   For example, you can clone this repository by running `git clone https://github.com/msosav/git-and-github-handbook.git` and you’ll have a copy of this handbook on your local machine.

2. **Push Changes**:

   ```bash
   git push origin branch_name
   ```

   This is like returning your completed book to the library so others can read it.

   For example, if you made changes in your local repository and you want to update the online repository on GitHub, you would push your changes using the command `git push origin main`. This sends your changes to the main branch of the repository on GitHub.

3. **Pull Changes**:

   ```bash
   git pull origin branch_name
   ```

   Imagine checking out the latest edition of a book from the library to see what new chapters have been added.

   For example, if someone else made changes to the online repository on GitHub and you want to update your local repository with those changes, you would pull the changes using the command `git pull origin main`. So, if a UX designer made some changes to the design of a website and you want to see those changes, you would pull the changes to your local repository.

4. **Create a Pull Request**: After pushing changes, go to your GitHub repository and create a pull request. This is like submitting your book for review, asking others to read it and suggest edits before it gets published.
