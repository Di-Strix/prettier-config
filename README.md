# An Andrew Ushakov's prettier config

### Installation

```
npm i --save-dev @di-strix/prettier-config
```

### Usage
- [Using package.json](#package,.json)
- [Using `prettier.config.js` or `.prettierrc.js`](#prettierrc.js)
- [Using `.prettierrc` or `.prettierrc.json`](#.prettierrc)

### package.json

Add this line to your `package.json` file
```diff
{
  ...
+ "prettier": "@di-strix/prettier-config",
  ...
}
```

### prettierrc.js

Export a single line from the file
```js
module.exports = '@di-strix/prettier-config'
```

### .prettierrc

Paste a single line to the file
```json
"@di-strix/prettier-config"
```
