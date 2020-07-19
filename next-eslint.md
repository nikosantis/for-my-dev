Add standard for next.js

`yarn add -D eslint babel-eslint eslint-config-standard eslint-plugin-standard eslint-plugin-node eslint-plugin-import eslint-plugin-promise eslint-plugin-react eslint-plugin-react-hooks eslint-config-standard-react`

Add .eslintrc

```
 {
  "parser": "babel-eslint",
  "env": {
    "browser": true,
    "es6": true,
    "node": true
  },
  "extends": ["standard", "standard-react"],
  "plugins": ["react-hooks"],
  "rules": {
    "react/react-in-jsx-scope": "off",
    "react/prop-types": "off",
    "react-hooks/rules-of-hooks": "error",
    "react-hooks/exhaustive-deps": "warn"
  }
}
```
