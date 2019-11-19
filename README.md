# NPM Package Example

To publish your own NPM package:

1. Fork this repo.
2. Edit [`package.json`](https://github.com/hchiam/npm-package-example/blob/master/package.json) fields (e.g., name, version, author, description, etc.).
3. Makes sure the `main` field in [`package.json`](https://github.com/hchiam/npm-package-example/blob/master/package.json) points to the entry point `index.js`, or whatever you file/filename you choose.
4. The `unpkg` field is for browser build.
5. In CLI: login to NPM with `npm login` command.
6. `npm publish`

Example published package:

* https://www.npmjs.com/package/hchiam-npm-package-example
* https://unpkg.com/hchiam-npm-package-example

Live example usage (using browser build):

https://codepen.io/hchiam/pen/VwwgZEm
