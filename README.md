This repo is set up as a static frontend and, for GitHub Pages, the generated site needs to be emitted into a Pages-ready folder instead of the default `dist/` output.

Build locally with:

npm install
npm run build

Then publish the generated `docs/` directory from the repository settings (GitHub Pages -> Source: Deploy from a branch -> `main`/`master` and `docs/`).

The app itself is a browser game frontend, so it still expects the live Airmash game servers/data feed to be available at runtime.
