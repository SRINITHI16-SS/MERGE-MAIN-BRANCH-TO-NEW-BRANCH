Create a New Branch & Merge main Branch

This guide explains how to create a new Git branch and merge the main branch into it using simple Git commands.

📌 Prerequisites

Git installed on your system

A Git repository with a main branch

Basic knowledge of terminal/command prompt

🚀 Step 1: Check Current Branch

First, verify which branch you are currently on.

git branch


The active branch will be highlighted with *.

🌱 Step 2: Create a New Branch

Create a new branch (example: feature-branch):

git branch feature-branch

🔄 Step 3: Switch to the New Branch

Move to the newly created branch:

git checkout feature-branch


👉 Shortcut (create + switch in one command):

git checkout -b feature-branch

🔀 Step 4: Merge main Branch into New Branch

First, make sure your main branch is up to date:

git checkout main
git pull origin main


Now switch back to your new branch:

git checkout feature-branch


Merge main into it:

git merge main

⚠️ Step 5: Resolve Conflicts (If Any)

If Git reports conflicts:

Open the conflicted files

Fix the conflicts manually

Save the files

Add and commit the changes

git add .
git commit -m "Resolved merge conflicts"

☁️ Step 6: Push the New Branch to GitHub

Upload the new branch to the remote repository:

git push origin feature-branch

✅ Result

A new branch is created

main branch changes are merged successfully

New branch is available on GitHub
SRINITHI B
srinithib@gmail.com
