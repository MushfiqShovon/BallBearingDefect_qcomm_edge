# Ball-Bearing Defect Segmentation — project webpage

Static, self-contained project page (single `index.html` + `assets/`, no build step,
no external dependencies). Light/dark theme follows the visitor's OS preference.

## Publish on GitHub Pages

1. Create a new GitHub repository (e.g. `ballbearing-project-site`).
2. Push this folder:
   ```bash
   git remote add origin https://github.com/<you>/<repo>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment** — Source: *Deploy from a
   branch*, Branch: `main`, folder `/ (root)`. Save.
4. The site goes live at `https://<you>.github.io/<repo>/` within a minute or two.

The `.nojekyll` file tells GitHub Pages to serve files as-is (no Jekyll processing).

## Editing

Everything is in `index.html` (content + CSS). Images live in `assets/` — swap or
add freely; they are plain `<img>` tags with captions. Related code lives in the
main project repo: https://github.com/MushfiqShovon/SAMwithBallbearing
