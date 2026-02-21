

# 🤝 Contributing to Kalvium Squad 138 Portfolio

Welcome 🚀
If this is your **first open-source contribution**, don’t worry.
This guide explains everything step-by-step — from cloning the repository to creating a Pull Request — with visual diagrams.

Follow this carefully and you won’t need anyone’s help.

---

# 📚 Before You Start

Make sure you have:

* ✅ Git installed → [https://git-scm.com/](https://git-scm.com/)
* ✅ VS Code installed → [https://code.visualstudio.com/](https://code.visualstudio.com/)
* ✅ GitHub account

Check Git installation:

```bash
git --version
```

If it shows a version number → you're ready.

---

# 🔀 How Open Source Contribution Works (Visual Overview)

## 🧭 Overall Contribution Flow

```
            ┌─────────────────────┐
            │  Original Repository │
            │   (Main Project)     │
            └──────────┬───────────┘
                       │
                       ▼
            ┌─────────────────────┐
            │      Fork Repo       │
            │  (Your GitHub Copy)  │
            └──────────┬───────────┘
                       │
                       ▼
            ┌─────────────────────┐
            │    Clone to Local    │
            │    (Your Computer)   │
            └──────────┬───────────┘
                       │
                       ▼
            ┌─────────────────────┐
            │   Create New Branch  │
            │  (Feature Branch)    │
            └──────────┬───────────┘
                       │
                       ▼
            ┌─────────────────────┐
            │   Make Changes       │
            │   Test Locally       │
            └──────────┬───────────┘
                       │
                       ▼
            ┌─────────────────────┐
            │     Commit Changes   │
            └──────────┬───────────┘
                       │
                       ▼
            ┌─────────────────────┐
            │      Push Branch     │
            └──────────┬───────────┘
                       │
                       ▼
            ┌─────────────────────┐
            │   Create Pull Request│
            └─────────────────────┘
```

---

# 🌿 Branching Strategy (Very Important)

Never work directly on `main`.

```
main  ────────────────────────────────●────────●────────●
                                       │
                                       ▼
feature/navbar-fix  ───────●──────●──────●
                             (your commits)
```

* `main` → Stable code
* `feature/...` → Your work branch
* After approval → Merged into `main`

---

# 🪜 Step-by-Step Contribution Guide

---

## 🔹 Step 1 — Fork the Repository

1. Go to the original GitHub repo.
2. Click **Fork** (top-right).
3. This creates your personal copy.

You will work in your fork.

---

## 🔹 Step 2 — Clone Repository to Local Machine

Open terminal:

```bash
git clone https://github.com/YOUR-USERNAME/Kalvium_squad138_portfolio.git
```

Move into project:

```bash
cd Kalvium_squad138_portfolio
```

---

## 🔹 Step 3 — Create a New Branch

Check current branch:

```bash
git branch
```

Create a new branch:

```bash
git checkout -b your-name-feature
```

Example:

```bash
git checkout -b manoj-navbar-fix
```

Now you're safe to work.

---

## 🔹 Step 4 — Make Changes

Open in VS Code:

```bash
code .
```

You can:

* Improve UI
* Fix responsiveness
* Add animation
* Fix spacing
* Improve accessibility
* Fix broken links

---

## 🔹 Step 5 — Test Locally

Open `index.html` in browser
OR use Live Server extension.

Always check:

* Desktop view
* Mobile view
* Console errors (Press F12 → Console)

---

# 🔄 Always Update Before Pushing

## Visual Explanation

```
main (remote)  ───────●──────●──────●

git pull origin main

feature-branch  ───●──●──●
                    │
git merge main      ▼
Now branch is updated
```

---

## Commands

Switch to main:

```bash
git checkout main
```

Pull latest:

```bash
git pull origin main
```

Go back to your branch:

```bash
git checkout your-branch-name
```

Merge main:

```bash
git merge main
```

---

# 🧨 If There Is a Merge Conflict

You will see something like:

```
<<<<<<< HEAD
Your Code
=======
Main Code
>>>>>>> main
```

Fix manually → remove markers → keep correct code.

Then:

```bash
git add .
git commit -m "Resolved merge conflict"
```

---

# 📦 Stage & Commit Changes

Check changes:

```bash
git status
```

Add files:

```bash
git add .
```

Commit:

```bash
git commit -m "Added navbar hover animation"
```

Use meaningful messages.

---

# 🚀 Push to GitHub

```bash
git push origin your-branch-name
```

---

# 🔁 Create Pull Request (PR)

1. Go to your fork on GitHub.
2. Click **Compare & Pull Request**
3. Add proper title.
4. Explain your changes.
5. Click **Create Pull Request**

Done 🎉

---

# 📌 Complete Beginner Git Command Flow

```
Fork
  ↓
Clone
  ↓
Create Branch
  ↓
Make Changes
  ↓
Test Locally
  ↓
git add .
  ↓
git commit
  ↓
git checkout main
  ↓
git pull origin main
  ↓
git checkout branch-name
  ↓
git merge main
  ↓
git push origin branch-name
  ↓
Create Pull Request
```

---

# ❌ Common Mistakes

Wrong way:

```
main ───●──●──●──● (everyone pushes directly)
```

Correct way:

```
main ───●────●────●
          │
          ├── feature-1
          ├── feature-2
          ├── feature-3
```

---

# 📛 Contribution Rules

### ❌ Do NOT:

* Push directly to `main`
* Delete others’ work
* Commit unnecessary files
* Upload node_modules

### ✅ Do:

* Write clean code
* Test before pushing
* Follow existing structure
* Use meaningful commit messages

---

# 🧠 Helpful Commands

Check branch:

```bash
git branch
```

See changes:

```bash
git diff
```

Delete local branch:

```bash
git branch -d branch-name
```

Delete remote branch:

```bash
git push origin --delete branch-name
```

---

# 🏁 You Just Contributed to Open Source

If you followed all steps:

You have successfully:

* Forked a repository
* Created a feature branch
* Merged updates
* Resolved conflicts
* Created a Pull Request

That is real open-source contribution.

---


