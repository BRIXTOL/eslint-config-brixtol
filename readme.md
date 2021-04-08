## @brixtol/eslint-config-javascript

This package includes the shareable ESLint configuration consumed by [Brixtol Textiles](https://www.brixtoltextiles.com) on JavaScript projects. This configuration uses the [Babel](https://github.com/babel/babel/tree/main/eslint/babel-eslint-parser).

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
    "extends": ["@brixtol/eslint-config-javascript"],
    "rules": {}
  }
}
```

### Troubleshoot

If the shareable config is being consumed outside the brixtol monorepo then you may need install deps into that project:

```cli
pnpm i @babel/eslint-parser @babel/eslint-plugin eslint eslint-config-standard eslint-import-resolver-babel-module eslint-plugin-import eslint-plugin-node eslint-plugin-promise --save-dev
```

### Related

- [@brixtol/eslint-config-typescript](https://github.com/brixtol/eslint-config-typescript)
- [@brixtol/prettier-config](https://github.com/brixtol/prettier-config)
- [@brixtol/browserslist-config](https://github.com/brixtol/browserslist-config)

### License

[MIT](#LICENCE)

---

We [♡](https://www.brixtoltextiles.com/discount/4D3V3L0P3RS]) open source!
