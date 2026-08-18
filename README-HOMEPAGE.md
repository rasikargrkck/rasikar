# Rasika Rathnayake homepage package

This folder contains drop-in replacement files for the existing Astro website.

## Replace these files

- `src/pages/index.astro`
- `src/layouts/BaseLayout.astro`
- `src/styles/global.css`

## Add these assets

- `public/images/rasika-hero-tshirt-natural.png`
- `public/images/protein-signaling.svg`
- `public/images/neuron-cell.svg`
- `public/files/Rasika_Rathnayake_CV_May_2026.pdf`

## Test in GitHub Codespaces

```bash
npm run build
npm run dev -- --host 0.0.0.0
```

Open the forwarded port at `/rasikar/`.

## Publish

```bash
git add src public
git commit -m "Build dark professional homepage"
git push
```

The GitHub Actions deployment will publish the update automatically.
