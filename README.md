# rollup-getting-started

basid on project:
https://github.com/rollup/rollup-starter-app

## Related links：
something about (package.json).module
https://juejin.im/entry/5a99ed5c6fb9a028cd448d6a

## Rollup guide:
https://rollupjs.org/guide/en

## Getting started

Clone this repository and install its dependencies:

```bash
git clone https://github.com/f12n/rollup-getting-started.git
cd rollup-starter-app
npm install
```

The `public/index.html` file contains a `<script src='bundle.js'>` tag, which means we need to create `public/bundle.js`. The `rollup.config.js` file tells Rollup how to create this bundle, starting with `src/main.js` and including all its dependencies, including [date-fns](https://date-fns.org).

`npm run build` builds the application to `public/bundle.js`, along with a sourcemap file for debugging.

`npm start` launches a server, using [serve](https://github.com/zeit/serve). Navigate to [localhost:5000](http://localhost:5000).

`npm run watch` will continually rebuild the application as your source files change.

`npm run dev` will run `npm start` and `npm run watch` in parallel.

## License

[MIT](LICENSE).
