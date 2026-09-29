CHEFFY STABLE ROTATION A + B PWA

This rebuild intentionally DOES NOT use data.js.
All menu and recipe data is embedded inside index.html so a mixed or missing data.js cannot break the app.

FILES THAT MUST BE IN THE GITHUB PAGES FOLDER WITH THESE EXACT NAMES:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

IMPORTANT BEFORE DEPLOYING:
1. Replace the old files with these exact filenames.
2. Delete or ignore duplicate files such as index(2).html, manifest(2).json, service-worker(2).js, icon-192(1).png, icon-512(1).png.
3. The old data.js is no longer used and can be deleted from the repo to avoid confusion.
4. Commit the changes.
5. Let GitHub Pages deploy.
6. Open the web URL in Chrome and refresh once.
7. Fully close the installed Cheffy app and reopen it.

WHAT IS INCLUDED:
- Rotation A Weeks 1–4
- Rotation B Weeks 1–4
- Rotation selector
- Breakfast / lunch / dinner tappable recipe cards
- Weekly salad tappable recipe card
- Weekly baking/snack tappable recipe card
- Rotation B prep recipes tappable where applicable
- Rotation B Emergency Easy recipe tappable
- Ingredients / Instructions tabs
- Offline support
- Update-friendly network-first service worker

WHY THE PREVIOUS DEPLOYMENT COULD BREAK:
- index.html depended on a separate data.js.
- A new index with an old data.js creates a schema mismatch.
- Duplicate filenames like index(2).html are not the same as index.html.
- The old cache-first service worker could continue serving older files.
