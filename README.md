# AI Course — 2nd Lesson

A lesson webpage published via [GitHub Pages](https://pages.github.com/).

## Live site

Once deployed, your site will be available at:

**https://chrislsm12-hash.github.io/AI-Course---2nd-Lesson/**

## How it works

This repository uses GitHub Actions to deploy the site automatically whenever you push to the `main` branch.

1. Edit `index.html` (and add any CSS, JS, or image files you need).
2. Commit and push your changes to `main`.
3. GitHub Actions builds and deploys the site (usually within 1–2 minutes).

You can check deployment status under the **Actions** tab on GitHub.

## Local preview

Open `index.html` in your browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Adding your webpage

If you built your page in Cursor locally, copy your files into this repository:

- `index.html` — main entry point (required)
- `style.css`, `script.js`, images, etc. — any supporting assets

Make sure asset paths are **relative** (e.g. `./style.css`, not `/style.css`) so they work correctly on GitHub Pages.

## First-time setup (one step)

GitHub Pages must be turned on once in your repository settings:

1. Open **Settings → Pages** on GitHub
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**
3. Choose branch **`gh-pages`**, folder **`/ (root)`**
4. Click **Save**

After the first push to `main`, the workflow creates the `gh-pages` branch automatically. Future pushes redeploy the site within about a minute.
