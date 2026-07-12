# Git Workflow

## What is Git Workflow?

Git Workflow is the process that describes how changes move through different stages before they are stored on GitHub.

---

## Workflow

```text
Working Directory
        │
    git add
        ▼
Staging Area
        │
 git commit
        ▼
Local Repository
        │
  git push
        ▼
Remote Repository (GitHub)
```

---

## Workflow Explanation

### Step 1 - Working Directory

Create or modify project files.

### Step 2 - Staging Area

Use `git add` to prepare selected changes for the next commit.

### Step 3 - Local Repository

Use `git commit` to save the staged changes permanently in the Local Repository.

### Step 4 - Remote Repository

Use `git push` to upload local commits to GitHub.

---

## Key Points

- Every change starts in the Working Directory.
- `git add` moves changes to the Staging Area.
- `git commit` saves changes in the Local Repository.
- `git push` uploads commits to the Remote Repository.

---

## Summary

Git Workflow helps developers manage project changes in an organized way by moving changes through four stages: Working Directory, Staging Area, Local Repository, and Remote Repository.