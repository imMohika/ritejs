<h1 align="center"><b>Rite</b></h1>
<p align='center'>
  Opinionated <a href="https://nextjs.org">Nextjs</a> </a> Starter Template
  <br />
  Inspired by <a href="https://github.com/antfu/vitesse">Vitesse</a>
</p>

---

## Features

- [x] Everything for being _Speed_: [React](https://github.com/facebook/react), [Vite](https://github.com/vitejs/vite), [pnpm](https://pnpm.js.org/), [ESBuild](https://github.com/evanw/esbuild)
- [ ] [File system based routing](https://github.com/hannoeru/vite-plugin-pages)
- [ ] [Bearable state management](https://github.com/pmndrs/zustand)
- [ ] [Layout system](./src/layouts)
- [ ] [Zero-config PWA](https://github.com/antfu/vite-plugin-pwa)
- [ ] [Tailwnd CSS 3](https://github.com/tailwindlabs/tailwindcss)
- [ ] [Every icon from everywhere](https://github.com/antfu/unplugin-icons)
- [ ] [I18n](./locales)
- [ ] [Markdown Support](https://github.com/antfu/vite-plugin-md)
- [ ] [On-demend Api importing](https://github.com/antfu/unplugin-auto-import)
- [ ] [Server-side generation](https://github.com/antfu/vite-ssg)
- [ ] [Critical CSS](https://github.com/GoogleChromeLabs/critters)
- [ ] [Unit Testing](https://github.com/vitest-dev/vitest)
- [ ] [E2E Testing](https://cypress.io/)
- [ ] [Standards checking with Husky](https://github.com/typicode/husky)
- [ ] [Github Actions](https://github.com/features/actions)
- [ ] [TypeScript](https://www.typescriptlang.org/), because it's the _right_ way to do _Rite_
- [ ] Deploy on Netlify
- [ ] Deploy on Vercel

## Comes with

### UI Frameworks

- [Tailwind CSS 3](https://github.com/tailwindlabs/tailwindcss) - A utility-first CSS framework for rapid UI development.
- [Mantine](https://github.com/mantinedev/mantine) - eact components library with native dark theme support

### Icons

- [Iconify](https://iconify.design) - use icons from any icon sets [🔍Icônes](https://icones.netlify.app/)
- [`unplugin-icons`](https://github.com/antfu/unplugin-icons) - icons as Vue components

### Plugins

- React Router
- Zustand
- vite-plugin-pwa
- vite-plugin-mdx

### Coding style

- ESLint with eslint-config-canonical
- [Markdownlint](https://github.com/DavidAnson/markdownlint)
- Prettier
- Stylelint

### Path aliases

- Alias @ to <rootDir>
- Alias ~ to <rootDir>/src a.k.a. <srcDir>

### Dev tools

- TypeScript
- Vitest
- Cypress
- pnpm
- ssr
- Netlify
- Recomended VS Code Extentions

## Usage

### Development

Just run and visit http://localhost:3000

```bash
pnpm dev
```

### Build

To build the App, run

```bash
pnpm build
```

And you will see the generated file in `dist` that ready to be served.

### Deploy on Vercel

Go to [Vercel](https://vercel.com/new) and select your git repository, `OK` along the way, and your App will be live in a minute.

## Why

When one of my friends said _If a good strongly opinionated template existed for react, i'll use react_ it gave me the motivation to create Rite.