# git status

## What is git status?

`git status` is used to display the current state of a Git repository. It shows the status of files in the Working Directory and the Staging Area.

---

## Why Do We Use git status?

Before staging, committing, or pushing changes, developers use `git status` to understand the current state of the repository.

---

## Syntax

```bash
git status
```

---

## Example

```bash
git status
```

Possible Output:

```text
On branch main

Changes not staged for commit:
    modified: Main.java

no changes added to commit
```

Another Example:

```text
On branch main

Changes to be committed:
    new file: Student.java
```

Another Example:

```text
On branch main

nothing to commit, working tree clean
```

---

## What Does git status Show?

- Current branch.
- Untracked files.
- Modified files.
- Staged files.
- Whether the Working Tree is clean or not.

---

## Common Status Messages

### Untracked Files

The file is created but Git is not tracking it yet.

---

### Changes Not Staged for Commit

The file has been modified, but it has not been added to the Staging Area.

---

### Changes to Be Committed

The file is in the Staging Area and is ready to be committed.

---

### Working Tree Clean

There are no pending changes. Everything is up to date.

---

## Key Points

- Does not modify any files.
- Used to check the current repository status.
- Helps identify which files need to be staged or committed.
- One of the most frequently used Git commands.

---

## Summary

`git status` displays the current state of the repository by showing tracked, untracked, modified, and staged files. It helps developers understand what action should be taken next.