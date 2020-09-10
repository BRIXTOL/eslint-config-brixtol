## @brixtol/eslint-config-brixtol

This package includes the shareable ESLint configuration used by the [Brixtol Textiles](https://www.brixtoltextiles.com). The config extending upon standard and mainly configured for [Mithril](https://mithril.js.org/) (or HyperScript) related developments.

#### Noteables

- Ecma2020
- Browser
- ES6
- Node

> Currently uses the [babel-eslint](https://github.com/babel/babel-eslint) parser.

### Install

[pnpm](https://pnpm.js.org/en/cli/install)

```cli
pnpm i @brixtol/eslint-config-brixtol --save-dev
```

### Usage

Extend the configuration in the directories `.eslintrc` file

```javascript
{
  'extends': [ 'brixtol']
}
```

### Related

- [@brixtol/prettier-config-brixtol](https://github.com/brixtol/currency-symbols)

### License

Licensed under [MIT](#LICENCE)

---

We [♡](https://www.brixtoltextiles.com/discount/4D3V3L0P3RS]) open source!
