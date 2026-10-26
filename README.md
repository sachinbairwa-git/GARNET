# GARNET

Project website for **"From Attribute Alignment to Attribute Verification: GARNET for
Text-Based Person Retrieval"** (WACV 2027, Paper ID 2471).

**Source code: Coming Soon.** This repository currently hosts only the project
website (`index.html` + `assets/`), published via GitHub Pages at
**https://sachinbairwa-git.github.io/GARNET/**. The GARNET training/evaluation
code will be released here before the camera-ready deadline.

---

Static site: `index.html` + `assets/`. No build step.

## Publish to GitHub Pages

This repo already contains a GitHub Actions workflow
(`.github/workflows/pages.yml`) that deploys `index.html` on every push to
`main`. From this directory:

```bash
git remote add origin https://github.com/sachinbairwa-git/GARNET.git
git add -A
git commit -m "Add GARNET project website"
git push -u origin main
```

Then, in the GitHub repo: **Settings → Pages → Build and deployment → Source
= "GitHub Actions"** (one-time setting). The workflow will run automatically
and the site will be published at:

```
https://sachinbairwa-git.github.io/GARNET/
```

Check the **Actions** tab for build status; the URL above goes live a minute
or two after the first successful run.

## Updating the page later

Edit `index.html` / `assets/css/style.css`, commit, and push to `main` — the
workflow redeploys automatically.
