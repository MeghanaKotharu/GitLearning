# Adding a Local Directory to Git & GitHub

When we create a new repository/folder on our **local machine** (instead of cloning from GitHub), we need to follow a slightly different process.  
This is done **only once** to upload a local project into GitHub.

---

## Steps

1. Create a new folder/repo locally and add your project files.  
2. Initialize Git in that folder.  
3. Create an **empty repository** on GitHub with the **same name**.  
   - ⚠️ Do **not** initialize with a README, `.gitignore`, or license (unless you also add them locally).  
4. Link your local repo to the GitHub remote.  
5. Add and commit files locally.  
6. Push them to GitHub.

---

## Commands

| Command                            | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| `git init`                         | Initializes a new Git repository in the current directory. |
| `git remote add origin <link>`     | Links the local repo to the GitHub repo (`<link>` = new repo URL on GitHub). |
| `git remote -v`                    | Verifies the remote repository details. |
| `git add .`                        | Stages all files in the current directory. |
| `git commit -m "first commit"`     | Commits the staged files with a message. |
| `git branch -M main`               | Renames the default branch to `main` (recommended). |
| `git push -u origin main`          | Pushes your local commits to GitHub (first push). |

---

✅ After this setup, you can continue the normal workflow:  
- `git add <file>` → `git commit -m "message"` → `git push origin main`
