# Rachel’s Loop GitHub Pages Site

Static one-page website for **Rachel’s Loop**. The repository is organized for GitHub Pages publishing from the repository root.

## Repository structure

- `index.html` — GitHub Pages entry page at the repository root
- `style.css` — site styling at the repository root
- `script.js` — mobile navigation behavior at the repository root
- `assets/` — images, textures, stamps, and the pitch deck PDF used by the site

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your publishing branch, usually `main`, and choose `/ (root)` as the folder.
5. Save the settings and wait for GitHub Pages to publish the site.

Because `index.html`, `style.css`, and `script.js` live at the repository root and all media paths point to `assets/`, the site can be served directly by GitHub Pages.
