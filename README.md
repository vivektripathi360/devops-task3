# Redmi Setup for DevOps Project (Task 4)

This file explains how to **access, manage, and update your DevOps project** on a Redmi phone according to Task 4 instructions.

---

## Task Objective
Manage a DevOps project using **Git best practices**.

## Tools
- Git
- GitHub

## Deliverables
- Project repository with proper commits and branching.
- Documentation of all tasks using Markdown (`README.md`, `redmi.md`).
- Proper `.gitignore` and Git tags.

---

## Step-by-Step Guide for Redmi

### 1. Accessing GitHub
- Open the **GitHub app** or **browser** (Chrome) on your Redmi.
- Log in with your GitHub account.
- Open the repo: `devops-task4`.

### 2. Viewing Files
- You can view `.md` (documentation) and code files directly.
- Browser or GitHub app provides read-only access.

### 3. Editing Files
- In GitHub app:
  1. Open the file you want to edit.
  2. Click the **edit icon**.
  3. Make your changes.
  4. Commit the changes → select the branch (`dev` or `feature`).
- Changes are automatically updated in the GitHub repo.

### 4. Optional: Using Git Commands on Redmi (Advanced)
1. Install **Termux** from Play Store.
2. Install Git:
   ```bash
   pkg install git
Clone the repo:

git clone https://github.com/username/devops-task3.git

Enter the repo folder and run:

git add .
git commit -m "Changes from Redmi"
git push origin dev

Create and switch between branches:

git branch dev
git branch feature
git checkout dev

Add Git tags to mark versions:

git tag v1.0
git push origin v1.0


