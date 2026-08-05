# Prabhaav Pillai — Portfolio

A fast, static, single-page portfolio built with [Astro](https://astro.build). Showcases projects, papers, and a resume, and is deployed to GitHub Pages via GitHub Actions at a custom domain (`prabhaav.me`).

## What it uses

- **Astro** — static, prerendered output
- **TypeScript / CSS** — custom components (`ProjectCard`, `PaperCard`) and a hand-written stylesheet with a blurred background layer controlled by CSS variables
- **GitHub Actions** — builds and deploys to GitHub Pages on every push to `main`
- **Custom domain** — `prabhaav.me` via a `public/CNAME` file

## 🚀 Project Structure

```text
/
├── public/            # Static assets: images, papers, resume.pdf, CNAME
├── src/
│   ├── components/    # ProjectCard.astro, PaperCard.astro
│   ├── layouts/       # Layout.astro
│   ├── pages/         # index.astro
│   └── styles/        # global.css
├── .github/
│   └── workflows/     # deploy.yml (GitHub Pages)
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
