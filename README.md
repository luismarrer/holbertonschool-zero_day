# Git Basics - Holberton Project

Hola, este es mi primer README. Estoy haciendo pruebas. :)


update 31/07/2024:
Este fue mi primer repositorio hecho en Holberton. Creo que también es mi primer repositorio en general.
Por lo basico de su contenido, prefiero ponerlo y dejarlo privado. Quizás más adelante haga un curso centrado
en Git y Github.

update 10/08/2024:
Completé un curso sobre Git. Adémas he estado repasando sobre el tema en general. He llegado a la conclusión
de que volveré a poner este repositorio público, pero mejoraré su README.

----------------------------------------------------------------------------------------------------------------

This repository contains the files and exercises for the Holberton School project on Git. The main objective of this project is to familiarize students with the fundamentals of source code management using Git and GitHub.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts without needing to consult external resources:

### General Concepts
- **Source Code Management**: Understanding the purpose and importance of managing and controlling versions of source code in software development.
- **Git**: What Git is, how it works, and why it's an essential tool for developers.
- **GitHub**: The relationship between Git and GitHub, and how GitHub extends Git's functionality.
- **Git vs GitHub**: The differences between Git (a version control system) and GitHub (a platform that hosts Git repositories).
- **Creating a Repository**: How to set up and initialize a new Git repository from the command line.
- **README Files**: The purpose of README files, and how to write effective ones to document your projects.
- **Committing Changes**: Best practices for making commits in Git, and how to write meaningful commit messages.
- **Pushing Code**: How to push your commits to a remote repository on GitHub.
- **Pulling Updates**: How to pull changes from a remote repository to keep your local copy up to date.
- **Branching**: How to create branches in Git, and why branches are useful for managing different versions of your project.
- **Merging Branches**: How to merge changes from one branch into another, resolving conflicts if necessary.
- **Collaborating on Projects**: How to work with others on the same repository, managing contributions and conflicts.
- **.gitignore Files**: Understanding which files should be excluded from your repository and how to use `.gitignore` files.

## Requirements

This project adheres to the following requirements:

- A `README.md` file at the root of this repository, providing a description of the repository.
- A `README.md` file at the root of the project folder (i.e., `git`), explaining what the project is about.
- All Git operations were performed using the command line, without relying on GitHub's web UI, except for operations that can only be done through the web UI.
- All answer files contain only the command used to perform the task, with no additional information.

## Installation and Setup

To install Git on your terminal, follow these steps:

```bash
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```
*Note: If you are logged in as the 'root' user (e.g., your username starts with 'root'), you can omit 'sudo' from the commands above.*

## Basic Git Commands

By the end of this project, you should be familiar with the following Git command lines:

```bash
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```

## Project Tasks

### 0. Create and setup your Git and GitHub account
**Score: 100.00%**

**Steps:**
1. Create a GitHub account.
2. Generate a Personal Access Token on GitHub to authenticate your repositories.
3. Update your Holberton School Intranet profile with your GitHub username.
4. Create your first GitHub repository with the following details:
    - **Name**: `holbertonschool-zero_day`
    - **Description**: This is my first repository as a full-stack engineer
    - **Public repo**, without README, .gitignore, or license.
5. Open the sandbox environment and clone your repository.
6. Create a `README.md` file with the content `My first readme`, commit with the message "My first commit", and push to the repository.

**Repository**:
- **GitHub repository**: `holbertonschool-zero_day`
- **File**: `README.md`

### 1. Repo-session
**Score: 100.00%**

- Create a new directory called `git` in your repository.
- Ensure that both the root of your repository and the `git` directory contain a `README.md` file with content.
- Commit and push your code to GitHub.

**Repository**:
- **GitHub repository**: `holbertonschool-zero_day`

### 2. Coding fury road
**Score: 100.00%**

- Create directories: `bash`, `c`, `js` at the root of your project.
- Create the following files:
  - `c/c_is_fun.c`
  - `js/main.js`
  - `js/index.js`
  - `bash/best` with content: `#!/bin/bash` and `echo "Best"`
  - `bash/school` with content: `#!/bin/bash` and `echo "School"`
- Add, commit with the message "Starting to code today, so cool", and push your changes.

**Repository**:
- **GitHub repository**: `holbertonschool-zero_day`
- **Directory**: `git`
- **Files**: `bash/best`, `bash/school`, `c/c_is_fun.c`, `js/main.js`, `js/index.js`

### 3. Collaboration is the base of a company
**Score: 100.00%**

- Create a branch `update_script` and:
  - Add an empty file named `bash/98`
  - Update `bash/best` to `echo "Best School"`
  - Update `bash/school` to `echo "The school is open!"`
  - Commit with the message "My personal work" and push.
- Change back to the `main` branch:
  - Update `bash/best` to `echo "This School is so cool!"`
  - Delete the `js` directory.
  - Commit with the message "Hot fix" and push.

**Repository**:
- **GitHub repository**: `holbertonschool-zero_day`
- **Directory**: `git`
- **Files**: `bash/best`, `bash/school`, `bash/98`

### 4. Collaboration: be up to date
**Score: 100.00%**

- Update your `README.md` file on GitHub from the web interface.
- Pull the changes locally, create a new file `up_to_date` in the `git` directory, containing the Git command you used to pull the changes.
- Commit with the message "How to be up to date in git" and push.

**Repository**:
- **GitHub repository**: `holbertonschool-zero_day`
- **Directory**: `git`
- **Files**: `README.md`, `up_to_date`

### 5. HAAA what did you do???
**Score: 100.00%**

- Merge the `update_script` branch into `main`. Resolve the merge conflict in `bash/best` by keeping the version from `update_script`.
- Push the changes to the origin.

**Repository**:
- **GitHub repository**: `holbertonschool-zero_day`
- **Directory**: `git`

### 6. Never push too much
**Score: 100.00%**

- Create a `.gitignore` file in the `git` directory.
- Define a rule in `.gitignore` to prevent Emacs backup files (those ending with `~`) from being pushed to the repository.

**Repository**:
- **GitHub repository**: `holbertonschool-zero_day`
- **Directory**: `git`
- **File**: `.gitignore`

## Conclusion

This project serves as a foundational introduction to Git and GitHub, which are essential tools for version control in software development. Mastery of these concepts will greatly enhance your ability to collaborate on projects and manage your code effectively.

Feel free to explore the repository and review the exercises to reinforce your understanding of Git.
