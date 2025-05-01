# Monthly Bills Log (PWA)

This is a Progressive Web App (PWA) that helps you track monthly bills with a dropdown to select pre-filled months, live summary calculations, and offline support. You can install it on your phone and manage your expenses easily.

## Features
- Preloaded month selection (12 months ahead)
- Auto-saves data locally per month
- Print/save summaries as PDF
- Export to JSON or CSV
- Delete or update any month
- Installable like a mobile app
- Works offline (via service worker)

## How to Deploy on GitHub Pages

1. **Create a Repository**
   - Go to [GitHub](https://github.com)
   - Click "New Repository"
   - Name it something like `monthly-bills-pwa`
   - Do not initialize with README

2. **Upload Files**
   - Upload the following files:
     - `monthly_bills_pwa_with_icons.html`
     - `manifest_updated.json`
     - `service-worker.js`
     - `calendar_icon_192.png`
     - `calendar_icon_512.png`

3. **Enable GitHub Pages**
   - Go to `Settings > Pages`
   - Under "Source", choose:
     - Branch: `main`
     - Folder: `/root`
   - Save and wait for your live link (e.g. https://yourname.github.io/monthly-bills-pwa/)

4. **Install App**
   - Open your site on a mobile browser
   - Tap Share → "Add to Home Screen"

---

**Powered by Press**