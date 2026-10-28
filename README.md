# PickleCut website

Official PickleCut marketing site: https://picklecut.goswie.com

Based on AceCut’s editorial website layout, with native PickleCut artwork, blue/yellow branding, genuine pickleball footage and a development-app Studio screenshot. Media attribution: `/credits`. Product availability is explicitly in development; no App Store link is fabricated. Existing account/OAuth website remains separate.

## Local development

Requires Bun >=1.2.0.

```sh
bun install
bun run dev
bun run build
bun run preview
```

Preview: http://127.0.0.1:4173 (override with PORT). Static source in `public/`, output in `dist/`. No runtime dependencies, tracking scripts or secrets. Terms and Privacy retain the existing PickleCut account site’s product-specific content.

## Deployment

Vercel project `picklecut-website`, team `diifans-projects`, GitHub `diifan/picklecut-website`, production branch `main`. Root `./`, framework Other, install `bun install`, build `bun run build`, output `dist`. Domain `picklecut.goswie.com`.

## Validation

Build and browser checks cover home, legal and attribution pages; 320/390/768/1440 px layouts, image loading, internal links, FAQ expansion and horizontal overflow. Review screenshots are stored outside the repository.

## 2026-10-29 visual refinement

Removed decorative arrows, added the AceCut envelope icon to every footer, and replaced hero/closing CTAs with App Store badges styled in the app’s own colors. Brand links do not underline on hover. Until a verified app listing is available, badges use the App Store search URL (as on AceCut); development availability disclosures remain. Replace search targets with the verified app ID at launch.
