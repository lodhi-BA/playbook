# Asad Lodhi — Professional Portfolio

Professional portfolio website for Asad Lodhi, Sr. Business Analyst / IT Project Manager.

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1: Create a GitHub repository
1. Go to [github.com](https://github.com) and sign in
2. Click **"New repository"** (green button, top right)
3. Name it: `portfolio` (or `asad-lodhi-portfolio`)
4. Set to **Public**
5. Click **"Create repository"**

### Step 2: Upload your files
1. On the new repo page, click **"uploading an existing file"**
2. **Drag and drop the entire contents of this folder** (all HTML, CSS, JS files + subfolders)
3. Make sure the folder structure is preserved:
   ```
   index.html
   experience.html
   expertise.html
   artifacts.html
   contact.html
   css/main.css
   js/main.js
   artifacts/brd.html
   artifacts/user-stories.html
   artifacts/gap-analysis.html
   artifacts/process-map.html
   artifacts/test-plan.html
   artifacts/kpi-dashboard.html
   ```
4. Add commit message: `Initial portfolio upload`
5. Click **"Commit changes"**

### Step 3: Enable GitHub Pages
1. In your repository, click **"Settings"** (top nav)
2. Scroll to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"Deploy from a branch"**
4. Branch: `main` / Folder: `/ (root)`
5. Click **"Save"**

### Step 4: Your site is live! 🎉
After ~2 minutes, your site will be available at:
```
https://[your-github-username].github.io/portfolio/
```

---

## 📁 Site Structure

| File | Page |
|------|------|
| `index.html` | Homepage — hero, achievements, artifact preview |
| `experience.html` | Full work history — E2, TCS, Hitachi, BD |
| `expertise.html` | Skills deep-dive — BA, IS, PM domains |
| `artifacts.html` | Sample document index |
| `contact.html` | Contact form + direct info |
| `artifacts/brd.html` | Business Requirements Document sample |
| `artifacts/user-stories.html` | Agile User Story Backlog |
| `artifacts/gap-analysis.html` | System Gap Analysis Report |
| `artifacts/process-map.html` | AS-IS / TO-BE Process Map |
| `artifacts/test-plan.html` | System Integration Test Plan |
| `artifacts/kpi-dashboard.html` | Interactive KPI Dashboard |

---

## ✏️ Customization

**Update LinkedIn URL:** Open `index.html` and `contact.html`, search for `linkedin.com/in/asadlodhi` and replace with your actual LinkedIn URL.

**Update contact form:** The form currently shows a success animation. To make it actually send emails, connect it to a free service like [Formspree](https://formspree.io) — just replace the `<form>` action with your Formspree endpoint.

---

Built with plain HTML, CSS, and JavaScript — no frameworks, no build tools needed.
