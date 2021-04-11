# Tailwind / PostCSS / HTML Starter Kit

Provides a playground for quick experiments using
Tailwind Jit, PostCSS and plain HTML files,
including live reload capabilities.

## Usage

Fetch the code, install dependencies and run the dev server:

```
npx degit drubb/tailwind-postcss-html
cd tailwind-postcss-html
npm install
npm run dev
```
The dev server uses port 3000 by default, so the preview
is available in the browser at localhost:3000.

Now try changing *.html* or *.pcss* files, and the pages will be
reloaded on save.

The *.pcss* extension for css files is used for convenience
(better IDE support). If you prefer using *.css* as
extension, you'll also need to change the watch
command in package.json!

## Features

* [Tailwind 2.1](https://tailwindcss.com) with [Jit mode](https://tailwindcss.com/docs/just-in-time-mode) activated
* [PostCSS 8](https://postcss.org) with [postcss-import](https://github.com/postcss/postcss-import) and [postcss-preset-env](https://preset-env.cssdb.org)
* [Live-Server](https://npmjs.com/package/live-server) to provide live reload capability

## Licence: MIT
