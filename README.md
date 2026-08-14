# Yang Weiqiang — Academic Homepage (GitHub Pages)

A static personal / research homepage for Yang Weiqiang, built from the final CV
(`Yang_Weiqiang_CV（保研）.docx`). No build step, no framework — plain HTML/CSS.

## Files
- `index.html` — the page (all content lives here)
- `assets/css/style.css` — styling (responsive, light academic theme)
- `.nojekyll` — tells GitHub Pages not to run Jekyll
- `assets/img/` — drop your photo here as `avatar.jpg` and update the `<img>` in `index.html`

## Customize
- **Photo:** replace the avatar circle (initials "YW") with
  `<img src="assets/img/avatar.jpg" alt="Yang Weiqiang">` inside `.avatar`.
- **Links:** in the sidebar `.links`, uncomment and edit the GitHub / LinkedIn / CV(PDF) buttons.
- **Content:** edit the text directly in `index.html`.

## Deploy to GitHub Pages
1. Create a repo on GitHub (e.g. `yang-weiqiang.github.io` for a user site, or any repo name for a project site).
2. Push this folder to the repo:
   ```bash
   git init
   git add .
   git commit -m "Initial academic homepage"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   choose branch `main` and folder `/ (root)`, then **Save**.
4. Wait ~1 minute. Your site is live at:
   - user site: `https://<your-username>.github.io`
   - project site: `https://<your-username>.github.io/<repo>`

> Tip: if you want a custom domain, add a `CNAME` file containing the domain and set it
> in Settings → Pages.
