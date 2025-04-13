# Vue 3 + Vite + Tailwind CSS v4 + shadcn/ui Template

This repository is a starter template for building modern web applications using:

- **Vue 3**
- **Vite**
- **Tailwind CSS v4** ([docs](https://tailwindcss.com/))
- **shadcn/ui** ([docs](https://ui.shadcn.com/))
- **Vitest** for unit testing
- **ESLint** for linting

Use this template to quickly scaffold a new project with a pre-configured setup for rapid development and best practices.

## Features

- ⚡️ Fast development with Vite
- 🎨 Utility-first styling with Tailwind CSS v4
- 🧩 Beautiful, accessible components with shadcn/ui
- 🧪 Unit testing with Vitest
- 🧹 Code quality with ESLint
- 📝 TypeScript support for `.vue` files

## Getting Started

To use this template, click "Use this template" on GitHub or clone the repo and install dependencies:

```sh
pnpm install
```

### Compile and Hot-Reload for Development

```sh
pnpm dev
```

### Type-Check, Compile and Minify for Production

```sh
pnpm build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
pnpm test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
pnpm lint
```

---

Feel free to customize and extend this template to fit your project's needs.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).
