# Domestic Monastic Planner — v2 PWA

This version is ready to be hosted as a web app and added to the iPhone Home Screen.

## Important
An iPhone cannot reliably run the app's JavaScript by simply opening `index.html` from Files. A PWA needs to be served from a web origin; for installability, HTTPS is the normal route. iOS 26 Safari can add sites to the Home Screen as web apps.

## Files
- index.html — app
- manifest.json — app identity/install settings
- sw.js — offline cache
- icons/ — Home Screen icons

## Recommended deployment
Upload this folder to a static HTTPS host such as GitHub Pages, Cloudflare Pages, Netlify, or another static web host. Then open the resulting HTTPS address in Safari and choose Share → Add to Home Screen → Open as Web App.

No database or server-side code is required for the current version; planner data is stored in the browser's local storage.
