# Basic Workflow: Local Changes in Git (Add & Commit)

Once we clone code from GitHub, it exists in our **local system**.  
But until we add & commit, the changes are **not stored in Git’s history**.  

- For **Git (local)** → we must do both `add` and `commit`.  
- For **GitHub (remote)** → only `push` is needed after commit.  

---

## File Status in Git

- **Untracked (U):** New files created (e.g., in VS Code) but not yet added to Git.  
- **Modified (M):** Files changed after the last commit but not staged.  
- **Staged (S):** Files added with `git add`, waiting to be committed.  
- **Unmodified:** Files already committed to Git (no changes).  

⚠️ If local changes are not yet pushed, Git may show:  
`your branch is ahead by 1 commit`  

---

## Commands

| Command                   | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `git status`              | Shows the current state of your working directory (untracked, modified, staged files). |
| `git add <file>`          | Stages a specific file for the next commit. |
| `git add .`               | Stages **all modified and new files** in the current directory. |
| `git commit -m "message"` | Permanently saves staged changes to your local project history. |
| `git log`                 | Displays the commit history for the current branch. |
| `git diff`                | Shows differences between **unstaged changes** and the last commit. |
| `git diff --staged`       | Shows differences between **staged changes** and the last commit. |

---
