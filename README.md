# `@t3kkitz/prettier-config`
![npm (scoped)](https://img.shields.io/npm/v/@t3kkitz/prettier-config.svg)

> My personal [Prettier](https://prettier.io) config.

## Usage

**Install**:

```bash
$ yarn add --dev @t3kkitz/prettier-config
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@t3kkitz/prettier-config"
}
```

**Or extend config by `.prettierrc.js`**:

```js
module.exports = {
  ...require("@t3kkitz/prettier-config"),
  semi: false
};
```
