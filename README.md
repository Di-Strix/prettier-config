# An Andrew Ushakov's prettier config

## Installation

```
npm i --save-dev @di-strix/prettier-config
```

## Usage
- [Using package.json](#package-json)
- [Using `prettier.config.js` or `.prettierrc.js`](#prettierrc-js)
- [Using `.prettierrc` or `.prettierrc.json`](#prettierrc)

---

### package.json <a id="package-json"></a>

Add this line to your `package.json` file
```diff
{
  ...
+ "prettier": "@di-strix/prettier-config",
  ...
}
```

### prettierrc.js <a id="prettierrc-js"></a>

Export a single line from the file
```js
module.exports = '@di-strix/prettier-config'
```

### .prettierrc <a id="prettierrc"></a>

Paste a single line to the file
```json
"@di-strix/prettier-config"
```
