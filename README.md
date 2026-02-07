# debitlens-site

Landing and legal pages for DebitLens.

Design assets from pre-beta exploration live in `/design/lovable-assets/`. They are intentionally not integrated into the beta builds and will be reviewed post-beta once core UX is validated.

## Icons

The site expects these icon files (referenced in `index.html` and `site.webmanifest`):

- **favicon.ico** — Fallback favicon (e.g. 32×32). Many tools accept `favicon.svg` and export ICO.
- **apple-touch-icon.png** — 180×180 PNG for “Add to Home Screen” on iOS.

To generate them from `favicon.svg` or `logo.svg`:

- [RealFaviconGenerator](https://realfavicongenerator.net/) — upload the SVG, download a package with ICO, PNG, and optional manifest tweaks.
- Or export from Figma/Illustrator/Inkscape (e.g. 32×32 for ICO, 180×180 for Apple touch icon).
