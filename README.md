# Deploy DataGuard to GitHub Pages — Free Hosting Guide

Your website will be live at:
https://YOUR-USERNAME.github.io/dataguard

---

## STEP 1 — Create a GitHub Account (skip if you have one)
1. Go to https://github.com
2. Click "Sign Up" and create a free account
3. Verify your email

---

## STEP 2 — Create a New Repository
1. Click the green "New" button (top left on GitHub)
2. Fill in:
   - Repository name: dataguard
   - Description: Automated Data Quality Auditor
   - Set to: PUBLIC  ← important for free hosting
   - Check: "Add a README file"
3. Click "Create repository"

---

## STEP 3 — Upload index.html
1. Inside your new repo, click "Add file" → "Upload files"
2. Drag and drop the index.html file you downloaded
3. Scroll down, click "Commit changes"

Your repo should now show index.html in the file list.

---

## STEP 4 — Enable GitHub Pages
1. Click "Settings" tab (top of your repo)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source" → select "Deploy from a branch"
4. Branch: main  |  Folder: / (root)
5. Click "Save"

---

## STEP 5 — Wait ~60 seconds, then visit your site
Your URL:  https://YOUR-GITHUB-USERNAME.github.io/dataguard

Example:   https://sdgai.github.io/dataguard

GitHub will show a green checkmark under Settings → Pages when ready.

---

## STEP 6 — Test it!
1. Open your URL in any browser
2. Drop a CSV file onto the upload zone
3. Wait ~5–10 seconds for Python to load in the browser (first time only)
4. See your full data quality dashboard!

---

## HOW TO UPDATE THE SITE LATER
If you want to update the website with a new version of index.html:
1. Go to your repo on GitHub
2. Click on index.html
3. Click the pencil icon (Edit)
4. Or click "Add file" → "Upload files" to replace it
5. Changes go live within 60 seconds

---

## SHARING YOUR SITE
Send anyone this link and they can audit their own CSVs:
https://YOUR-USERNAME.github.io/dataguard

Features:
  Works on phone, tablet, desktop
  No login required
  Data stays in the user's browser — never uploaded anywhere
  Free forever on GitHub Pages

---

## TROUBLESHOOTING

Problem: Site shows 404
Fix: Wait 2 minutes after enabling Pages, then hard-refresh (Ctrl+F5)

Problem: Python takes too long to load
Fix: Normal on first visit — Pyodide (~10MB) is downloading.
     Subsequent uses are cached and much faster.

Problem: CSV analysis fails
Fix: Make sure your CSV has a header row.
     Maximum file size is ~50MB.

---

## OPTIONAL — Custom Domain
If you want a custom URL like dataguard.yourdomain.com:
1. Settings → Pages → Custom domain
2. Enter your domain and follow DNS instructions
GitHub Pages supports free SSL/HTTPS on custom domains too.
