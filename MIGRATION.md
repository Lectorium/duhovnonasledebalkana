# Static migration — 26 November 2026

75 public WordPress pages copied, 25 per language (Italian, English, Serbian Cyrillic). Links preserve the original page hierarchy and use relative paths, so this directory works with GitHub Pages or Cloudflare Pages on a custom domain. Text and external references have been retained; the original header, emblem and color palette have been adapted to static HTML and CSS. No draft or password-protected pages or comments were imported.

The test copy uses a noindex metadata tag until a final domain is selected. All 14 public images are stored locally in assets/media as optimized display copies, including the emblem and book covers; `media-sources.json` records the original URLs and local paths. No image is fetched from WordPress at page load. Image captions and attribution remain in the page content; see MEDIA-CREDITS.md for provenance. Contact pages link to the original WordPress form rather than displaying an inactive form. No WordPress administration functionality is included. The original WordPress site has not been changed.

GitHub Pages settings: deploy from branch main, folder / (root). Cloudflare direct upload: use the repository contents as the site output directory, no build command required.
