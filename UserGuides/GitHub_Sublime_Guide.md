# 🐙 GitHub + Sublime Text Integration Guide

---

## 🔗 What Is GitHub?

GitHub is a **cloud-based Git repository hosting service** that helps you:
- Store & manage code
- Track changes with Git
- Collaborate with others via branches, pull requests, and issues

---

## 🧠 How GitHub Works with Sublime Text

Sublime Text itself doesn't directly connect to GitHub, but it integrates with Git — and Git can sync your code with GitHub.

### ✅ How to Use GitHub from Sublime

1. **Write/Edit Code in Sublime**
2. **Use Git (via CLI or plugin) to commit your changes**
3. **Push those commits to GitHub**

---

## 🧩 Recommended Sublime Plugins for GitHub Workflow

| Plugin         | Purpose                                 |
|----------------|------------------------------------------|
| `GitSavvy`     | Full Git interface inside Sublime        |
| `SideBarGit`   | Git actions in right-click sidebar       |
| `GitHubTools`  | Open blame, file links, PRs in GitHub    |
| `Sublime Merge`| Official Git GUI with Sublime integration|

---

## 🚀 Typical Workflow with GitSavvy

1. Open Command Palette: `Ctrl+Shift+P`
2. Run `GitSavvy: Status`
3. You can now:
   - Stage / unstage files
   - Commit changes
   - Push to GitHub
   - Pull from origin
   - Create and checkout branches
   - View diffs and logs

---

## 🧠 Tips from Sublime + GitHub Power Users

- 💡 Keep your project opened as a `.sublime-project` from the root Git repo
- 📦 Add a `README.md` and `LICENSE.md` to every repo for GitHub friendliness
- 🔁 Use GitSavvy's `GitSavvy: Commit` and `GitSavvy: Push` for fast iteration
- 🔗 Use `GitHubTools` to get file links for line-specific sharing
- ⌨️ Create `.sublime-commands` for common Git actions like push/pull

---

## 🔄 Syncing a Project to GitHub (Step-by-Step)

1. **Initialize Git (if needed)**:
   ```bash
   git init
   git remote add origin https://github.com/you/your-repo.git
   ```

2. **Stage & commit**:
   ```bash
   git add .
   git commit -m "Initial commit"
   ```

3. **Push to GitHub**:
   ```bash
   git push -u origin main
   ```

Use GitSavvy for this interactively within Sublime if preferred.

---

## 📁 Recommended Folder Setup

```plaintext
MyProject/
├── .git/
├── .sublime-project
├── README.md
├── LICENSE.md
├── src/
└── docs/
```

---

## 📦 Suggestions for a Better Workflow

- ✅ Use `README.md` and `docs/guide.md` to self-document everything
- ✅ Use `.gitignore` to exclude `*.log`, `*.pyc`, `/node_modules`, etc.
- ✅ Sync Sublime settings (like TabNine config) in your Git repo
- ✅ Add badge shields in your `README.md` (build passing, license, etc.)
- ✅ Use GitHub Actions for CI/CD or linting

---

## 🌟 Bonus Tools

| Tool               | Benefit                          |
|--------------------|----------------------------------|
| `Sublime Merge`    | Git GUI that works seamlessly    |
| `Prettier` / `ESLint`| Code formatters via GitHub hooks |
| `GitHub Copilot`   | More aggressive AI coding (Alt AI) |

---

## ✅ Summary

Sublime is fast, and GitHub is collaborative — using them together means you can:
- Develop with speed
- Document with markdown
- Version everything cleanly
- Share and collaborate effortlessly

