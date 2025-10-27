# Git Reference Cheat Sheet

**Name:** Isaac Stanek  
**School:** Oklahoma Wesleyan University

## Purpose
This file is a personal cheat sheet for Git commands that I will use for version control in projects.

## Common Git Commands

### Setup & Configuration
- `git config --global user.name "Your Name"`
- `git config --global user.email "you@example.com"`

### Repository Commands
- `git init` — Initialize a new repository
- `git clone <repo_url>` — Clone a remote repository

### Staging & Committing
- `git add <file>` — Stage a file for commit
- `git add .` — Stage all changes
- `git commit -m "commit message"` — Commit staged changes

### Branching & Merging
- `git branch` — List branches
- `git branch <branch_name>` — Create a new branch
- `git checkout <branch_name>` — Switch to a branch
- `git merge <branch_name>` — Merge a branch into current branch

### Updating & Publishing
- `git pull` — Fetch and merge changes from remote
- `git push` — Push local changes to remote

### Inspecting Changes
- `git status` — Show staged and unstaged changes
- `git log` — Show commit history
- `git diff` — Show differences between commits or working directory
