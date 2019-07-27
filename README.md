# eslint-plugin-legacy-decorators

Tiny plugin to add `{ legacyDecorators: true }` to eslint parser options. This is particularly useful with [standard](https://github.com/standard).

## Install

Use [npm](https://npmjs.com/) to install.

```sh
npm install eslint-plugin-legacy-decorators --save
```

## Usage

After installing, add the plugin to your `standard` configuration (or other linter).

```js
  // ... in package.json ...
  "semistandard": {
    "parser": "babel-eslint",
    "plugins": ["legacy-decorators"]
  }
```

## License

MIT, see [LICENSE.md](http://github.com/mattdesl/eslint-plugin-legacy-decorators/blob/master/LICENSE.md) for details.
