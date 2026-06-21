# git-github-cheat-sheet
A comprehensive Git and GitHub cheat sheet with commonly used commands and examples.
# Git & GitHub Cheat Sheet

## Configure Git
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

## Initialize Repository
```bash
git init
```

## Check Status
```bash
git status
```

## Add Files
```bash
git add .
git add filename
```

## Commit Changes
```bash
git commit -m "Initial commit"
```

## Connect Remote Repository
```bash
git remote add origin <repository-url>
```

## Push Changes
```bash
git push origin main
```

## Pull Latest Changes
```bash
git pull origin main
```

## Clone Repository
```bash
git clone <repository-url>
```

Branching Commands

Create a New Branch

git branch feature-branch

Switch to a Branch

git checkout feature-branch

Or using the newer command:

git switch feature-branch

Create and Switch to a New Branch

git checkout -b feature-branch

Or:

git switch -c feature-branch

List All Branches

git branch

Delete a Branch

git branch -d feature-branch

Rename the Current Branch

git branch -m new-branch-name
