# strawdogsdev.com

Marketing site for Straw Dogs LLC — a boutique ghostwriting and authority architecture firm for hybrid publishers.

Built with [Astro](https://astro.build/) + [Tailwind CSS v4](https://tailwindcss.com/), deployed to Netlify.

## Local development

```sh
npm install
npm run dev
```

The dev server runs on http://localhost:4321 by default.

## Build

```sh
npm run build
```

Output is written to `dist/`.

## Deploy

The site auto-deploys to Netlify on every push to `main`. Custom domain: strawdogsdev.com.

## Structure

- `src/layouts/BaseLayout.astro` — meta tags, fonts, scroll-reveal observer
- `src/components/` — one component per page section
- `src/pages/index.astro` — composes the single-page site
- `src/styles/global.css` — color palette and typography in Tailwind `@theme`
- `public/` — static assets (favicon, images, `_redirects`)
- `netlify.toml` — build & headers config

## Brand family

- [platteclark.com](https://platteclark.com) — the principal's site
- [authorunknown.fm](https://authorunknown.fm) — the podcast
