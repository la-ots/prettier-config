# @la-ots/stylelint-config

Standard configuration for [Prettier](https://prettier.io/).

## Installation

```bash
npm install --save-dev @la-ots/prettier-config
```

### Configure settings

Create `.prettierrc.js` file with the following content:

```javascript
module.exports = {
  ...require("@la-ots/prettier-config"),
};
```

### IDE Integration

Follow [instructions provided by Prettier](https://prettier.io/docs/en/editors.html) for integration setup.

## Running linters

Add the following scripts to your `package.json`:

```javascript
{
  "scripts": {
    "prettier-check": "prettier --check .",
    "prettier-fix": "prettier --write ."
  }
}
```

Execute scripts:

```bash
npm run prettier-check
npm run prettier-fix
```
