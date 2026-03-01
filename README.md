# 🚀 Git & GitHub Guide

A beginner-friendly guide to **Git**, **GitHub**, and different ways to manage repositories and collaborate on projects.

---

## 📌 What is Git?

**Git** is a **Version Control System** used to:

* Track changes in code
* Maintain project history
* Collaborate with multiple developers

👉 A project folder in Git is called a **Repository (Repo)**.

---

## 🖥️ Git Bash

Git Bash is a terminal used to execute Git commands manually.

### 🔹 Basic Concepts

* **Repository** → Project folder
* **README File** → Project overview
* **Add + Commit** → Saving a snapshot of changes

---

### ⚙️ Basic Commands

| Command         | Description            |
| --------------- | ---------------------- |
| `git --version` | Check Git installation |
| `clear`         | Clear terminal         |
| `pwd`           | Show working directory |
| `ls`            | List files             |
| `ls -a`         | Show hidden files      |
| `cd folder`     | Enter folder           |
| `cd ..`         | Go back                |

---

### 👤 Git Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list
```

---

### 📁 Repository Setup

```bash
git init
git clone <repo-link>
mkdir FolderName
```

---

### 📊 File States in Git

1. **Untracked** → New files
2. **Modified** → Edited files
3. **Staged** → Ready to commit
4. **Unmodified** → No changes

---

### ✅ Tracking Changes

```bash
git status
git add <file-name>
git commit -m "message"
```

---

### ☁️ Connecting to GitHub

```bash
git remote add origin <repo-link>
git remote -v
git branch -M main
git push -u origin main
```

* **origin** → Remote repository name
* **main** → Branch name

---

### 🌿 Branching

```bash
git branch
git checkout <branch-name>
git checkout -b <new-branch>
git branch -d <branch-name>
```

👉 Branch = Safe copy to test new features.

---

### 🔀 Merging Code

```bash
git diff main
git merge <branch-name>
git pull origin main
```

**Merge Conflict Solutions**

* Accept first change
* Accept second change
* Accept both changes

---

### ↩️ Undoing Changes

#### Before Commit

```bash
git reset <file>
git reset
```

#### Undo Last Commit

```bash
git reset HEAD~1
```

#### Undo Multiple Commits

```bash
git reset <commit-hash>
```

#### Force Reset

```bash
git reset --hard <commit-hash>
```

---

### 📜 View History

```bash
git log
```

Press `q` to exit log view.

---

### 🍴 Fork

**Fork** creates a personal copy of someone else's repository.

---

## 🖱️ GitHub Desktop

GUI application for Git operations without commands.

### Key Features

* **Branch** → Work safely on new features
* **Push** → Upload local changes
* **Pull** → Download latest updates
* **Merge** → Combine branches

---

## 💻 VS Code Git Integration

Visual Studio Code provides built-in Git support:

* Stage files
* Commit changes
* Push & Pull repositories
* Manage branches directly from editor

---

## 🌐 Uploading via GitHub Website

You can upload files manually using your browser without installing Git.

---

## 🧭 Recommended Learning Path

1️⃣ Start with **GitHub Desktop** (build confidence)
2️⃣ Use **VS Code Git Integration** (daily workflow)
3️⃣ Learn **Git Bash** (industry-level skill)

---

## ⭐ Why Learn Git?

* Industry standard tool
* Essential for developers
* Enables teamwork & project tracking
* Safe experimentation using branches

---

✨ Happy Coding!

