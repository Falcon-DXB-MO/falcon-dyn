# Falcon Dynamics Website

Professional services website for Falcon Dynamics built with the Falcon Dynamics Design System.

## Files Included

```
export/
├── index.html              # Main landing page (rename to index.html at repo root)

└── README.md              # This file
```

## Setup Instructions

1. **Download all files** from the `export/` folder
2. **Place in your GitHub repo root**:
   - Copy `index.html` to the repo root
   - Copy `styles.css` to the repo root
   - Copy the `tokens/` folder to the repo root
3. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Add Falcon Dynamics services website"
   git push origin main
   ```

4. **Enable GitHub Pages**:
   - Go to your repo Settings → Pages
   - Select `main` branch as source
   - Your site will be live at `falcon-dyn.com` (via CNAME)

## Features

- **Responsive Design** — Works on mobile, tablet, and desktop
- **Service Cards** — 6 services showcased with hover animations
- **Professional Typography** — Archivo display font + IBM Plex Sans body
- **Brand Colors** — Navy, crimson, gold, and steel from the design system
- **Call-to-Action Sections** — Hero and closing CTAs with buttons
- **Sticky Navigation** — Always-visible header

## Colors Used

- **Navy** (#0A1626) — Primary brand color
- **Crimson** (#B5202E) — Action/accent color
- **Gold** (#B8945A) — Premium highlights
- **Steel** (#4D5A69) — Neutral text

## No External Dependencies

This website uses only Google Fonts (loaded from CDN). All CSS is self-contained in the `styles.css` and design tokens files. No JavaScript frameworks required.

---

**Built with Falcon Dynamics Design System**
