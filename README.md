# Sylesh Studio

Staging build of the redesigned website for Shailesh (Sylesh) Joshi: paintings and prints, murals, homes and interiors, custom furniture, biography, timeline and news.

## What is here

- `index.html` is the whole site: one page, with its styles and script inline. Sections are switched by the link hash, for example `#homes` or `#h-la`.
- `img/` holds every artwork and project photograph as WebP, a full-size file and a `-t` thumbnail where the original is large enough.
- `logo/` holds the SJ monogram logo as SVG: the mark, a round seal, and horizontal and stacked lockups. Files ending in `-light` are for light backgrounds; the others are for dark backgrounds. `favicon.svg` is the browser-tab icon.

## Viewing it

Open `index.html` in a browser, or serve the folder with any static host. The fonts load from Google Fonts.

## Before it goes live

- The page carries a staging banner and a "What is still needed" page listing open items. Both should come out at launch.
- `index.html` has a `noindex` tag so search engines skip the staging build. Remove it at launch.
- The contact form is not connected to anything yet.
- Artwork titles, media, sizes and years are still to come from the artist.
