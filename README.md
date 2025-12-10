# QR Code Generator (static)

This is a small static webpage that generates QR codes client-side from any text or URL and lets the user download the PNG.

How to use
1. Place `index.html` at the root of your repository (for example `dimasad/caex-qrcode`).
2. Push to the default branch (usually `main` or `master`).
3. Enable GitHub Pages for the repository (Repository Settings → Pages) or rely on the automatic default workflow — when served from the repository root it will be available at:
   `https://<your-username>.github.io/<your-repo>/`
   Example test URL: https://dimasad.github.io/caex-qrcode/

Notes
- The generator runs entirely in the browser; no server-side processing or special deployment steps are required.
- The page uses a small QR code library loaded from the jsDelivr CDN (qrcode 1.5.1). If you prefer no external dependencies, replace the CDN script with a local copy of the library.

Customization ideas
- Add SVG export
- Add custom foreground/background colors
- Add logo overlay (be careful with error correction level)
- Persist recent values in localStorage

License
- You can use and modify this freely in your repository.

Attribution

This project was adapted from work by Dimas Abreu Archanjo Dutra:
<https://github.com/dimasad/caex-qrcode?tab=MIT-1-ov-file>

Original code and assets are licensed under the MIT License (see LICENSE).
Modifications and hosting by Gage Beeman (https://github.com/gage-beem).
