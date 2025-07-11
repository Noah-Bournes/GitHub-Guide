# Commands

## 📥 Clone a Repository
```bash
git clone https://github.com/username/repo.git
```

## 🔄 Check Repo Status
```bash
git status          # Show current changes
git log             # Show commit history
```

## ✍️ Making Changes
```bash
git add filename        # Stage one file
git add .               # Stage all changes
git add --all           # Stage all changes
git commit -m "Message" # Commit with a message
git commit -a -m "message" # Stage all + Commit with a message
```

## ⬆️ Push to GitHub
```bash
git push origin main    # Push to the main branch
```

## ⬇️ Pull Latest Changes
```bash
git pull origin main    # Update local repo with latest remote changes
```

## 🌿 Branching
```bash
ls                              # List files in directory
git branch -m old-name new-name # Change name
git branch                      # List branches
git branch new-feature          # Create new branch
git checkout new-feature        # Switch to branch
git checkout -b bugfix          # Create + switch in one command
```

## 🔀 Merge Branches
```bash
git checkout main           # Go to main
git merge new-feature       # Merge new-feature into main
```

## 🧹 Undo / Fix Stuff
```bash
git restore filename        # Undo changes to a file
git reset HEAD filename     # Unstage a file
git reset --hard HEAD       # Revert all local changes
```

## Local > GitHub
```bash
mkdir new-cyber-repo
cd new-cyber-repo
git init                             # Start a new local repo
echo "# Cyber Notes" > README.md
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/new-cyber-repo.git
git push -u origin main
```

## Extra Commands
```bash
git diff                 # View unstaged changes
git diff --staged        # View staged changes

git stash                # Save uncommitted changes for later
git stash pop            # Reapply stashed changes

git commit --amend       # Modify the most recent commit

git log --oneline        # Compact view of commit history
git log --graph --all    # Visualize branch and merge history
```

## 💡 GitHub Shortcuts (Web)

| Task                     | GitHub Web Shortcut                                 |
|--------------------------|-----------------------------------------------------|
| Open a repo              | `https://github.com/username/repo`                 |
| Fork a repo              | Click **"Fork"** on the top right                  |
| Create pull request (PR) | Click **"Pull requests > New pull request"**       |
| View Issues              | Click **"Issues"** tab in a repo                   |
