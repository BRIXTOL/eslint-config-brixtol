## @brixtol/eslint-config-brixtol

This package includes the shareable ESLint configuration used by [Brixtol Textiles](https://www.brixtoltextiles.com). The config extends upon standard and is mainly configured for internal developments.

### Install

[pnpm](https://pnpm.js.org/en/cli/install)

```cli
pnpm i @brixtol/eslint-config-brixtol --save-dev
```

### Usage

Extend the configuration with `package.json`

```json
{
"eslintConfig": {
  "ignorePatterns": "*.html",
  "extends": ["@brixtol/eslint-config-brixtol"]
}
```

### Related

- [@brixtol/prettier-config](https://github.com/brixtol/prettier-config)

### License

Licensed under [MIT](#LICENCE)

---

We [♡](https://www.brixtoltextiles.com/discount/4D3V3L0P3RS]) open source!
