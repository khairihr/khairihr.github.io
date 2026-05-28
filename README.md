# Khairi Hibatullah Ridho — Portfolio

A static, single-file portfolio site + résumé. No build step, no dependencies.

## Files
- `index.html` — the portfolio site (this is the homepage)
- `cv.html` — printable résumé. Open it and click **Save as PDF** to export a clean PDF.
- `vercel.json` — optional Vercel config (clean URLs)

## Preview locally
Just double-click `index.html`, or run a tiny server:

```bash
# Python
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy to Vercel (easiest)
1. Create a free account at https://vercel.com
2. **Option A — drag & drop:** go to the Vercel dashboard → "Add New… → Project" → drag this whole folder in.
3. **Option B — Git:** push this folder to a GitHub repo, then "Import Project" in Vercel. Framework preset: **Other**. No build command, output dir = root.

Your site will be live at `https://<your-name>.vercel.app`. You can add a custom domain later for free.

## Deploy to Netlify / GitHub Pages (alternatives)
- **Netlify:** drag the folder onto https://app.netlify.com/drop
- **GitHub Pages:** push to a repo, enable Pages on the `main` branch root.

## Updating content
Everything is plain HTML/CSS in `index.html` and `cv.html`. Edit text directly. The résumé link in the nav points to `cv.html`.
