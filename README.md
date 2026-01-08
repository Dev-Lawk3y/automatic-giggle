# GoatBot — Colourful Landing (Red → Black → Green)

A simple Node.js + Express site that serves a small static landing page with a colourful gradient, ready to deploy on Render.

Contents:
- server.js — Node/Express server
- public/ — static site (index.html, styles.css, script.js)
- package.json
- render.yaml (optional Render config)

## Requirements
- Node.js (v18+ recommended)
- npm

## Run locally
1. Install deps:
   npm install

2. Start server:
   npm start

3. Open http://localhost:3000

## Deploy on Render
1. Push this repo to GitHub (or connect an existing repo).
2. Create a new Web Service on Render:
   - Connect your GitHub repo
   - Set Environment: Node
   - Build command: `npm install`
   - Start command: `npm start`
   - (If you included `render.yaml`, Render can auto-provision the service using that file.)
3. Deploy and visit the provided Render URL.

## Customize
- Change colors in `public/styles.css` under `:root` variables:
  --red, --black, --green
- Replace the SVG logo in `public/index.html`.
- Add pages to `public/` and update navigation.

## Notes
- Server listens on `process.env.PORT` (Render supplies that).
- Static files are served from `/public`.
- For custom domain and HTTPS, configure in Render dashboard.

Built by Lawkey Marvelous.

# automatic-giggle
Just a test web
