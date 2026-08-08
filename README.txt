Version 22 — cleanup/migration for duplicate Do Not Work areas.

Important:
- On startup, duplicate/overlapping Do Not Work polygons left by older versions are automatically consolidated.
- A user-named area is preferred over a generic "Do Not Work Area N".
- Only one permanent center label is created for each remaining area.
- Center label uses the polygon centroid rather than a simple vertex average.
- Removed obsolete editor code that hard-coded Republic/Cardale.
- Cancel/Save rebuilds DNW layers and labels cleanly.
- Houses button remains an action button: visible -> Houses OFF; hidden -> Houses ON.
