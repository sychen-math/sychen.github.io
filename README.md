# Shih-Yu Chen

A lightweight static academic website prepared for GitHub Pages. It uses plain HTML and CSS, so no build system or command-line setup is required.

## Publish with GitHub Pages

1. Sign in to GitHub.
2. Create a **public** repository named exactly:

   ```text
   YOUR-USERNAME.github.io
   ```

   Replace `YOUR-USERNAME` with your actual GitHub username.
3. In the new repository, choose **Add file → Upload files**.
4. Upload the **contents** of this folder, not the enclosing folder itself. The repository root should contain `index.html`, `404.html`, `README.md`, `.nojekyll`, and the `assets` folder.
5. Commit the files to the `main` branch.
6. Open **Settings → Pages**. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
7. The site will be available at:

   ```text
   https://YOUR-USERNAME.github.io/
   ```

## Updating the site

- Personal details and publication entries are in `index.html`.
- Visual design is in `assets/style.css`.
- To edit on GitHub, open a file and click the pencil icon, then commit the change.

## Files

- `index.html` — website content
- `assets/style.css` — layout and visual design
- `assets/favicon.svg` — browser icon
- `404.html` — custom not-found page
- `.nojekyll` — tells GitHub Pages to serve the files directly
