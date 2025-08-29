# 📘 Git Commands with Descriptions

## Setup
- `git config --global user.name "Your Name"` -> Sets your Git username globally.
- `git config --global user.email "your@email.com"` -> Sets your email globally.

## Repository Initialization
- `git init`  ->  Initialize a new Git repository.
- `git clone <repo-url>`  ->  Clone an existing repository.

## Staging & Committing
- `git status`  -> Show modified files in the working directory.
- `git add <file>`  -> Stage changes for commit.
- `git commit -m "message"`  -> Commit staged changes with a message.

## Branching
- `git branch`  -> List all branches.
- `git checkout -b <branch>` ->  Create and switch to a new branch.
- `git merge <branch>`  ->  Merge branch into the current one.

## Remote Operations
- `git remote add origin <url>` ->  Add a remote repository.
- `git push origin main`  -> Push commits to remote main branch.
- `git pull origin main` -> Fetch and merge changes from remote.

## Others
- `git log`  
  Show commit history.
- `git diff`  
  Show changes between commits or working directory.
- `git reset --hard <commit>`  
  Reset to a specific commit.
