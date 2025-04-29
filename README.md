# Git Practice
    Intro repository to become familiar with github.
---
### VS Code Keyboard shortcuts
- **Ctrl + `** : toggles the terminal.
- **Ctrl + w** : closes the current editor tab.
- **Ctrl + Shift + t** : reopens the most recently closed tab.
- **Ctrl + g** : opens dialog to go to specific line, column.
---
### Basic commands.
- Create a branch: `git checkout -b "new-branch-name"`
- Checkout existing branch: `git checkout "branch-name"`
- Make sure the branch is up to date with main after checkout:
`git fetch origin main`
- Push new branch to github: `git push -u origin "new-branch-name"`.
After the initial push, you just use git push to make sure your branch
is up to date on github.
- See which files are modified/staged: `git status`.
- Stage changes for commit: `git add "file-name"`.
Can be used again if more changes are made.
- Unstage a commit: `git restore --staged "file-name"`.
---
### When you just want to reset back to remote branch
1. `git fetch origin`
2. `git reset --hard origin/"branch-name"`
---
### Post pull request workflow
1. Switch to main: `git checkout main`
2. Pull latest changes: `git pull`
3. Check local branches: `git branch`
4. Delete old local branch: `git branch -d "branch-name"`
5. Check remote branches: `git branch -r`
6. Remove no longer existing remote branches: `git fetch --prune`
7. Create new branch with: `git checkout -b "branch-name"`
---
    Create pull requests in github.com. You can merge and delete the
    branch remotely. After that, you need to checkout a new branch.
