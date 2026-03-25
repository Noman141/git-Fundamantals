# git-Fundamantals
# 🚀 Git Fundamentals Guide

A beginner-friendly Git guide 
---

## 📑 Table of Contents

- [Introduction](#introduction)
- [Basic Commands](#basic-commands)
- [Branching](#branching)
- [Merging](#merging)

---

## Introduction

Git is a version control system used to track changes in code.

---

## Basic Commands

# How to Create a Repository?
A repository (repo) is where your project lives. You can create it using a GUI or command line.

# Method 1: Creating from GUI (Easiest)
```Creating on GitHub:
GitHub:
Log in to GitHub (https://github.com)
Click the "+" icon in the top-right corner
Select "New repository"
Fill in the details:
Repository name
Description (optional)
Public or Private
Initialize with README (optional)
Add .gitignore (optional)
Choose a license (optional)
Click "Create repository"```
# GitLab:
```Log in to GitLab (https://gitlab.com)
Click "New project"
Choose "Create blank project"
Fill in the details:
Project name
Project URL
Visibility level (Private, Internal, Public)
Initialize with README (optional)
Click "Create project"```

# Creating from Command Line
Initialize a New Repository:
# Create a new directory
mkdir my-project
cd my-project

# Initialize Git repository
git init

# Verify initialization
ls -la  # You should see a .git directory
Create Your First Commit:
# Create a README file
echo "# My Project" > README.md

# Check status
git status

# Add file to staging area
git add README.md

# Commit the file
git commit -m "Initial commit: Add README"

# View commit history
git log
Connect to Remote Repository:
# Add remote origin (replace with your repository URL)
git remote add origin https://github.com/username/repository.git

# Verify remote
git remote -v

# Push to remote
git push -u origin main

# Rewright README.md file & Push
ভাল প্রশ্ন 👍 এখন আপনি Git-এর real workflow-এ ঢুকেছেন 🔥

আপনি README.md edit করেছেন → এখন সেটা GitHub-এ push করতে হবে।

---

# 🚀 Step-by-Step Push করার নিয়ম

## ✅ Step 1: Check status

```bash
git status
```

👉 এটা দেখাবে কোন file change হয়েছে (README.md)

---

## ✅ Step 2: Add file

```bash
git add README.md
```

👉 অথবা সব add করতে চাইলে:

```bash
git add .
```

---

## ✅ Step 3: Commit করুন

```bash
git commit -m "Update README with documentation"
```

---

## ✅ Step 4: Push করুন (সবচেয়ে গুরুত্বপূর্ণ)

```bash
git push origin main
```


