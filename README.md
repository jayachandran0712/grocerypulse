# GroceryPulse – Retail Manager

A mobile-first installable Progressive Web App for a grocery retailer.

## Features
- Product catalogue with purchase price, selling price, stock, reorder level, category and supplier
- Purchase price updates with date, quantity and supplier
- Per-product price history charts and recorded purchase transactions
- Gross margin calculations and inventory-at-cost estimate
- Low-stock / low-margin watchlist
- Supplier contact records
- JSON backup/restore and CSV exports
- Offline app shell after first load (service worker)

## Deploy on GitHub Pages
1. Create a **public** GitHub repository named `grocerypulse`.
2. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for the Pages deployment. Your URL will be `https://YOUR-USERNAME.github.io/grocerypulse/`.

## Install on iPhone
1. Open the deployed HTTPS URL in Safari.
2. Tap Share → Add to Home Screen.
3. Name it GroceryPulse and tap Add.
4. Launch from the new Home Screen icon. Open it online once before relying on offline use.

## Important data note
This version stores records in browser localStorage on the device/browser profile. Export JSON backups regularly. It does not sync across devices, authenticate staff, fetch supplier prices automatically, or send push notifications. For shared cloud data, add a hosted database and authentication before multi-user use.

## First use
The initial catalogue is sample/demo data. Edit or delete it and enter your actual products and supplier purchase prices. Currency is INR.
