# DenDoc Dental — Website

A single-page luxury dental clinic website. Pure HTML, CSS, and JavaScript — no build tools or frameworks required.

## Structure
```
index.html      → main page markup
css/style.css   → all styles
js/script.js    → all interactivity (animations, sliders, forms, theme toggle, etc.)
```

## Deploy on GitHub Pages
1. Create a new GitHub repository (e.g. `dendoc-dental`).
2. Upload `index.html`, the `css/` folder, and the `js/` folder to the repo root (keep the folder structure intact).
3. Go to **Settings → Pages** in your repo.
4. Under **Source**, select the `main` branch and `/ (root)` folder, then **Save**.
5. GitHub will publish your site at:
   `https://<your-username>.github.io/dendoc-dental/`
   (takes 1–2 minutes to go live after first deploy)

## Notes
- No backend/build step needed — it's static HTML/CSS/JS, so GitHub Pages serves it as-is.
- Google Fonts and the Lucide icon library load from CDNs, so an internet connection is required when viewing the site.
- Placeholder images (doctor portraits, testimonial avatars) use randomuser.me — swap these `src` URLs in `index.html` for real photos before going fully live.
- Update the WhatsApp number, phone numbers, and email in `index.html` (Contact + footer sections) to your real clinic details.
