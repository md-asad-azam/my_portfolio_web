# Portfolio Website

Personal portfolio built with Astro, React islands, Tailwind CSS, Framer Motion, and Three.js.

## Tech Stack

- **Astro** — static-first site framework
- **React** — interactive islands (hero animation, particle background, scroll reveals)
- **Tailwind CSS** — styling
- **Framer Motion** — animations and scroll-triggered transitions
- **Three.js / React Three Fiber** — 3D particle background
- **Lenis** — smooth scrolling

## Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/md-asad-azam/my_portfolio_web.git
cd my_portfolio_web
npm install
```

Run the dev server:

```bash
npm run dev
```

Site runs at `http://localhost:4321`.

## Build

```bash
npm run build      # outputs to dist/
npm run preview    # preview the production build locally
```

## Project Structure

```
src/
├── components/     # Astro + React components
├── layouts/        # Base page layout
├── pages/          # Routes (index.astro)
├── styles/         # Global CSS
└── data/           # Project content (projects.ts)
```

## Deployment

Deployed on Vercel — auto-deploys on push to `main`.

## Inspiration

- [brittanychiang.com](https://brittanychiang.com/)
- [lenis.dev](https://lenis.dev/)
---