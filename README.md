# ScaleUp Nepal — Landing Page

A static landing page linking to the four city cohort application forms (Dhangadi, Butwal, Pokhara, Surkhet).

## Local preview
Just open `index.html` in any browser. No build step.

## Deploy to Vercel via GitHub

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit — ScaleUp Nepal landing"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

### 2. Connect to Vercel
1. Go to [vercel.com/new](https://vercel.com/new)
2. Import your GitHub repo
3. **Framework Preset:** `Other` (static site — no build needed)
4. **Build Command:** leave empty
5. **Output Directory:** leave empty (or `.`)
6. Click **Deploy**

Every push to `main` will auto-redeploy.

## Files
- `index.html` — the page
- `assets/scaleup-logo.png` — logo (transparent, white-on-dark)
- `assets/scaleup-theme.png` — reference theme image (not used at runtime; safe to delete)
- `vercel.json` — Vercel config (clean URLs)
