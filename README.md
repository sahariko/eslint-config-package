# ESLint Config Package

A pretty standard ESLint configuration I use for my packages.

## Installation and Usage

Install the NPM package and all its dependencies:

```
npm i -D eslint eslint-config-package
```

Add the configuration to your `.eslintrc.js` file:

```js
// .eslintrc.js

module.exports = {
  extends: 'package'
}
```

Or to your `.eslintrc` file:

```json
// .eslintrc

{
  "extends": "package"
}
```
