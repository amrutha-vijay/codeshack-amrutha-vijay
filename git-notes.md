# Git Notes — Beginner's Handbook

## 1. git init
Initialises a new Git repository in the current folder.

Example:
`git init`

## 2. git clone
Copies an existing remote repository to your computer.

Example:
`git clone https://github.com/username/project.git`

## 3. git status
Shows the current branch and the state of your files.

Example:
`git status`

## 4. git add
Stages changes so they can be included in a commit.

Example:
`git add README.md`

## 5. git commit
Records staged changes with a descriptive message.

Example:
`git commit -m "Add project introduction"`

## 6. git log
Displays the commit history.

Example:
`git log --oneline`

## 7. git diff
Shows changes that have not been staged.

Example:
`git diff`

## 8. git push
Uploads local commits to a remote repository.

Example:
`git push -u origin feature/notes`

## 9. git pull
Fetches remote changes and integrates them into the current branch.

Example:
`git pull origin main`

## 10. git fetch
Downloads updates from a remote repository without integrating them into the current branch.

Example:
`git fetch origin`

## 11. git switch
Switches branches or creates a new branch.

Example:
`git switch -c feature/notes`

## 12. git merge
Integrates changes from one branch into another.

Example:
`git merge feature/notes`

## Key Takeaway
Git tracks changes in files, while GitHub hosts repositories online and helps developers collaborate.

## Feature Branch Workflow

Feature branches allow developers to work on changes separately from the main branch.

Example workflow:

1. Create a new branch:
   `git switch -c feature/my-change`

2. Check the current branch:
   `git branch --show-current`

3. Stage your changes:
   `git add .`

4. Commit your changes:
   `git commit -m "Describe the change"`

5. Push the branch to GitHub:
   `git push -u origin feature/my-change`

6. Open a pull request to propose merging the feature branch into `main`.

In a team repository, every member should work on their own branch and submit changes for review. Avoid committing directly to `main`.

