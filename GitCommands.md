# 📘 Git Commands with Descriptions

## 🔹 Setup
- `git config --global user.name "Your Name"` -> Sets your Git username globally.
- `git config --global user.email "your@email.com"` -> Sets your email globally.
- `git config --list`  →  View all configs.

## 🔹 Repository Initialization
- `git init`  ->  Initialize a new Git repository.
- `git clone <repo-url>`  ->  Clone an existing repository.

## 🔹 Staging & Committing
- `git status`  -> Show modified files in the working directory.
- `git add <file>`  -> Stage changes for commit.
- `git add .` → Stage all files.
- `git commit -m "message"`  -> Commit staged changes with a message.
- `git commit -am "message"` → Add & commit tracked files.

## 🔹 Branching
- `git branch`  -> List all branches.
- `git branch <name>` → Create branch.
- `git checkout <branch>` → Switch branch.
- `git checkout -b <branch>` ->  Create and switch to a new branch.
- `git merge <branch>`  ->  Merge branch into the current one.
- `git branch -d <name>` → Delete branch.

## 🔹 Remote Operations
- `git remote -v` ->  Show remotes.
- `git remote add origin <url>` ->  Add a remote repository.
- `git push origin main`  -> Push commits to remote main branch.
- `git pull origin main` -> Fetch and merge changes from remote.
- `git push -u origin <branch>` → Push & set upstream.
- `git pull origin <branch>`→ Fetch + merge from remote.
- `git fetch` → Download objects but don’t merge.

## 🔹 Undoing Changes
- `git restore <file>` → Undo changes in working directory.
- `git reset <file>` → Unstage file.
- `git reset --hard <commit>` → Reset everything to a commit.
- `git revert <commit>` → Revert a commit (safe).

## 🔹 Tags
- `git tag`  →  List tags.
- `git tag <name>`  →  Create tag.
- `git push origin <tag>`  →  Push tag to remote

## 🔹 Viewing History
-`git log` → Show commit history.
-`git log--oneline` → Compact log view.
-`git diff` → Show unstaged changes.
- `git diff --staged` → Show staged changes.

## 🔹 Stash (Save Work Temporarily)
- `git stash` → Save uncommitted changes.
- `git stash list` → View stashes.
- `git stash pop` → Reapply last stash.

## 🔹 Collaboration
- `git fetch origin` → Get latest changes.
- `git pull origin main` → Update local main.
- `git push origin main` → Push changes to main.

## 🔹 Advanced
- `git cherry-pick <commit>` → Apply a specific commit.
- `git rebase <branch>` → Rebase commits on top of another branch.
- `git reflog` → View reference logs.
- `git bisect` → Find commit that introduced a bug.

## 🔹 Others
- `git log` ->  Show commit history.
- `git diff` ->  Show changes between commits or working directory.
- `git reset --hard <commit>` ->  Reset to a specific commit.
