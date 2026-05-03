# Deploying to GitHub Pages

**Your site folder:** `eportfolio-naief/`  
**Target URL:** `https://YOUR-USERNAME.github.io/naief-capstone-eportfolio/`  
**Time needed:** ~10 minutes

---

## Step 1 — Create the GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon (top right) → **New repository**
3. Repository name: `naief-capstone-eportfolio`
4. Set to **Private** (you said you want it private until complete)
5. Leave everything else unchecked
6. Click **Create repository**

---

## Step 2 — Upload your files

On the new empty repository page:

1. Click **uploading an existing file** (the link in the middle of the page)
2. Open your `eportfolio-naief/` folder on your computer
3. Select **all files and folders** inside it:
   - `index.html`
   - `about.html`
   - `project.html`
   - `competencies.html`
   - `deliverables.html`
   - `reflection.html`
   - `assets/` folder (drag the whole folder — GitHub accepts folder uploads via drag-and-drop)
4. Wait for the upload to complete
5. Scroll down, add a commit message (e.g. "Initial upload") and click **Commit changes**

> **Important:** Make sure `assets/css/style.css` and `assets/img/profile.jpg` are both uploaded inside their folders, or the pages will be unstyled and the photo will be broken.

---

## Step 3 — Enable GitHub Pages

1. In your repository, click **Settings** (tab at the top)
2. In the left sidebar, scroll to **Pages**
3. Under "Source", select **Deploy from a branch**
4. Branch: `main` · Folder: `/ (root)`
5. Click **Save**

GitHub will show a message: *"Your site is being built."* Wait about 60 seconds, then refresh the page — you'll see the live URL.

---

## Step 4 — Visit your site

Your URL will be:
```
https://YOUR-USERNAME.github.io/naief-capstone-eportfolio/
```

Replace `YOUR-USERNAME` with your actual GitHub username.

> **Note:** The site is Private on GitHub (code is hidden), but GitHub Pages publishes it publicly. If you want the site completely inaccessible until submission, skip Step 3 until you're ready. You can enable Pages at any time.

---

## Updating content later

To update any page:
1. Go to your repository on GitHub
2. Click the file you want to edit (e.g. `reflection.html`)
3. Click the **pencil icon** (Edit this file)
4. Make your changes
5. Click **Commit changes**

The live site updates within ~30 seconds.

**For July 2026 final reflection:** Edit `reflection.html`, replace the interim reflection text with your final version, remove the ℹ️ note at the top, and update the `<title>` and `.subtitle` to remove "Interim Reflection · April 2026".

---

## File structure reference

```
eportfolio-naief/
├── index.html          ← Home page
├── about.html          ← About Me
├── project.html        ← About the Project
├── competencies.html   ← AHS Competencies (all 5)
├── deliverables.html   ← Project Deliverables
├── reflection.html     ← Critical Self-Reflection
├── assets/
│   ├── css/
│   │   └── style.css   ← All styling (Western purple design system)
│   └── img/
│       └── profile.jpg ← Profile photo
└── DEPLOY.md           ← This file (do not upload this one)
```

---

## When the app is live

Update `deliverables.html` — find this block:

```html
<span class="deliv-pending">⏳ In active development — link coming soon</span>
```

Replace with:

```html
<a class="deliv-link" href="YOUR-APP-URL" target="_blank" rel="noopener">Open App ↗</a>
```
