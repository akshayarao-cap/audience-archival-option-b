# Audience Archival – Option B prototype

A click-through design prototype of archive and unarchive in Engage+ Audience Manager.
It's one self-contained static page (`index.html`): there's no build step and no backend,
and all data is held in memory with a "Reset data" control.

## Run locally
Open `index.html` in a browser.

## Deploy
- **Vercel:** import this repo, set Framework preset to "Other", and leave the build
  command empty. Each push to `main` redeploys to the same URL.
- **Netlify:** import this repo with an empty build command and publish directory `.`,
  or drag this folder onto https://app.netlify.com/drop.

## Update
Replace `index.html` with the new export, then commit and push. The live link updates
on push and only on push.
