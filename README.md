# AI Sprint Demo

A blank white page built with [Vite](https://vite.dev), ready to deploy as a static site on [here.now](https://here.now).

## Develop

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The production site is written to `dist/`.

## Deploy to here.now

here.now serves static files, so publish the contents of `dist/` after building. `vite.config.js` sets `base: './'`, so asset paths are relative and the site works at whatever URL here.now gives it.
