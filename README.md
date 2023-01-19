# verteal ESLint Config

## What is included in this package?
- Standard config base
- React plugin
- React Hooks plugin
- Prettier

## Installing
1. Install the dependency
```bash
  npm i -D @verteal/eslint-config
```

2. Create a `eslintrc.json` file in the root of your project and paste the following code:
```bash
  {
    "extends": "@verteal/eslint-config/react"
    // or if you are using node.js "extends": "@verteal/eslint-config/node"
  }
```