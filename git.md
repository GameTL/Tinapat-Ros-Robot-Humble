# Initialize and Clone Repositories

git init: Initialize a new repository in the current directory.
git clone <repo_URL>: Clone a repository from a URL.

# Basic Workflow
git status: Show the status of changes in the working directory.
git add <file/folder>: Add files or changes to the staging area.
git commit -m "message": Commit the staged changes along with a message.

# Branching and Merging
git branch: List all branches.
git branch <branch_name>: Create a new branch.
git checkout <branch_name>: Switch to another branch.
git merge <branch_name>: Merge another branch into the current branch.

# Remote Repositories
git remote add <remote_name> <remote_URL>: Add a remote repository.
git push <remote_name> <branch_name>: Push changes to a remote repository.
git pull <remote_name> <branch_name>: Pull changes from a remote repository.

# Misc Commands
git log: Show commit history.
git revert <commit_hash>: Revert a specific commit.
git reset: Reset the current HEAD to a specific state.