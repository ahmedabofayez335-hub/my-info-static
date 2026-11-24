# Static personal site (free, 24/7 on GitHub Pages)

## Edit
Open `config.js` and change your info. Put your picture in this folder as `photo.jpg` (or paste an image link in `photo`).
For Arabic set `lang: "ar"` and `dir: "rtl"`.

## Deploy on GitHub Pages
1. Create a GitHub account and a new **public** repository (e.g. `me`).
2. Upload all files from this folder (including `.nojekyll`) to the repo root.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
4. After about a minute your site is live at `https://USERNAME.github.io/REPO/`.
   (Name the repo `USERNAME.github.io` to get `https://USERNAME.github.io/`.)

To update later: edit `config.js` on GitHub (pencil icon) → Commit. The site refreshes in about a minute.

## Test locally
Just double-click `index.html`.
