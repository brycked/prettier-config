# @bricked/prettier-config

[![license](https://img.shields.io/github/license/brycked/prettier-config)](LICENSE.md)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![version](https://img.shields.io/npm/v/@bricked/prettier-config?color=crimson&logo=npm)](https://www.npmjs.com/package/@bricked/prettier-config)

Shared Prettier configuration for my projects.

## Installation

```sh
npm install --save-dev @bricked/prettier-config
yarn add --dev @bricked/prettier-config
pnpm add --dev @bricked/prettier-config
```

## Usage

Add the Prettier config to your `package.json`:

```json
{
  "prettier": "@bricked/prettier-config"
}
```

Or to `.prettierrc.js`:

```js
module.exports = require("@bricked/prettier-config");
```
