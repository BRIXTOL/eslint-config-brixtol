## @brixtol/eslint-config-javascript

This package includes the shareable ESLint configuration consumed by [Brixtol Textiles](https://www.brixtoltextiles.com) on JavaScript projects. This configuration uses the [Babel](https://github.com/babel/babel-eslint).

### Install

[pnpm](https://pnpm.js.org/en/cli/install)

```cli
pnpm i @brixtol/eslint-config-javascript --save-dev
```

### Usage

Extend the configuration with `package.json`

```json
{
  "eslintConfig": {
    "ignorePatterns": "*.html",
    "extends": ["@brixtol/eslint-config-javascript"]
  }
}
```

### Related

- [@brixtol/eslint-config-typescript](https://github.com/brixtol/eslint-config-typescript)
- [@brixtol/prettier-config](https://github.com/brixtol/prettier-config)

### License

[MIT](#LICENCE)

---

We [♡](https://www.brixtoltextiles.com/discount/4D3V3L0P3RS]) open source!
