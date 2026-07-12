# SNHS Website Learning Progress

📅 **Date:** July 12, 2026

> 📝 **Note:** I learned this Git, GitHub, and Azure DevOps workflow by collaborating with Google Gemini to practice local repository management and cloud tracking.

## 🚀 The Core VS Code Git Workflow
Every time I want to update the website, I follow this 4-step professional visual lifecycle:

1. **Edit**: Make changes to the website files in VS Code and save (`Ctrl + S`).
2. **Stage**: Go to the **Source Control panel** (the branch icon) and click the **`+` icon** next to the modified file to prepare it.
3. **Commit**: Type a short descriptive message in the **Message box** at the top of the panel, then click the blue **Commit button** to save a local snapshot.
4. **Push / Sync**: Click the blue **Sync Changes button** (or click the **`...` three dots** at the top right of the panel and select **Push**) to send the snapshot to GitHub and trigger the live Azure deployment.

---

## 💡 Key Concepts Learned

### 📸 Snapshot vs. Backup
* **Snapshot**: Git doesn't make bulky copies of the entire project folder. Instead, a commit only saves the *exact lines of code* that changed since the last checkpoint, making it lightning-fast.
* **The `git config` Signature**: Commits require a `user.name` and `user.email` configuration so that GitHub can securely verify who authored the changes.

### 📝 Why it's called "Markdown" (`.md`)
* It is a clever pun on **"Markup Languages"** (like HTML). 
* Instead of messy technical code tags, it uses lightweight text punctuation (like `#` for headings and `**` for bolding) to stay human-readable as plain text while displaying beautifully on GitHub.

---

## 🛠️ Git Troubleshooting Cheat Sheet

* **Fix Missing Identity Error**: Run these in the terminal if Git blocks a commit:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your-email@example.com"