# git commit

## What is git commit?

`git commit` is used to save the staged changes permanently in the **Local Repository**. Every commit creates a new version (snapshot) of the project.

---

## Why Do We Use git commit?

The `git commit` command is used to save the staged changes and maintain the version history of a project. It allows developers to track changes and restore previous versions whenever required.

---

## Syntax

```bash
git commit -m "Commit Message"
```

Example:

```bash
git commit -m "Added Login Page"
```

---

## What Happens After Running git commit?

- Staged changes are saved in the Local Repository.
- A new commit (snapshot) is created.
- A unique Commit ID (SHA Hash) is generated.
- The commit message is stored.
- The project history is updated.
- The HEAD pointer moves to the latest commit.

---

## Commit ID (SHA Hash)

Whenever a commit is created, Git automatically generates a unique **Commit ID (SHA Hash)**.

Example:

```text
8a3f2c1b9d6a4e5f7c8d9e1234567890abcdef12
```

This unique ID helps Git identify every commit in the repository.

---

## HEAD Pointer

**HEAD** is a pointer that always points to the **latest commit** of the current branch.

Whenever a new commit is created, Git automatically moves the HEAD pointer to that commit.

Example:

```text
Before Commit

Commit A ← Commit B
              ↑
            HEAD

After Commit

Commit A ← Commit B ← Commit C
                         ↑
                       HEAD
```

---

## Common Usage

### Commit with a Message

```bash
git commit -m "Initial Commit"
```

Creates a commit with a meaningful message.

---

### Stage and Commit Modified Files

```bash
git commit -am "Updated Project"
```

Stages and commits all **modified tracked files**.

> **Note:** Newly created files are not included. They must first be added using `git add`.

---

## Key Points

- Saves staged changes in the Local Repository.
- Creates a new version (snapshot) of the project.
- Generates a unique Commit ID (SHA Hash).
- Stores the commit message.
- Updates the project history.
- HEAD automatically points to the latest commit.

---

## Summary

`git commit` saves the staged changes permanently in the Local Repository. It creates a new version of the project, generates a unique Commit ID, updates the project history, and moves the HEAD pointer to the latest commit.
