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


  ### Enhancing Business Value and Architectural Visuals
**Date:** July 13, 2026

**Note:** Focused on elevating the project documentation from a basic technical summary to an enterprise-grade portfolio piece tailored for cloud engineering and GRC roles. 

**Key Updates & Activities:**
* **Business-Oriented README:** Restructured the `README.md` to highlight business impact, system architecture, and enterprise security boundaries. Added a dedicated "Security, Governance & Compliance Controls" section detailing Identity & Access Management (PoLP), GitHub Encrypted Secrets, and Data Protection (AES-256 and TLS).
* **Enterprise Architecture Diagram:** Designed a custom DevSecOps and cloud infrastructure diagram using Microsoft Visio. Visually mapped the secure flow from the local developer environment, through the GitHub Actions pipeline, and into the segmented Azure Resource Group.
* **Repository Organization:** Established a dedicated `images/` directory within the VS Code workspace to maintain clean repository hygiene. Uploaded the Visio export and linked it into the documentation using relative Markdown image paths (`![Alt Text](images/filename.png)`).

**Tools & Techniques Learned:**
* **Visio for the Web Efficiency:** Mastered the "Design Once, Duplicate Often" workflow to maintain consistent fonts and shapes, and utilized alignment tools to perfectly center icons within architectural boundary containers.
* **High-Quality Asset Exporting:** Learned the specific settings required to export Visio diagrams as High-Resolution PNG files (without transparent backgrounds) to ensure crisp readability across both Light and Dark modes on GitHub.
* **Markdown Hierarchy:** Reinforced the use of `##` to generate clean Level 2 Headings, creating a logical, easy-to-read hierarchy for standard technical documentation.
* **Plain Text Code Blocks:** Used the ` ```text ` markdown block format to draft plain-text diagrams and outlines without triggering unwanted programming syntax highlighting.