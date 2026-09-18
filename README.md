# PackMe v5

Mobile-first PWA for smart travel packing checklists.

## GitHub Pages
Upload **all files inside this folder** to the root of a GitHub repository, then enable GitHub Pages from the repository's Settings → Pages → Deploy from branch.

Important: upload `index.html`, `app.js`, `styles.css`, `sw.js`, and `manifest.webmanifest` at the repository root — not inside an extra `packme` folder.

## v4 fix
The navigation and “Neue Reise” button now use robust event delegation instead of inline JavaScript handlers. The service worker cache was also versioned so old broken JavaScript is not reused.
