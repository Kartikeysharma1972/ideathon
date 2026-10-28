# Ideathon 2026: brochure QR link

The brochure QR code always opens **https://kartikeysharma1972.github.io/ideathon/**.
That page immediately forwards visitors to the current destination, so the printed QR never needs to change.

## Change where the QR goes

1. Open `index.html` (on GitHub: click the file, then the pencil icon).
2. Replace the URL after `url=` on the line marked `THE BROCHURE QR CODE OPENS THIS PAGE`.
3. Commit. The new destination is live within a few minutes (GitHub Pages caches for up to 10 minutes).

Do not rename or delete this repository, rename the GitHub account, or turn off GitHub Pages. Any of these breaks every printed QR code.

## What's here

- `index.html`: the redirect (the only file the QR depends on)
- `site/`: the built Ideathon 2026 website, copied from the `ideathon-2026` project's `dist/` folder. To update it, copy `dist/` over `site/` again and push.
- `qr/`: print files for the QR code (SVG for print, PNG for screens)
