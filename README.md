## **Git**

* **Definition**: Git is a **version control system (VCS)** that helps track changes in code.

* **Features**:

  * Open-source, fast, and scalable.
  * Tracks the **history of code**, making it easy to go back to a previous version (savepoint).
  * Enables **collaboration** among developers.
  * Works locally on your system.

* **Workflow**:

  * Whenever we make changes in Git, we typically follow 2 steps:

    1. **Add** → Stage the changes (preparing them for commit).
    2. **Commit** → Save the changes to the Git history with a message.

---

## **GitHub**

* **Definition**: GitHub is a **cloud-based platform** that allows developers to host and manage their code repositories using Git.

* **Features**:

  * Stores code in repositories (folders).
  * Serves as a **developer portfolio**.
  * Supports collaboration through pull requests, issues, and discussions.
  * Provides a `README.md` file for project description, features, and instructions (written in **Markdown**).

* **Note**: On GitHub, you usually see commits directly (no manual `add` step like in Git on your local system).

---

## **Pre-requisites**

1. **Install Git**

   * Download from [Git official site](https://git-scm.com/)
   * Or check if already installed:

     ```bash
     git --version
     ```

2. **Install Windows Terminal (if on Windows)**

3. **Configure Git** (set up identity for commits):

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your_email@example.com"
   ```

---

👉 Would you like me to also create a **step-by-step cheat sheet** with the most commonly used Git + GitHub commands (clone, push, pull, etc.) so you have everything in one place?
