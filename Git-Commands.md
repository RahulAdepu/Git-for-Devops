# Git Commands

## Repository Initialization
- `git init`: Initializes a new Git repository in the current directory.
  
## Staging and Committing Changes
- `git add .`: Stages all changes in the current directory.
- `git commit -m "message"`: Commits staged changes with a message.
- `git status`: Checks the status of the working directory and staging area.

## Branch Management
- `git checkout -b devops`: Creates and switches to a new branch called "devops."
- `git switch devops`: Switches to the "devops" branch.
- `git checkout devops` / `git checkout master`: Switches between branches.
- `git branch`: Lists all branches in the repository.

## Pushing and Logging
- `git push .` / `git push -u origin main HEAD:master`: Pushes local commits to a remote repository.
- `git log`: Displays commit history.
- `git history`: (Likely an alias for viewing history, often set as `git log`).

## Global Configuration
- `git config --global user.name "Your Name"`: Sets the global username for commits.
- `git config --global user.email "your.email@example.com"`: Sets the global email for commits.
- `git config --global core.editor "vim"`: Sets Vim as the default editor for Git.
- `git config --global alias.co checkout`: Creates a shortcut alias `co` for the `git checkout` command.

## Viewing Configuration
- `git config --list --global`: Lists all global Git configurations.
- `git config user.name`: Shows the configured Git username.
- `git config user.email`: Shows the configured Git email.
