# ysawiris.github.io

Personal portfolio for Youssef Sawiris — engineer (ex-Strava) and 6th grade math teacher (Lodestar, East Oakland).

Built with [Astro](https://astro.build). Deployed to GitHub Pages via Actions.

## Local development

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # builds to dist/
npm run preview  # preview the production build
```

## Deploy

Pushes to `main` trigger `.github/workflows/deploy.yml`, which builds with Astro and publishes to GitHub Pages.

## Adding content

- New engineering project → add a section to `src/pages/engineering.astro` (will move to content collections when the list grows past ~12).
- New teaching artifact → add a section to `src/pages/teaching.astro`.
- Resume / PDFs → `public/resume/` — link from the home page.
