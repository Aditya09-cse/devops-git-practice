## Git Cheatsheet

- Check installed Git version  
  `git --version`

- Set global username (for all repositories)  
  `git config --global user.name "your-name"`

- Set global email (for all repositories)  
  `git config --global user.email "your-email"`

- Initialize a new empty Git repository  
  `git init`

- Check current repository status  
  `git status`

- Add specific file from untracked → staged  
  `git add <file-name>`

- Add all files from untracked → staged  
  `git add .`

- Remove file from staging area (staged → untracked)  
  `git rm --cached <file-name>`

- Commit staged changes (staged → tracked with history)  
  `git commit -m "your commit message"`

- View full commit history  
  `git log`

- View commit history in one line format  
  `git log --oneline`

- Restore deleted or modified tracked file  
  `git restore <file-name>`

---

## 📁 .git Folder

- The `.git` folder is the most important folder in a Git repository.
- It stores all commits, branches, configuration, and history.
- If you delete the `.git` folder, your project becomes a normal directory (no version control).

## Advance Git
- Merge one branch into another branch  
  → `git merge <branch-name>`

- Replay commits of current branch on top of another branch (linear history)  
  → `git rebase <branch-name>`

- Temporarily save uncommitted work (work in progress)  
  → `git stash`

- Apply stashed changes and remove them from stash list  
  → `git stash pop`

- Apply a specific commit from another branch to current branch  
  → `git cherry-pick <commit-id>`

- Combine all commits of a branch into one commit before merging  
  → `git merge --squash <branch-name>`
