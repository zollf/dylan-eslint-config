# Dylan Typescript Eslint Config
## How to Install
```bash
yarn add --dev https://github.com/zollf/dylan-eslint-config.git
yarn add --dev prettier
yarn add --dev eslint eslint-config-prettier eslint-plugin-prettier
yarn add --dev @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

Add to package.json
```json
"eslintConfig": {
  "extends": "./node_modules/dylan-eslint-config/index"
},
```

Run Eslint Test
```bash
yarn run eslint . --ext .ts,.tsx
```