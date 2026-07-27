# FLiPdOuT ProDucTioNz

Premium website repository for the FLiPs Flight Ops Companion launch and future FLiPdOuT releases.

## What this is
This repo contains the static website for FLiPdOuT ProDucTioNz. It is built to showcase the flagship product, media content, and future product releases with a premium launch-page feel.

## Stack
- HTML
- CSS
- JavaScript
- GitHub Pages
- Stripe Checkout

## Features
- Premium landing page.
- Hero section with clear call to action.
- About, gallery, product, and features sections.
- Explainer video support.
- Podcast audio support.
- Mobile hamburger menu.
- Scroll reveal animations.
- Stripe-ready checkout button.

## Folder Structure
- `index.html` — main landing page.
- `assets/css/style.css` — site styles.
- `assets/js/main.js` — navigation and scroll behavior.
- `assets/img/` — images and gallery assets.
- `assets/video/` — explainer video files.
- `assets/audio/` — podcast audio files.
- `.github/workflows/deploy.yml` — GitHub Pages deploy workflow.

## Local Workflow
1. Edit files in Acode.
2. Use Termux to stage, commit, and push.
3. Let GitHub Pages publish the static site.

## Media Notes
- Keep images optimized for web.
- Use `assets/video/` for the explainer video.
- Use `assets/audio/` for the podcast.
- Keep media filenames simple and consistent.

## Deployment
This site is designed for GitHub Pages as a static site. Push changes to the repository and let the workflow publish the latest version.

## Notes
- Keep secrets out of the repo.
- Do not store API keys in frontend files.
- Connect Stripe only after product pricing and checkout flow are finalized.

## Contact
FLiPdOuT ProDucTioNz
