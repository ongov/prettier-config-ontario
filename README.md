# prettier-config-ontario

A [Prettier](https://prettier.io) configuration based on the Ontario Frontend JavaScript style guide that will be released in the future. This README is repurposed from prettier-config-airbnb.

## Installation

```sh
npm install prettier-config-ontario --save-dev
```

or

```sh
yarn add prettier-config-ontario --dev
```

## Usage

Create a `.prettierrc.json` file in your project root directory with a value:

```json
"prettier-config-ontario"
```

If you need to overwrite some properties, create a `.prettierrc.js` file in your project root directory, import the configuration and export the modifications:

```javascript
module.exports = {
  ...require('prettier-config-ontario'),
  printWidth: 120,
};
```
