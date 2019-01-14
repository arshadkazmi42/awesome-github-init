## ESLint Basic Config (NodeJs)

This config validates the following

- Extends `strongloop`
- Allows double quotes only
- Allows 2 spaces tabs

```json
{
  "env": {
    "node": true,
    "mocha": true
  },
  "parserOptions": {
    "ecmaFeatures": true,
    "sourceType": "module"
  },
  "extends": "strongloop",
  "rules": {
    "quote-props": [2, "always", { "keywords": true }],
    "max-len": ["error", { "code": 100, "tabWidth": 2, "ignoreTemplateLiterals": true  }]
  }
}
```