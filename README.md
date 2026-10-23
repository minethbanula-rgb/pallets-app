# pallets.app

Minimal mobile-first, privacy-friendly color palette generator. Runs fully in the browser, no backend required.

## Features
- Upload from gallery or capture from mobile camera
- K-means color extraction, proportional mosaic
- Tap a swatch to copy HEX
- Regenerate palette
- Export 1080×1920 Instagram Story PNG
- Native sharing when supported

## Deploy to GitHub Pages
Create a public repository, upload `index.html`, then go to Settings → Pages → Deploy from a branch → main / root.

Note: This is an MVP. Proportions are based on clustered pixel frequencies; the three-row visual layout is stylized and not a mathematically exact treemap. Camera input behavior depends on browser support.
