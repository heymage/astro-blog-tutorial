# heyastro 🚀 Blog Tutorial

[![Netlify Status](https://api.netlify.com/api/v1/badges/b797d2bb-37b9-4d9c-bb05-18d188291417/deploy-status)](https://app.netlify.com/sites/heyastro/deploys)

```
npm create astro@latest -- --template minimal
```

## 🚀 Project Structure

Inside your Astro project, you'll see the following folders and files:

```
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command              | Action                                           |
|:---------------------| :----------------------------------------------- |
| `pnpm install`       | Installs dependencies                            |
| `pnpm dev`           | Starts local dev server at `localhost:3000`      |
| `pnpm build`         | Build your production site to `./dist/`          |
| `pnpm preview`       | Preview your build locally, before deploying     |
| `pnpm astro ...`     | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro --help`  | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
