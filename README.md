# MIRAI × AGAMI: Human Power (V8)

An interactive 3D pitch for the Bangladesh–Japan Art Exhibition 2027, by AQUA. It is a static site with no build step.

## Contents

- `index.html`: the experience
- `three.min.js`: Three.js r152, bundled locally
- `assets/`: images and music
- `vercel.json`: hosting headers, with search indexing turned off

## Deploy on Vercel

**Dashboard**
1. Unzip this file.
2. Upload this folder to a new GitHub repository, with `index.html` at the top level.
3. In Vercel, choose **Add New > Project** and import the repository.
4. Set **Framework Preset** to **Other**.
5. Leave the Build Command and Output Directory empty.
6. Click **Deploy**.

**Vercel CLI**
```bash
npm i -g vercel
cd human-power-mirai-agami
vercel        # creates a preview
vercel --prod # publishes to production
```

## Before sharing

- Turn on Vercel Deployment Protection if the link should stay private. The `noindex` header only asks search engines not to list the site. Anyone with the link can still open it.
- Fill in the BDT prices in the AQUA section of `index.html`.
- Confirm you have the rights to `chromatic-waves.mp3` and `cyberpunk-theme.mp3`.
- Get written JTI Legal clearance before sharing the link outside AQUA.

## Controls

- WASD or arrow keys: ride
- Space: hop
- T: auto tour
- C / V: camera mode / Mira front
- N: switch world

Sound starts after the first click, as browsers require.

## Test locally

Run `npx serve .` in this folder. Do not open the page from inside the zip.
