# PokeBinder viewer

Static client-only viewer for shared PokeBinder snapshots. Open a share link or load an exported HTML file locally. No accounts, analytics, database or uploaded collection data. Card art belongs to its respective owners.

Links contain compressed binder data in the URL fragment. Anyone with a link can read and forward it. The fragment is not sent in the page request. Linked artwork loads from approved image providers; HTML exports embed available cached art for offline use. Private costs, notes and certificate numbers are excluded by the app; market values are opt-in.

This repository contains only the viewer, not the Android app source. The canonical template is app/src/main/assets/binder-viewer.html in the app repository. When updating it, copy that file to index.html here and commit; GitHub Pages publishes main/root. Test both embedded JSON and compressed links before publishing.
