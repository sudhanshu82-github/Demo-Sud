# Edu-Sud

GIT Commands to move code from VScode local to GITHUB
------------------------------------------------

Step 1: Create a new repo in GITHUB by login to Github.com portal

Step 2: Run below commands in the VS Code terminal in the repo which you want to push from VSCode into Github
git init
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git

To push the code into Github:
git status
git add .
git commit -m "Initial commit"
git branch -M main
git push OR git push -u origin main

Purpose of the git commands
-----------------------------
Git and GitHub aren't the same thing.

Git manages versions of your code locally.
GitHub hosts Git repositories online.
VS Code is where you're editing the code and can run Git commands.

That's why git commit doesn't automatically upload anything. git push is the command that sends your commits to GitHub.

| Command                     | Purpose                                     |
| --------------------------- | ------------------------------------------- |
| `git init`                  | Turn the folder into a Git repository       |
| `git status`                | See changed/untracked files                 |
| `git add .`                 | Stage your changes                          |
| `git commit -m "message"`   | Save a version/checkpoint                   |
| `git branch -M main`        | Name the main branch `main`                 |
| `git remote add origin URL` | Connect local Git to GitHub                 |
| `git remote -v`             | Check the GitHub connection                 |
| `git push -u origin main`   | First upload to GitHub                      |
| `git push`                  | Upload later commits                        |
| `git pull`                  | Download changes from the remote repository |
