# Commands

## 🔧 Setup (First Time Only)
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

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
git commit -m "Message" # Commit with a message
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
git branch new-feature      # Create new branch
git checkout new-feature    # Switch to branch
git checkout -b bugfix      # Create + switch in one command
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

## 💡 GitHub Shortcuts (Web)

| Task                     | GitHub Web Shortcut                                 |
|--------------------------|-----------------------------------------------------|
| Open a repo              | `https://github.com/username/repo`                 |
| Fork a repo              | Click **"Fork"** on the top right                  |
| Create pull request (PR) | Click **"Pull requests > New pull request"**       |
| View Issues              | Click **"Issues"** tab in a repo                   |
