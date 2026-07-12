# git push

## What is git push?

`git push` is used to upload the committed changes from the **Local Repository** to the **Remote Repository (GitHub)**.

---

## Why Do We Use git push?

After creating a commit, the changes are available only in the Local Repository. The `git push` command is used to upload those commits to GitHub, making them available to other developers.

---

## Syntax

```bash
git push <remote-name> <branch-name>
```

Example:

```bash
git push origin main
```

---

## What Happens After Running git push?

- Commits are uploaded from the Local Repository to GitHub.
- The Remote Repository is updated.
- Other developers can access the latest changes by pulling the repository.

---

## Understanding the Command

### origin

`origin` is the default name (alias) of the remote repository.

Example:

```text
origin
   │
   ▼
https://github.com/username/Git-Essentials.git
```

---

### main

`main` is the branch where the commits are pushed.

---

## Common Usage

### Push to the main branch

```bash
git push origin main
```

---

### First Push

```bash
git push -u origin main
```

The `-u` option sets the upstream branch. After this, you can simply use:

```bash
git push
```

---

### Push to Another Branch

```bash
git push origin feature-login
```

Pushes commits to the `feature-login` branch.

---

## Key Points

- Uploads commits to the Remote Repository.
- Pushes changes from the Local Repository to GitHub.
- `origin` represents the remote repository.
- `main` represents the branch name.
- A commit must exist before using `git push`.

---

## Summary

`git push` uploads committed changes from the Local Repository to the Remote Repository. It is commonly used to share code, back up projects, and collaborate with other developers.