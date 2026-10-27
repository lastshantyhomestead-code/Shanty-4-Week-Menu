CHEFFY CLASSIC — REFINED FOUR ROTATIONS (2026-10-26)
- Existing A/B preserved. C/D regenerated to reduce overlapping dinners and vary baked snacks and salads.

WHAT CHANGED
- Rotation tabs A, B, C and D, with 4 weeks per rotation (16 complete weeks).
- Rotation A preserved from the existing app.
- Rotation B synced to the latest edited menu master.
- Rotations C and D refined: only three common flexible dinners, new unused indexed recipes, new salads and baking combinations, refreshed C/D lunch & breakfast patterns.
- Grocery tabs C/D rebuilt from the selected recipes, Wednesday pizza dough, weekly salad/baking, basic breakfasts and extra vegetable snacks. Shopping quantities are estimates to verify against actual recipe cards; no prices.
- Clickable recipe cards updated from Cheffy Recipe Master, including complete Wednesday pizza dough instructions.
- Sunday / Weekly Prep remains prominent above each menu.
- Rejected Thai sweet potato burgers removed. Retired recipes are retained in the archive only.
- No external APIs, pricing services, accounts or subscriptions.

TO UPDATE YOUR EXISTING GITHUB PAGES SITE
1. Save a separate copy of your current working Cheffy files/site first.
2. Extract this ZIP. Upload all seven files to your CURRENT Cheffy GitHub Pages repository root (replace existing files with the same names).
3. Wait until GitHub Pages shows your changes. Refresh your app/site; on a phone you may need to close and reopen it.
4. Because the offline service worker cache version has changed, the latest pages should update on the next online visit. If the old view persists, refresh again once or clear site cache.
5. Check all A, B, C and D tabs, Week 1–4, a Wednesday pizza recipe and the grocery check-off.

IMPORTANT
- This update uses the existing app's local storage. Your checked-off grocery items and rotation selections remain on your device where IDs are unchanged, but updated grocery lists can introduce new items.
- Editing an Excel master later will NOT automatically update this static app; export a new app build.
- Do not replace this version with experimental Cheffy 2.0; archive Classic separately first.

CHEFFY CLASSIC — FOUR ROTATIONS (2026-10-26)

WHAT CHANGED
- Rotation tabs A, B, C and D, with 4 weeks per rotation (16 complete weeks).
- Rotation A preserved from the existing app.
- Rotation B synced to the latest edited menu master.
- Rotations C and D added from the four-rotation Cheffy Menu Master.
- Grocery tabs synced to the four-rotation Cheffy Grocery Master. Quantities are estimates, not prices.
- Clickable recipe cards updated from Cheffy Recipe Master, including complete Wednesday pizza dough instructions.
- Sunday / Weekly Prep remains prominent above each menu.
- Rejected Thai sweet potato burgers removed. Retired recipes are retained in the archive only.
- No external APIs, pricing services, accounts or subscriptions.

TO UPDATE YOUR EXISTING GITHUB PAGES SITE
1. Save a separate copy of your current working Cheffy files/site first.
2. Extract this ZIP. Upload all seven files to your CURRENT Cheffy GitHub Pages repository root (replace existing files with the same names).
3. Wait until GitHub Pages shows your changes. Refresh your app/site; on a phone you may need to close and reopen it.
4. Because the offline service worker cache version has changed, the latest pages should update on the next online visit. If the old view persists, refresh again once or clear site cache.
5. Check all A, B, C and D tabs, Week 1–4, a Wednesday pizza recipe and the grocery check-off.

IMPORTANT
- This update uses the existing app's local storage. Your checked-off grocery items and rotation selections remain on your device where IDs are unchanged, but updated grocery lists can introduce new items.
- Editing an Excel master later will NOT automatically update this static app; export a new app build.
- Do not replace this version with experimental Cheffy 2.0; archive Classic separately first.

CHEFFY — APPLE + ANDROID + GROCERY LIST

This build starts from the stable Apple + Android Rotation A/B version.

NEW GROCERY FEATURE
- A Grocery List button appears before Sunday / Weekly Prep.
- The grocery list automatically follows the selected Rotation and Week.
- Items are grouped in store-friendly sections:
  Produce
  Bakery & Bread
  Refrigerated
  Canned & Jarred
  Pantry & Dry Goods
  Baking & Treats
  Frozen & Protein
  Breakfast & Bulk
  Other
- OPTIONAL items remain visible in the active list and are labelled Optional.
- Pantry/staple items remain visible and are labelled Check pantry or Staple.
- Tap any item you already have or have picked up and it disappears from Remaining.
- Done / Undo keeps every removed item so it can be restored.
- Restore all items resets that week.
- Grocery progress is saved separately for each Rotation + Week on that device.
- Old HAVE values in Rotation A are treated as Check pantry so an old shopping session does not falsely assume those items are still in stock.

UPLOAD THESE EXACT FILENAMES TO THE SAME GITHUB PAGES FOLDER:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png
- README.txt (optional)

There is still NO data.js dependency.
An old data.js in GitHub will not affect this build.

After uploading, commit the files and allow GitHub Pages to redeploy.
The service-worker cache is now cheffy-v6-grocery.
