# Prettier config

Prettier config for my personal projects, most of the settings are the same as prettier defaults. Only following options were changed:

- [`singleQuote`](https://prettier.io/docs/en/options.html#quotes) set to `true`, because I'm too used to them at this point
- [`trailingComma`](https://prettier.io/docs/en/options.html#trailing-commas) set to `es5`, because I like trailing commas, not `all` because although I hope I will never have to support non ES6 environment without transpiling, who knows 🤷‍♂️
- [`proseWrap`](https://prettier.io/docs/en/options.html#prose-wrap) set to `always`, I find myself using editor for markdown more and more and I prefer to have it automatically wrapped to desired lenght instead of relying on editor settings for line wrapping (this is supported from `1.8.2` version of `prettier`)

Published as scoped npm package [@straku/prettier-config](https://www.npmjs.com/package/@straku/prettier-config)
