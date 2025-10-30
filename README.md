# Minimal Portfolio — Clean, simple, beginner-friendly

This repository is intentionally minimal — a tiny, well-structured portfolio starter for beginners that prioritizes clean code and readability over bells and whistles.

Key ideas:

- Minimal by design: a single page with clear semantic sections (Intro, Projects, Contact).
- Clean-code friendly: small components, explicit names, no global state or complicated build steps.
- Beginner-first: easy to edit, easy to extend — replace text and links and you're ready to go.

## Live demo

This site is deployed on Vercel: https://portfolio-yettabaas-projects.vercel.app/

## Quick start

1. Install dependencies
2. Run the dev server

```bash
npm install
npm run dev
```

Open http://localhost:3000 and edit files under `src/`.

## What to edit

- `src/pages/home.tsx` — main content and sections.
- `src/components/` — small UI pieces (feel free to remove or simplify further).
- `src/assets/global.css` and `tailwind.config.js` — styling tokens.

## Keeping it minimal

If you want to reduce this project to the absolute minimum, consider:

- Removing unused components in `src/components/`.
- Deleting sample data in `src/data/` (for example `repos.json`) if you don't use it.
- Removing unnecessary dependencies from `package.json`.

## Deployment

- Vercel (recommended for simplicity): connect your GitHub repo and deploy — the defaults work for this Vite app.
- The app is already deployed here: https://portfolio-yettabaas-projects.vercel.app/

## Notes for maintainers

- Goal: keep public surface area tiny and code easy to read.
- Prefer editing `src/pages/home.tsx` for content changes and keep components focused.

## License

MIT — use and modify freely.
