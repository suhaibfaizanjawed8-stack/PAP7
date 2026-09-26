# Prince Art Packages website

Deploy-ready, dependency-free multi-page website for Prince Art Packages (Private) Limited.

## Install and run locally

```sh
npm install
npm test
npm start
```

Open `http://127.0.0.1:4173/` after starting the preview.

## Production build

```sh
npm run build
```

The production website is generated in `dist/`. All routes are real directories with their own `index.html`, so direct visits and refreshes work without SPA rewrites.

## Deploy to Vercel

1. Push this complete project to a GitHub repository or import the project folder directly in Vercel.
2. Vercel reads `vercel.json`, runs `npm run build`, and publishes `dist/`.
3. No environment variables or external image hosting are required.

The same folder is GitHub-ready. Keep `package.json`, `vercel.json`, `src/`, `scripts/` and the included image assets together.

Photography sources and licenses are documented in `IMAGE-SOURCES.md`.
