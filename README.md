# eslint-react
eslint config (react)


your `package.json` should include:

```json
  "scripts": {
    "lint": "eslint ."
  },
  "prettier": "antoine-prettier",
  "devDependencies": {
    "antoine-prettier": "^1.0.6",
    "eslint": "^6.8.0",
    "eslint-config-react-app": "^5.2.0",
    "eslint-plugin-import": "^2.20.1",
    "eslint-plugin-jsx-a11y": "^6.2.3",
    "eslint-plugin-react": "^7.18.3",
    "eslint-plugin-react-hooks": "^2.3.0"
  },
```

for babel, add:

```
  {
    "babel-eslint": "^10.0.3",
    "@babel/preset-react": "^7.8.3",
    "babel-plugin-transform-react-remove-prop-types": "^0.4.24",
    "@babel/plugin-proposal-nullish-coalescing-operator": "^7.8.3",
    "@babel/plugin-proposal-optional-chaining": "^7.8.3",
  }
```
