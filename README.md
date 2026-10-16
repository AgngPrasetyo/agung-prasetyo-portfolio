# Agung Prasetyo — Portfolio Website

A responsive, single-page portfolio built with plain HTML, CSS, and JavaScript. It is designed to publish on GitHub Pages without a VPS, paid domain, database, or build step.

## Preview locally

Open `index.html` in a browser. For a more realistic local preview, use VS Code's Live Server extension or run a static file server from this folder.

## Publish for free with GitHub Pages

1. Sign in to GitHub and create a **public** repository named `agung-prasetyo-portfolio` (or another available name).
2. Upload the contents of this folder to the **root** of the repository. Make sure `index.html` is at the repository root, not buried in an extra folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, set the source to **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for the deployment to finish. Your site will be available at `https://YOUR-GITHUB-USERNAME.github.io/REPOSITORY-NAME/`.

For the cleanest URL, you can instead create a public repository named `YOUR-GITHUB-USERNAME.github.io`; then the URL will be `https://YOUR-GITHUB-USERNAME.github.io/`.

## Before publishing

- Review the CV PDF in `assets/Agung_Prasetyo_CV.pdf` and replace it if you update your CV.
- Verify the contact links and any public details you want to share.
- Add project repository or live-demo links only when you have confirmed the URLs.
- The portfolio is static: GitHub Pages does not run a Flask/Python backend. It can showcase your Flask projects and screenshots, while those apps themselves need separate hosting if you want their live functionality online.

## Files

- `index.html` — page content and semantic structure
- `styles.css` — layout, visual styling, and responsive rules
- `script.js` — mobile navigation, project filters, and dynamic footer year
- `assets/` — project screenshots, favicon, and downloadable CV
