# Pramesh Basnet — Portfolio

A single-page portfolio website for **Pramesh Basnet** — Zoologist, Environmental Enthusiast & Science Graduate.

Built as a self-contained static site (`index.html`) with no build step or dependencies (fonts load from Google Fonts CDN).

## Run locally

Just open the file in a browser:

```bash
open index.html        # macOS
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy with GitHub Pages

1. **Create a repo** on GitHub (e.g. `pramesh-portfolio`).
2. **Push this folder** to the repo:

   ```bash
   git add .
   git commit -m "Add portfolio site"
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick the **`main`** branch and the **`/ (root)`** folder, then **Save**.
5. Wait a minute — your site goes live at:

   ```
   https://<your-username>.github.io/<your-repo>/
   ```

The `.nojekyll` file tells GitHub Pages to serve the files as-is (skip Jekyll processing).

## Before you publish — edit these placeholders

In `index.html`:

- Replace `your-email@example.com` with your real email.
- Replace the `#` in the **LinkedIn** and **Instagram** links with your real profile URLs.
- Optionally swap the "PB" avatar initials for a real photo.
