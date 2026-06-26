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

# Git Branching Commands

## Create a New Branch

```bash
git branch feature-branch
```

## Switch to a Branch

```bash
git checkout feature-branch
```

## Switch Using the New Command

```bash
git switch feature-branch
```

## Create and Switch to a New Branch

```bash
git checkout -b feature-branch
```

## Create and Switch Using the New Command

```bash
git switch -c feature-branch
```

## List All Branches

```bash
git branch
```

## Delete a Branch

```bash
git branch -d feature-branch
```

## Rename the Current Branch

```bash
git branch -m new-branch-name
```

# Git Merge Commands

## Merge a Branch into Current Branch

```bash
git merge feature-branch
```

## Switch to Main Branch

```bash
git checkout main
```

## Merge Feature Branch into Main

```bash
git merge feature-branch
```

## Abort a Merge

```bash
git merge --abort
```

## View Merge History

```bash
git log --oneline --graph
```

## Fast Forward Merge

```bash
git merge --ff-only feature-branch
```

## Merge Without Fast Forward

```bash
git merge --no-ff feature-branch
```
# Git Reset Commands

## Soft Reset

```bash
git reset --soft HEAD~1
```

## Mixed Reset

```bash
git reset HEAD~1
```

## Hard Reset

```bash
git reset --hard HEAD~1
```

## Reset a Specific File

```bash
git reset filename
```

## Unstage All Changes

```bash
git reset
```

## Reset to a Specific Commit

```bash
git reset --hard <commit-hash>
```

## View Commit History

```bash
git log --oneline
```
# Git Restore Commands

## Restore a Modified File

```bash
git restore filename
```

## Restore All Modified Files

```bash
git restore .
```

## Unstage a File

```bash
git restore --staged filename
```

## Unstage All Files

```bash
git restore --staged .
```

## Restore a File from a Specific Commit

```bash
git restore --source <commit-hash> filename
```

## Restore Both Staged and Working Directory

```bash
git restore --source HEAD --staged --worktree filename
```

## Check Repository Status

```bash
git status
```
