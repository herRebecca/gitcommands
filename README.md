# Git Practice Repository

Welcome to Esther’s Practice Repository — a collaborative project designed to help me learn and practice Git through real-world workflows.

Each contributor creates a branch focused on a specific Git command (most branches were contributed by me as part of my Git learning process 😅). The branches are later merged together to help practice real Git merge workflows and collaboration.

This `main` branch serves as the base branch, containing the homepage and this README file.

---

##  Project Update

**May 15, 2026**

All individual Git command branches have now been successfully merged into the `git--merge` branch, and subsequently merged into the `main` branch without conflicts or lost changes.

This completed the repository's primary goal of practicing:

- branch creation
- isolated feature work
- merge workflows
- collaborative Git practices
- conflict-free integration

The repository now serves as a consolidated reference for beginner Git commands and workflows.

---

##  Project Purpose

- Practice Git branching and collaboration.
- Document individual Git commands in isolated branches.
- Learn by doing — hands-on experience with commits, branches, merges, and pull requests.
- Understand how collaborative Git workflows function in real projects.

---

##  Repository Structure

- `main` → stable project branch
- `git--merge` → branch used to merge all Git command branches together
- `git-*` branches → individual Git command practice branches

---

##  How This Works

### 1. Clone this repository from the `main` branch

git clone https://github.com/herRebecca/gitcommands.git
cd gitcommands

##  How This Works

### 1. Clone this repository from the `main` branch

```bash
git clone https://github.com/herRebecca/gitcommands.git
cd gitcommands
```

### 2. Create a new branch named after a Git command

```bash
git checkout -b git-status
```

### 3. Add content to your branch

Add HTML and CSS content that explains or demonstrates the Git command.

> No need to edit files directly on the `main` branch.

### 4. Push your branch to GitHub

```bash
git push origin git-status
```

---

##  Table of Contents (Git Command Branches)

| Git Command | Branch Name | Contributor |
|-------------|-------------|-------------|
| git init    | git-init    | @esther |
| git clone   | git-clone   | @esther |
| git commit  | git-commit  | @esther |
| git push    | git-push    | @esther |

🔗 You can explore each branch on GitHub by switching branches using the branch dropdown menu.

---

##  Contributing

Collaborators who are added to the repository will have access to contribute.

Please follow these simple rules:

- Use clear and consistent branch names (e.g., `git-fetch`, `git-rebase`)
- Only commit to your own branch
- Add meaningful content that explains or demonstrates the Git command
- Keep changes isolated to your branch
- Pull requests are optional unless you want a review or want your branch merged into another branch

---

##  Lessons Learned

Through this project, I practiced:

- creating and switching branches
- staging and committing changes
- pushing branches to GitHub
- merging multiple branches
- understanding merge workflows
- collaborative Git practices
- organizing a beginner-friendly repository structure

---

##  License

This project is intended for learning and educational purposes.

No formal license has been applied.
