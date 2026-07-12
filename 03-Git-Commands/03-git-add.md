# git add

## What is git add?

`git add` is used to move changes from the **Working Directory** to the **Staging Area**. It prepares the selected changes for the next commit.

---

## Why Do We Use git add?

Before creating a commit, Git needs to know which changes should be included. The `git add` command is used to stage those changes.

---

## Syntax

```bash
git add <file-name>
```

or

```bash
git add .
```

---

## Common Usage

### 1. Stage a Specific File

Suppose your project contains:

```text
Calculator/
│
├── Main.java
├── Student.java
└── README.md
```

You modified only `Main.java`.

```bash
git add Main.java
```

Result:

- ✅ Main.java → Staging Area
- ❌ Student.java → Working Directory
- ❌ README.md → Working Directory

Only the selected file is staged.

---

### 2. Stage Multiple Files

Suppose you modified both `Main.java` and `Student.java`.

```bash
git add Main.java Student.java
```

Result:

- ✅ Main.java → Staging Area
- ✅ Student.java → Staging Area

Both files are staged together.

---

### 3. Stage All Files

Suppose you:

- Created `Login.java`
- Modified `Main.java`
- Modified `README.md`

Instead of adding each file separately, execute:

```bash
git add .
```

Result:

- ✅ Login.java
- ✅ Main.java
- ✅ README.md

All changes in the current directory are staged.

---

### 4. Stage All Changes in the Repository

Suppose you:

- Created `Login.java`
- Modified `Main.java`
- Deleted `Test.java`

Execute:

```bash
git add -A
```

Result:

- ✅ Login.java
- ✅ Main.java
- ✅ Test.java (Deletion is staged)

All new, modified, and deleted files are staged.

---

### 5. Stage Only Modified and Deleted Files

Suppose your project contains:

```text
Modified : Main.java
Deleted  : Test.java
Created  : Login.java
```

Execute:

```bash
git add -u
```

Result:

- ✅ Main.java
- ✅ Test.java
- ❌ Login.java

Only modified and deleted tracked files are staged. Newly created files are not staged.

---

### 6. Stage Files by Extension

Suppose your project contains:

```text
Main.java
Student.java
style.css
index.html
```

Execute:

```bash
git add *.java
```

Result:

- ✅ Main.java
- ✅ Student.java
- ❌ style.css
- ❌ index.html

Only Java files are staged.

---

## What Happens After Running git add?

- Git starts tracking the selected changes.
- Changes move from the Working Directory to the Staging Area.
- The changes become ready for the next commit.
- The changes are **not saved permanently** until `git commit` is executed.

---

## Key Points

- Moves changes from the Working Directory to the Staging Area.
- Prepares changes for the next commit.
- Only staged changes are committed.
- Does not save changes permanently.
- Supports staging a single file, multiple files, or all files.

---

## Summary

`git add` is used to prepare project changes for the next commit by moving them from the Working Directory to the Staging Area. It gives developers control over which changes should be included in a commit.
