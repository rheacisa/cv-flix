# cv-flix

Netflix-style portfolio template for a personal CV/portfolio site.

Live demo: https://rheacisa.github.io/cv-flix/

About
- Minimal static HTML portfolio inspired by a Netflix layout.
- Author: Rhea

Preview locally

1. Start a local web server from the project root:

```bash
cd /workspaces/cv-flix
python3 -m http.server 8000
```

2. Open http://localhost:8000 in your browser and refresh to see changes.

Editing
- The main file is `index.html`. Edit it in the editor and refresh your browser to preview.

Deploy (GitHub Pages)

1. Push changes to `main` on your fork (`rheacisa/cv-flix`).

```bash
git add -A
git commit -m "Update site"
git push origin main
```

2. In the repo on GitHub, go to **Settings → Pages** and set:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`

3. Save. Your site will be published at `https://rheacisa.github.io/cv-flix/`.

Notes
- Images and external assets are hotlinked from the web (Unsplash, Google Play). Replace them if you want local assets.
- If you want a custom domain or HTTPS configuration, I can help set that up next.
