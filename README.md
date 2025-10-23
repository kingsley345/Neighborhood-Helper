# Neighborhood Helper — Local Demo

This is a single-file demo app (plus images) that stores data in your browser's localStorage.

How to view

1. Open `Neighborhood Helper.html` in your browser (double-click or right-click → Open with → Browser).
2. Use the navigation links at the top. The app is fully client-side — no server required.

Quick tests

- Home: View Related Carers; clicking a carer will open the Profile view for that helper.
- Profile: Add a helper (with an optional photo). Use Edit/Delete next to a helper to modify or remove them.
- Work History: Add an entry for a selected helper with an optional photo. Edit/Delete work entries.
- Helpers: View all helpers; click View to open their profile.

Notes

- Images are stored as data URLs in localStorage (convenient demo but limited by browser storage quotas).
- If you need persistent or large-image storage, consider using a backend or IndexedDB.

Enjoy — let me know if you want an index.html wrapper or a small local server script to serve this file.