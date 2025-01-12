# KhulnaSoft Prettier Config

[![npm](https://img.shields.io/npm/v/@khulnasoft/prettierrc.svg)](https://www.npmjs.com/package/@khulnasoft/prettierrc)
[![downloads](https://img.shields.io/npm/dt/@khulnasoft/prettierrc.svg)](https://www.npmjs.com/package/@khulnasoft/prettierrc)
[![build](https://travis-ci.org/khulnasoft-lab/prettierrc.svg?branch=master)](https://travis-ci.org/khulnasoft-lab/prettierrc)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

Prettier config for projects at KhulnaSoft.

## Usage

```
npm install --save-dev @khulnasoft/prettierrc
```

Then add this `prettier.config.js` to the project:

```js
module.exports = require('@khulnasoft/prettierrc')
```

## Making changes

```
npm link
cd <project>
npm link @khulnasoft/prettierrc
npm run prettier
```

## Publish a new version

Follow [semver](http://semver.org/). **Changing or adding a rule is a breaking change and requires a new major version**.

```
npm version major|minor|patch
git push
git push --tags
npm publish
```
