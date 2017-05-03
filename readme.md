# Mithril / Typescript / SASS Example Project

This is an example project using [Mithril](https://mithril.js.org/), TypeScript and node-sass.

## Installation:

    npm install

## Serve this project locally and recompile .ts and .scss sources on save:

    npm start

Then go to http://localhost:3000 in your browser. This will serve the files in the `public` directory, defaulting to the `index.html` file.

The files `public/js/app.js` and `public/css/app.css` are rebuilt whenever the sources are recompiled.

While this npm script is running, edits made to `src/ts/*.ts` and `src/css/*.scss` files will be recompiled automatically so you can simply refresh your browser to see the updated app.

## Build a minified bundle

    npm run build

Will output a minified `app.js` file in `public/js` and `app.css` in `public/css`
