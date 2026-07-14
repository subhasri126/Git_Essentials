# git pull

## What is git pull?

`git pull` is used to download the latest changes from the **Remote Repository** and update the **Local Repository** and **Working Directory**.

---

## Why Do We Use git pull?

The `git pull` command is used to keep the local project up to date with the latest changes available in the Remote Repository. It is commonly used when multiple developers work on the same project.

---

## Syntax

```bash
git pull <remote-name> <branch-name>
```

Example:

```bash
git pull origin main
```

---

## What Happens After Running git pull?

- Downloads the latest changes from the Remote Repository.
- Updates the Local Repository.
- Updates the Working Directory with the latest project files.
- Keeps the local project synchronized with the Remote Repository.

---

## Common Usage

### Pull the Latest Changes

```bash
git pull origin main
```

Downloads and updates the latest changes from the `main` branch.

---

### Pull from the Default Remote

```bash
git pull
```

Pulls changes from the configured default remote and branch.

---

## git pull vs git clone

| git pull | git clone |
|----------|-----------|
| Updates an existing local repository | Copies an existing remote repository for the first time |
| Used after cloning | Used only once when getting the repository |
| Downloads only the latest changes | Downloads the complete repository |

---

## Key Points

- Downloads the latest changes from the Remote Repository.
- Updates both the Local Repository and the Working Directory.
- Used to synchronize the local project with GitHub.
- No need to use `git clone` again after the repository has been cloned.

---

## Summary

`git pull` is used to download the latest changes from the Remote Repository and update the Local Repository and Working Directory. It helps developers keep their local project synchronized with the latest version available on GitHub.