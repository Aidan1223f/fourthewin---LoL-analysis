# Project 4: League of Legends – GitHub Pages

This folder contains everything needed to publish your project as a **GitHub Pages** site in its own repo.

## What’s included

- `index.html` – project page (research question, methods, visualizations)
- `jhin_wl.png`, `jhin_wr_by_league.png`, `KD_JhinBot.png`, `goldvsdmgJhin.png`, `numericasummary.png` – images used by the page

## Steps to publish

1. **Create a new repo on GitHub**
   - Go to [github.com/new](https://github.com/new).
   - Name it something like `proj04-lol` or `lol-jhin-analysis` (or anything you like).
   - Leave it empty (no README, .gitignore, or license).
   - Create the repo.

2. **Push this folder as the repo contents**
   From your computer, in a terminal:

   ```bash
   cd /Users/aidannguyen/Downloads/DSC80/dsc80-2026-wi/projects/proj04-pages
   git init
   git add .
   git commit -m "Initial commit: Project 4 project page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and the repo name you chose.

3. **Turn on GitHub Pages**
   - Open your new repo on GitHub.
   - Go to **Settings** → **Pages** (left sidebar).
   - Under **Build and deployment**:
     - **Source:** Deploy from a branch
     - **Branch:** `main` (or `master`)
     - **Folder:** `/ (root)`
   - Click **Save**.

4. **Open your site**
   After 1–2 minutes, your page will be at:
   **https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/**

Use that URL as your **Website Link** in the project notebook.
