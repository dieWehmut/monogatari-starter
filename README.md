# monogatari-starter

Static frontend starter for a Monogatari story/capture site.

## Deploy

This template deploys with GitHub Pages Actions. The default build is a pure frontend story site:

- `VITE_STATIC_STORY=true`
- login entry points hidden
- capture comments configured through Giscus variables

Set these repository variables when you want capture comments:

- `VITE_CAPTURE_GISCUS_REPO`
- `VITE_CAPTURE_GISCUS_REPO_ID`
- `VITE_CAPTURE_GISCUS_CATEGORY`
- `VITE_CAPTURE_GISCUS_CATEGORY_ID`

Optional variables include `VITE_CAPTURE_GISCUS_MAPPING`, `VITE_CAPTURE_GISCUS_STRICT`,
`VITE_CAPTURE_GISCUS_REACTIONS_ENABLED`, `VITE_CAPTURE_GISCUS_INPUT_POSITION`,
`VITE_CAPTURE_GISCUS_THEME`, and `VITE_CAPTURE_GISCUS_LANG`.

Put capture assets in an external assets repository or edit `src/data/capture/manifest.json`.
The starter intentionally ships without the author's personal capture database.
