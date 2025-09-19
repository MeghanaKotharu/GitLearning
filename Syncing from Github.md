# Syncing with Remote Repositories (GitHub)

These commands are used to **collaborate and sync** your local repository with GitHub (or any other remote host).

---

## Commands

| Command                            | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| `git push origin <branch-name>`    | Uploads your local commits to the remote repository (commonly `main`). |
| `git push -u origin main`          | Sets `origin main` as the default. <br>➡️ After this, you can simply run `git push` next time. |
| `git fetch origin`                 | Downloads changes from the remote **without merging** them into your local branch. |
| `git pull origin <branch-name>`    | Downloads and **automatically merges** changes from the remote branch into your local branch. |
| `git remote add origin <link>`     | Links your local repository to a remote one on GitHub (`<link>` = repo URL). |
| `git remote -v`                    | Lists the remote repositories your local repo is connected to. |

---

✅ Typical flow after local changes:  
1. `git add .`  
2. `git commit -m "message"`  
3. `git push`  -for github 

