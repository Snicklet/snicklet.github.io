# Snicklet website

Official landing page for **Snicklet**, a visual-first DevOps IDE.

## Development

Requires Node.js 24.

```bash
npm install
npm run dev
npm run build
```

Built with Astro and plain CSS. The build is static and targets the organization site at https://snicklet.github.io/.

## Design

- Product UX reference: `Snicklet/Snicklet` → `DESIGN.md` and `src/app/styles.css`
- Brand source of truth: private `Snicklet/brand-assets` repository
- Only web-required, approved brand exports are copied into `public/brand/`.
- The hero preview is explicitly a placeholder until an approved, genuine Snicklet screenshot is available.
- This repository contains the website source; it is **not** the IDE source code.

## Deployment

Pull requests run a build check. Pushes to `main` build and deploy to GitHub Pages after configuring **Settings → Pages → Source → GitHub Actions**.

No production publishing is intended before design review and merge.
