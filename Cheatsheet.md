# Git Commands Cheat Sheet

This cheat sheet provides a quick overview of basic Git commands useful for everyday use in your projects.

## Configuration

- **Set your username:** `git config --global user.name "Your Name"`
- **Set your email address:** `git config --global user.email "your_email@example.com"`

## Starting and Cloning Repositories

- **Initialize a new Git repository:** `git init`
- **Clone an existing repository:** `git clone <repository-url>`

## Basic Commands

- **View the status of your files:** `git status`
- **Add files to staging:** `git add <file>` or `git add .` (to add all files)
- **Commit changes:** `git commit -m "Commit message"`
- **Push changes to remote repository:** `git push`
- **Pull latest changes from remote repository:** `git pull`

## Branching and Merging

- **List all branches:** `git branch`
- **Create a new branch:** `git branch <branch-name>`
- **Switch to a branch:** `git checkout <branch-name>`
- **Create and switch to a new branch:** `git checkout -b <branch-name>`
- **Merge a branch into the current branch:** `git merge <branch-name>`
- **Delete a branch:** `git branch -d <branch-name>`

## Viewing Changes

- **View changes in the working directory:** `git diff`
- **View the commit history:** `git log`
- **View a summary of changes:** `git log --oneline`

## Undoing Changes

- **Undo changes in the working directory:** `git checkout -- <file>`
- **Remove staged changes:** `git reset HEAD <file>`
- **Revert a commit by creating a new commit with opposite changes:** `git revert <commit-hash>`
- **Reset your branch to a previous commit (dangerous):** `git reset --hard <commit-hash>`

Remember, Git commands can have additional options and flags to perform more specific tasks. Refer to the Git documentation for more detailed information.