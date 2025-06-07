
# 📘 Git & GitHub Commands Cheat Sheet

A helpful collection of essential Git and GitHub commands with explanations — perfect for beginners and daily use.

---

## 🛠️ Basic Git Configuration

```bash
git config --global user.name "Your Name"         # Set your Git username
git config --global user.email "you@example.com"  # Set your Git email
git config --global init.defaultBranch main       # Use 'main' as default branch
```

---

## 📁 Repository Setup

```bash
git init                                # Initialize a new local Git repo
git clone <repo_url>                    # Clone an existing GitHub repo
```

---

## 📄 Staging and Committing Changes

```bash
git status                              # Show changed and untracked files
git add .                               # Stage all changes
git add <file>                          # Stage a specific file
git commit -m "Your message"            # Commit changes with a message
git log                                 # Show commit history
```

---

## 🔀 Branching and Merging

```bash
git branch                              # List all branches
git branch <branch-name>                # Create a new branch
git checkout <branch-name>              # Switch to a branch
git checkout -b <branch-name>           # Create and switch to a new branch
git merge <branch-name>                 # Merge a branch into the current one
git branch -m old-name new-name         # Rename a branch
```

---

## 🌍 Remote Repositories (GitHub)

```bash
git remote add origin <repo_url>        # Add a remote GitHub repo
git remote -v                           # View remote connections
git push -u origin main                 # Push to GitHub and set upstream
git pull origin main                    # Pull latest changes from GitHub
```

---

## 🚫 Removing Files or Repos

```bash
git rm --cached <file>                  # Untrack a file but keep it locally
git rm <file>                           # Remove a file from repo and local
```

---

## 📦 Handling Submodules & Embedded Repositories

```bash
git submodule add <url> <folder>        # Add a Git submodule
git rm --cached <folder>                # Remove an embedded repo from tracking
```

---

## 💥 Undoing Changes

```bash
git reset HEAD~                         # Undo last commit (keep changes)
git reset --hard HEAD~                  # Delete last commit and changes
git revert <commit_hash>                # Revert a specific commit
```

---

## 🧹 Clean Workspace

```bash
git clean -fd                           # Remove untracked files and folders
git stash                               # Save local changes temporarily
git stash pop                           # Reapply stashed changes
```

---

## 🧭 Change Default Branch Name

```bash
git branch -m master main               # Rename master to main locally
git push -u origin main                 # Push new main branch
git push origin --delete master         # Delete old master branch on GitHub
```

---

## 🗑️ Delete a GitHub Repository

> ✅ **Only via GitHub website**  
Go to: **Settings → Danger Zone → Delete this repository**

---

## 📋 Notes

- CRLF warnings are normal on Windows systems.
- Embedded repo warnings mean a Git repo exists inside another. Remove using:
  ```bash
  git rm --cached <folder>
  ```

---

## 🧠 Helpful Tips

- Always pull before pushing.
- Write meaningful commit messages.
- Use `.gitignore` to skip files like `.env`, `.venv`, etc.

---

## 👨‍💻 Created by

Malik Saad Khawar 
*Learning Git, GitHub, and Open Source with passion!*
