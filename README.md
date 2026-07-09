# WrestleSIM

A browser-based wrestling promotion business simulator.

## Deploy to Vercel

This package is a static site. The whole game is bundled inside `index.html`.

Vercel settings:

- Framework Preset: Other
- Build Command: leave blank
- Output Directory: leave blank or `.`
- Install Command: leave blank

## Updating your live site

Replace your current GitHub files with the files in this folder, commit the changes, and Vercel should redeploy automatically.

If your old site showed a plain white/basic page, it was likely because the old `index.html` referenced missing `styles.css` and `app.js` files. This fixed version keeps the CSS and JavaScript inside `index.html` so Vercel serves the full game correctly.
