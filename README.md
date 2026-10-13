# Sylesh Studio

Staging build of the redesigned website for Shailesh (Sylesh) Joshi: paintings and prints, murals, homes and interiors, custom furniture, biography, timeline and news.

## What is here

- `index.html` is the whole site: one page, with its styles and script inline. Sections are switched by the link hash, for example `#homes` or `#h-la`.
- `img/` holds every artwork and project photograph as WebP, a full-size file and a `-t` thumbnail where the original is large enough.
- `logo/` holds the SJ logo as SVG. The round seal is the main logo (`seal-badge.svg` carries its own dark disc); there are also the monogram alone, and horizontal and stacked lockups. Files ending in `-light` are for light backgrounds; the others are for dark backgrounds. `favicon.svg` is the browser-tab icon.

## Viewing it

Open `index.html` in a browser, or serve the folder with any static host. The fonts load from Google Fonts.

## Before it goes live

- The footer links to an "Open items" page listing what is still needed. It should come out at launch.
- `index.html` has a `noindex` tag so search engines skip the staging build. Remove it at launch.
- The contact form is not connected to anything yet.
- Artwork titles, media, sizes and years are still to come from the artist.
