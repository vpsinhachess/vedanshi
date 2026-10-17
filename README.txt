VEDANSHI'S FUN WORLD — INSTALLABLE WEB APP (PWA)

Upload these items to the root of https://vpsinhachess.github.io/vedanshi/:
- index.html (replace the current homepage)
- manifest.webmanifest
- sw.js
- icons/ (upload the complete folder and its three PNG icons)

Commit the changes and wait for GitHub Pages to publish. Then open the site in Chrome on Android and reload. The page includes an Install App button when Chrome exposes the install prompt. Chrome's ⋮ menu may also show Install app / Add to Home screen.

A webpage cannot silently install an app; the visitor must approve the browser prompt. The homepage shell is cached for offline opening, but the linked games are separate pages and may still require internet unless each game also has offline support. Keep the supplied relative paths because the site is hosted under /vedanshi/.
