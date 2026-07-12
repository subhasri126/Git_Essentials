# Repository

## What is a Repository?

A Repository (Repo) is a storage location where a project's files, folders, and complete version history are maintained. It allows Git to track changes, manage different versions, and maintain the history of a project.

A repository contains:
- Project files
- Git history
- Commits
- Branches
- Configuration files

---

## Types of Repository

Git mainly uses two types of repositories:

### Local Repository

A Local Repository is stored on the developer's local machine. It contains the complete project along with its version history. Every commit is first saved in the Local Repository.

### Remote Repository

A Remote Repository is stored on a remote hosting platform such as GitHub. It is mainly used for collaboration, backup, and sharing projects with other developers.

---

## Local Repository vs Remote Repository

| Local Repository | Remote Repository |
|------------------|-------------------|
| Stored on the local machine | Stored on GitHub or another remote server |
| Used for local development | Used for collaboration and backup |
| Commits are saved here first | Receives commits using `git push` |

---

## Repository Creation

A repository can be created in two ways:

### Method 1

Create a repository on GitHub and clone it to your local machine using:

```bash
git clone <repository-url>
```

### Method 2

Create a project folder locally and initialize Git using:

```bash
git init
```

After initialization, connect the local repository to GitHub and push the project.

---

## Key Points

- A repository stores the complete project and its version history.
- Git supports Local and Remote Repositories.
- Every commit is first stored in the Local Repository.
- GitHub stores the Remote Repository.
- Local and Remote Repositories can be synchronized using Git commands.

---

## Summary

A Repository is the central place where Git stores and manages a project's files and history. Git uses Local Repositories for development and Remote Repositories for collaboration and backup.