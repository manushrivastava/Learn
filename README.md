# Learn — Dr. Manu Shrivastava

Landing page for Dr. Manu Shrivastava (Assistant Professor, Manipal University Jaipur), linking out to
course resource sites:

- Design & Analysis of Algorithms — https://daa.shrivastavamanu.co.in
- Advanced Data Structures — https://ads.shrivastavamanu.co.in
- Relational Database Management Systems — https://rdbms.shrivastavamanu.co.in

## Structure

- `index.html` — the whole page (hero + scroll-reveal course cards + footer), CSS and JS inline.
- `assets/landing_page.png` — hero banner image.
- `assets/logos/*.svg` — placeholder logos for each course card (see below).

## Replacing the placeholder logos

`assets/logos/daa-logo.svg`, `ads-logo.svg`, and `rdbms-logo.svg` are simple generated
placeholders in the hero image's color palette. To use your own logos:

1. Drop your image in `assets/logos/` (PNG, SVG, or JPG all work).
2. Update the matching `<img src="...">` in `index.html` to point to the new filename.

## Deploying on Vercel

This is a static site with no build step. In Vercel, just import this repo and deploy with
the default settings (framework preset: "Other" / no build command, output directory: `/`).
