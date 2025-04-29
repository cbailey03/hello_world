# Hello World
    Intro repository to become familiar with github.
---
Keyboard shortcuts
---
- Ctrl + ` : toggles the terminal.
- Ctrl + w : closes the current editor tab.
- Ctrl + Shift + t : reopens the most recently closed tab.
- Ctrl + g : opens dialog to go to specific line, column.
---
Basic commands.
- Create a branch: git checkout -b "new-branch-name"
- Checkout existing branch: git checout "branch-name"
- Make sure the branch is up to date with main after checkout.
git fetch origin main
- Push new branch to github: git push -u origin "new-branch-name".
After the initial push, you just use git push to make sure your branch
is up to date on github.
- See which files are modified/staged: git status.
- Stage changes for commit: git add "file-name".
Can be used again if more changes are made.
- Unstage a commit: git restore --staged "file-name".

