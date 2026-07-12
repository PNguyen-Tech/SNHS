# SNHS Website Learning Progress

> 📝 **Note:** I learned this Git, GitHub, and Azure DevOps workflow by collaborating with Google Gemini to practice local repository management and cloud tracking.

## 🚀 The Core Git Workflow
Every time I want to update the website, I follow this 4-step professional lifecycle:

1. **Edit**: Make changes to the website files in VS Code and save (`Ctrl + S`).
2. **Stage**: Package the specific changes into the staging area:
   ```bash
   git add .

```

3. **Commit**: Take a permanent local snapshot with a descriptive message:
```bash
git commit -m "Your description here"

```


4. **Push**: Sync the snapshot to GitHub to trigger the live Azure deployment:
```bash
git push origin main

```



---

## 💡 Key Concepts Learned

### 📸 Snapshot vs. Backup

* **Snapshot**: Git doesn't make bulky copies of the entire project folder. Instead, a commit only saves the *exact lines of code* that changed since the last checkpoint, making it lightning-fast.
* **The `git config` Signature**: Commits require a `user.name` and `user.email` configuration so that GitHub can securely verify who authored the changes.

### 📝 Why it's called "Markdown" (`.md`)

* It is a clever pun on **"Markup Languages"** (like HTML).
* Instead of messy technical code tags, it uses lightweight text punctuation (like `#` for headings and `` for bolding) to stay human-readable as plain text while displaying beautifully on GitHub.

---

## 🛠️ Git Troubleshooting Cheat Sheet

* **Fix Missing Identity Error**: Run these in the terminal if Git blocks a commit:
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

```


* **Local Undo (Discard Changes)**: To instantly erase unsaved or uncommitted mistakes and revert to the last clean checkpoint, hover over the file in the **Source Control** view and click the **Discard Changes** icon (counter-clockwise arrow).
* **Periodical Fetching**: Let VS Code run `git fetch` automatically in the background so it can quietly check GitHub for updates and keep the laptop safely in sync.

```
