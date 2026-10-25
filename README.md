# Kodofy

Kodofy is a developer-focused landing page builder demo built with React, Vite, and Tailwind CSS. It includes a marketing homepage and a simple editor for adding and arranging page components.

## Live site

https://prabin-00.github.io/kodofy-website-builder/

## Requirements

- Node.js 20 or later
- npm

## Run locally

From the repository root, install dependencies and start the development server:

```bash
npm install
npm run dev
```

Vite serves the app at http://localhost:3000/.

## Build and preview

```bash
npm run build
npm run preview
```

## Project structure

- `kodofy-clone/src/pages/Home.jsx` - landing page
- `kodofy-clone/src/pages/Editor.jsx` - page editor demo
- `kodofy-clone/src/components/` - shared navigation and footer
- `kodofy-clone/src/index.css` - global styles and Tailwind directives
- `.github/workflows/deploy.yml` - builds and deploys the site to GitHub Pages on pushes to `main`

## Deployment

GitHub Pages must be enabled for the repository with **Build and deployment > Source** set to **GitHub Actions**. Pushing to `main` runs the deployment workflow automatically.
