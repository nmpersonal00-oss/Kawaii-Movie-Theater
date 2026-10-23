# Pink Premiere & Pearly Popcorn — Cozy Twilight (Icon Ready)

Includes your existing Version 4 theater app **unchanged except for icon/head metadata**.
The JavaScript, forms, database configuration, reviews, curtains and sounds are identical to Version 4.

## Included
- `index.html` — the entire app, with site icon references
- `favicon.ico` and `favicon-32.png` — browser tabs/bookmarks
- `apple-touch-icon.png` — iPhone/iPad Add to Home Screen
- `icon-192.png` and `icon-512.png` — installable app icons for browsers/Android
- `manifest.webmanifest` — names, display mode, icon discovery

## GitHub Pages steps
Create a **new** repository for this entertainment app. It must not be uploaded over your closet repository.
Extract this ZIP. Upload all **seven files** to the **repository root**, next to each other (not the ZIP and not the outer folder). In repository Settings > Pages use main / (root).
After deployment, open the new site in Safari, choose Share > Add to Home Screen. In Chrome, bookmark or install from the published address.
If an existing shortcut displays an old image, remove just the shortcut, reopen the published site, and add it again. That does not delete entries stored in Supabase.

Notes: image refs are relative (`./...`) and work with any GitHub Pages repository path. A manifest helps modern browsers select icons; browser caches may delay an update. Cross-device shared data still requires both people to sign into the same cloud account.
