# Portfolio site

Static site: `index.html`, `style.css`, `img/`. No build step.


## Deploy with GitHub Pages
1. Create a repo on GitHub (for a root URL `https://cynd2.github.io`, name it `cynd2.github.io`).
2. In this folder:
   ```
   git init
   git add .
   git commit -m "Add portfolio site"
   git branch -M main
   git remote add origin https://github.com/cynd2/cynd2.github.io.git
   git push -u origin main
   ```
3. On GitHub: Settings > Pages > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
4. Wait a minute, then open `https://cynd2.github.io`.

Optional: add a custom domain under Settings > Pages.
