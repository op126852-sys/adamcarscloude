# Adam Cars

A private, single-file luxury automotive showroom site.

## Features
- Interactive 3D car configurator built with Three.js — drag to rotate, live paint swatches
- Live animated canvas background (drifting light-streak particles)
- Fully responsive, accessible layout that respects `prefers-reduced-motion`
- Front-end "Request a Private Viewing" form (no backend wired up yet)

## Run locally
Just open `index.html` in a browser. No build step, no dependencies to install.

## Deploy
Static site, zero config, deploys anywhere:

**Vercel**
```bash
npm i -g vercel
vercel --prod
```
or drag the folder onto https://vercel.com/new — Hobby plan by default.

**Netlify / GitHub Pages** also work out of the box.

## Stack
- Three.js (r128) via CDN — no bundler
- Vanilla HTML / CSS / JS
- Google Fonts: Big Shoulders Display, Inter, JetBrains Mono

## Roadmap
- Wire the viewing-request form to email or a Supabase table
- Swap the procedural low-poly car for an imported GLTF model
