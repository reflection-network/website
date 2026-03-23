# website

Landing page for Reflection Network at [reflection.network](https://reflection.network).

## What it does

A single-page Astro site that introduces Reflection: what capsules are, how agents are defined as Git repos with Nix config, and links to docs and GitHub. Includes PostHog analytics.

## Development

```bash
npm install          # install dependencies
npm run dev          # start local server at localhost:4321
```

## Building

```bash
npm run build        # build to dist/
npm run preview      # preview production build
```

## Deployment

Pushes to `main` trigger GitHub Actions, which builds and deploys to GitHub Pages with the `reflection.network` CNAME.

## Live site

[reflection.network](https://reflection.network)
