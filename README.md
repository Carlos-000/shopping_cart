# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
  
## Imagens do projeto
![Captura de tela_2023-07-24_21-45-29](https://github.com/Carlos-000/shopping_cart/assets/139983395/5771f351-2c5d-4254-b9bf-647a741ec393)

![Captura de tela_2023-07-24_21-46-46](https://github.com/Carlos-000/shopping_cart/assets/139983395/16a9c9ef-43d0-46a8-a402-e0e531e7b8fb)

![Captura de tela_2023-07-24_21-47-43](https://github.com/Carlos-000/shopping_cart/assets/139983395/a1132426-afab-43cf-b62e-cc59a3675d71)
