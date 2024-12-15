# Projeto de carrinho de compras 

Este projeto tem o objetivo de apresentar as funcionalidades de lista de produtos consumindo uma API (Para a API foi usado o json-server subindo o arquivo db.json, neste arquivo contém a lista de produtos usados). Também é realizada a funcionalidade de manipulação do carrinho de compras.

As ferramentas usadas foram: React + TypeScript + Vite + Json-server + Tailwindcss + React-icons. 

O objetivo do projeto foi aprender mais sobre as ferramentas citadas acima.

# Site sendo executado




https://github.com/user-attachments/assets/304c3236-f68e-4417-a018-3ec7164555ad



# Instalação

Para instalar, basta seguir o padrão do Vite. Depois de clonado o repositório, no terminal digitar "npm i" para instalar as dependências, em seguida "npm run dev". A aplicação irá subir localhost na porta mencionada. Depois subir o json-server com o arquivo db.json.

# Arquivo padrão abaixo (ignorar)

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
