# Andrea Gherardi — Portfolio

Portfolio personale sviluppato con [Astro](https://astro.build) e [Tailwind CSS v4](https://tailwindcss.com).

## Stack

- **Astro 6** — static site generator
- **Tailwind CSS v4** — styling via `@tailwindcss/vite`
- **Deploy** — [Netlify](https://netlify.com)

## Sviluppo locale

Richiede Node.js ≥ 22.

```bash
npm install
npm run dev
```

Il sito sarà disponibile su `http://localhost:4321`.

## Build

```bash
npm run build
npm run preview  # anteprima della build statica
```

## Deploy

Il deploy avviene automaticamente su Netlify ad ogni push sul branch `main`. La configurazione è in `netlify.toml`.
