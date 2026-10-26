<div align="center">

Git & GitHub Operations Assignment
A hands-on practice repository for learning Git version control and GitHub workflows





</div>

📌 About the Project

This repository contains practical exercises for understanding Git and GitHub. It covers local and remote repository management, staging, commits, branching, merging, pull requests, reset and revert operations, conflict resolution, and forking.

📚 Table of Contents

* Objectives
* Assignment Topics
* Commands Practiced
* Screenshots
* Repository and Pull Request Links

🎯 Objectives

* Understand the basic Git workflow.
* Manage local and remote repositories.
* Practice staging, unstaging, committing, and pushing changes.
* Work with branches and pull requests.
* Understand reset, revert, and merge-conflict resolution.
* Track repository changes using Git inspection commands.

🧩 Assignment Topics

1 Local Repository Setup
-> Initialize a repository, commit initial.txt, and practice staging and unstaging temp.txt.

2 Remote Repository Operations
-> Connect to GitHub, push and pull changes, and selectively unstage files.

3 Branching and Pull Requests
-> Create and work with the g1 branch, then raise and merge a pull request.

4 Local Git Operations
-> Practice fetch, merge, soft/mixed/hard reset, interactive staging, and branch comparison.

5 Branch Merging and Cleanup
-> Merge b3, b2, and b1; resolve a merge conflict; delete branches.

6 Fork Operations
-> Fork and clone a repository, push a change, and create a pull request.

7 Additional Operations
->Practice rm and revert, and document changes with git status and git diff.

💻 Commands Practiced

# Repository setup and commits
git init
git add
git commit
git status

# Staging and unstaging
git restore --staged temp.txt
git reset HEAD temp.txt
git reset --mixed HEAD
git add -p

# Remote operations
git remote add origin <repository-url>
git fetch origin
git pull origin main
git push origin main

# Branching and merging
git checkout g1
git merge
git diff main g1
git branch -d b1

# Reset and inspection
git reset --soft HEAD~1
git reset --hard HEAD~1
git diff --staged
git ls-files
git log

# Revert and remote branch cleanup
git revert <commit-id>
git push origin --delete g1

🔗 Repository and Pull Request Links
GitHub Repository: 




<div align="center">

Made as part of Git & GitHub practice

</div>
