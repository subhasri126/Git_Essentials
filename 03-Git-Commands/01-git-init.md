# git init

## What is git init?

`git init` is used to initialize a new Git repository. It converts a normal project folder into a Git repository.

---

## Why Do We Use git init?

Before using any Git commands, Git must be initialized for the project. After initialization, Git starts tracking the project.

---

## Syntax

```bash
git init
```

---

## Example

```bash
mkdir Student-Management-System
cd Student-Management-System

git init
```

Output:

```
Initialized empty Git repository in D:/Student-Management-System/.git/
```

---

## What Happens After Running git init?

- A hidden `.git` folder is created.
- Git starts managing the project.
- The project becomes a Git repository.
- Other Git commands can now be used.

---

## Key Points

- Initializes a new Git repository.
- Creates the hidden `.git` directory.
- Required before using Git in a new project.
- Running `git init` again does not delete existing commits.

---

## Summary

`git init` is the first command used in Git. It creates a hidden `.git` directory and allows Git to start tracking the project.