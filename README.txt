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
