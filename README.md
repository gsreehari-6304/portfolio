# Sree Hari — Portfolio Website

A responsive portfolio website built with HTML5, CSS3, and vanilla JavaScript.

## Files
- `index.html` — portfolio content and semantic page structure.
- `style.css` — dark theme, responsive layouts, and visual effects.
- `script.js` — mobile navigation, current year, and contact form email preparation.
- `assets/Sreehari_IT_Resume.pdf` — add your resume PDF here before using the resume download buttons.

## Run locally
1. Keep the folder structure as supplied.
2. Copy your resume PDF to `assets/Sreehari_IT_Resume.pdf`.
3. Open `index.html` in a browser. For best results, use VS Code with the Live Server extension and click **Go Live**.

## Resume
The two resume buttons point to `assets/Sreehari_IT_Resume.pdf`. The PDF is not bundled automatically; copy your resume into that exact location.

## Contact form
The form validates fields and opens the visitor's configured email app with a prepared email. It does not send through a backend. To receive messages without the visitor's email app, connect a form service or build a backend and update `script.js`.

## Publish on GitHub Pages
1. Create a GitHub repository, for example `sreehari-portfolio`.
2. Upload `index.html`, `style.css`, `script.js`, and the `assets` folder.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
5. Wait for GitHub Pages to publish and use the URL shown in Settings → Pages.

## Publish on Netlify
1. Sign in to Netlify.
2. Choose **Add new site / Deploy manually** (label may vary).
3. Drag the portfolio folder into the deployment area, or connect your GitHub repository.
4. Test the published URL and resume download.

## Before publishing
- [ ] Add `assets/Sreehari_IT_Resume.pdf`.
- [ ] Check email, phone, and LinkedIn details.
- [ ] Check the website on mobile and desktop.
- [ ] Test the resume download and contact form.
- [ ] Add real GitHub/project links only when available.
