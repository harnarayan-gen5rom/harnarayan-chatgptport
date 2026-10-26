# Harnarayan / GEN5ROM — RIFT ENGINE

A complete interactive creative portfolio with **RIFT ENGINE** as the only full-screen 3D experience, transferred from the owner's `PORTFOLIO` repository without modifying it.

## Live

**Vercel production (linked to this repo's `main` branch):**
https://gen5rom-rift-engine-narayan-s-projects-bac03f7f.vercel.app/

Source repository: https://github.com/harnarayan-gen5rom/harnarayan-chatgptport

## Content

- Real interactive Three.js mechanical anomaly with black chrome blades, crimson core, cursor/touch proximity, rupture transformation and in-world 3D featured gallery
- All **34 projects** mirrored from the GEN5ROM archive, with category filters, lazy thumbnails, video playback and full artwork previews
- Work experience at **Zigency (Apr–Sep 2026)**, independent freelance projects (Nov 2025–Apr 2026), **Neofox Media (Aug–Oct 2025)**
- Education: IGNOU B.Sc. (Biology) **pursuing**, design/motion training at DICE Academy
- About, tools, skills, contact and original resume link
- Responsive desktop, tablet and mobile UI; no PRISM FIELD section

## Structure

`index.html` — RIFT hero, experience, skills, work, about, contact and dialogs.  
`rift.js` / `rift.css` — transferred real Three.js implementation and visuals.  
`portfolio.js` / `portfolio.css` — dynamic 34-item archive, filters and responsive presentation.  
`base.css` — shared styles.  
`.github/workflows/validate.yml` — desktop/tablet/mobile smoke tests and source integrity checks.

The original repositories (`PORTFOLIO`, `GEN5ROM`, `GEN5ROM-CYBER`, `Harnarayan5`) are **not modified**.

## Deploying

Push to `main` to automatically deploy through the linked Vercel Git integration.

GitHub Pages isn't activated for this new repository. The GitHub integration cannot create its Pages site (permission denied). To enable that second hosting option, the repository owner must enable Pages and set the source to **GitHub Actions** in GitHub Settings → Pages, then manually run `GitHub Pages (manual, after Pages is enabled)` from the Actions tab. The workflow is not triggered by pushes until hosting is configured.

No secrets or local build step are needed for the static website. The real 3D experience loads Three.js from jsDelivr; the art-directed preview remains if WebGL is unsupported.
