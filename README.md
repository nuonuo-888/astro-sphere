![Astro Sphere Lighthouse Score](_astrosphere.jpg)

Astro Sphere is a static, minimalist, lightweight, lightning fast portfolio and blog theme based on my personal website.

It is primarily Astro, Tailwind and Typescript, with a very small amount of SolidJS for stateful components.

## 🚀 Deploy

[![Deploy to Tencent EdgeOne Pages](https://img.shields.io/badge/Deploy-Tencent%20EdgeOne%20Pages-006EFF?style=for-the-badge&logo=tencentqq&logoColor=white)](https://edgeone.ai/pages/new?template=https%3A%2F%2Fgithub.com%2Fnuonuo-888%2Fastro-sphere&output-directory=dist%2Fclient&build-command=npm+run+build&install-command=npm+install&origin_from=childtom)

The one-click button above clones `nuonuo-888/astro-sphere`, installs dependencies with `npm`, runs `npm run build`, and serves the generated `dist/client/` folder automatically on Tencent EdgeOne Pages.

## 👁 Preview

[![Preview](https://img.shields.io/badge/Preview-4ECCA3?style=for-the-badge&logo=globe&logoColor=white)](https://astro-sphere.edgeone.app/)

## 📋 Features

- ✅ 100/100 Lighthouse performance
- ✅ Responsive
- ✅ Accessible
- ✅ SEO-friendly
- ✅ Typesafe
- ✅ Minimal style
- ✅ Light/Dark Theme
- ✅ Animated UI
- ✅ Tailwind styling
- ✅ Auto generated sitemap
- ✅ Auto generated RSS Feed
- ✅ Markdown support
- ✅ MDX Support (components in your markdown)
- ✅ Searchable content (posts and projects)
- ✅ Code Blocks - copy to clipboard

## 💯 Lighthouse score

![Astro Sphere Lighthouse Score](_lighthouse.png)

## 🕊️ Lightweight

All pages under 100kb (including fonts)

## ⚡︎ Fast

Rendered in ~40ms on localhost

## 📄 Configuration

The blog posts on the demo serve as the documentation and configuration.

## 💻 Commands

All commands are run from the root of the project, from a terminal:

Replace npm with your package manager of choice. `npm`, `pnpm`, `yarn`, `bun`, etc

| Command                   | Action                                            |
| :------------------------ | :------------------------------------------------ |
| `npm install`             | Installs dependencies                             |
| `npm run dev`             | Starts local dev server at `localhost:4321`       |
| `npm run dev:network`     | Starts dev server on local network                |
| `npm run sync`            | Generates TypeScript types for all Astro modules. |
| `npm run build`           | Build your production site to `./dist/`           |
| `npm run preview`         | Preview your build locally, before deploying      |
| `npm run preview:network` | Starts preview server on local network            |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check`  |
| `npm run astro -- --help` | Get help using the Astro CLI                      |
| `npm run lint`            | Run ESLint                                        |
| `npm run lint:fix`        | Auto-fix ESLint issues                            |

## 🗺️ Roadmap

A few features I plan to implement

- ⬜ Article Pages - Table of Contents
- ⬜ Article Pages - Share on social media

## ✨ Acknowledgement

Theme inspired by [Paco Coursey](https://paco.me/), [Lee Robinson](https://leerob.io/) and [Hayden Bleasel](https://www.haydenbleasel.com/)

## 🏛️ License

MIT

# 1.0.1 Update

Added ability to run dev and preview on local network.
added npm run dev:network
added npm run preview:network

Added slightly more particle density in both light and dark mode.

Added subtle dark mode star and meteor animations.

Removed eslint config
