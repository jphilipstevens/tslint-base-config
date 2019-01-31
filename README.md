# TSLint Config

## Installation

```sh
npm install @jphilipstevens/tslint-base-config --save-dev
```

## Usage

In `tslint.json`:

```json
{
  "extends": "@jphilipstevens/tslint-base-config"
}
```

## Rules

* [TSLint](https://www.npmjs.com/package/tslint)
* [TSLint ESLint Rules](https://www.npmjs.com/package/tslint-eslint-rules)
* [TSLint Config Prettier](https://www.npmjs.com/package/tslint-config-prettier)

## Peer Dependencies
This package  has peer dependencies for the tslint, Typescript (inherited from tslint), and the rules
```json
"peerDependencies": {
    "tslint": "^5.5.0",
    "tslint-config-prettier": "^1.17.0",
    "tslint-eslint-rules": "^5.4.0",
    "typescript": "^2.2.0 || ^3.0.0"
  }
```