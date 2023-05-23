
<p align="center">
  Aplicação em React/TypeScript - Cadastro de projetos baseado em um timer 🚀
  <br>
  <br>

  <img alt="Language count" src="https://img.shields.io/github/repo-size/alvarobraz/project-timer"/>

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  </a>

  <a href="https://www.linkedin.com/in/alvarobraz/">
    <img alt="Made by alvarobraz" src="https://img.shields.io/badge/made%20by-alvarobraz-%237519C1">
  </a>

  <a href="https://github.com/alvarobraz/project-timer/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/alvarobraz/project-timer">
  </a>

  <img alt="License" src="https://img.shields.io/github/license/alvarobraz/project-timer">
</p>

---

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#estrutura">Estrurura</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a>
</p>

<br>

## :dart: Sobre ##

Aplicação em ReactJs/TypeScript de cadastro de projetos baseado em um timer onde é gravado um histórico que exibe se o projeto está em andamento, interrompido ou concluído!


## :rocket: Tecnologias ##

As seguintes tecnologias foram utilizadas no projeto:

- [React.js](https://pt-br.legacy.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Styled Components](https://styled-components.com/)
- [ContextApi](https://legacy.reactjs.org/docs/context.html)
- [useReducer](https://react.dev/reference/react/useReducer)
- [immer](https://www.npmjs.com/package/immer)
- [React Hook Form](https://react-hook-form.com/)
- [Zod](https://www.npmjs.com/package/zod)
- [date-fns](https://www.npmjs.com/package/date-fns)



## Estrutura ##
```
.
├── index.html
├── LICENSE
├── package.json
├── public
│   └── assets
│       └── igniteLogo.svg
├── README.md
├── src
│   ├── App.tsx
│   ├── components
│   │   └── Header
│   │       ├── Header.tsx
│   │       └── styles.ts
│   ├── contexts
│   │   └── Context.tsx
│   ├── DefaultLayout
│   │   ├── DefaultLayout.tsx
│   │   └── styles.ts
│   ├── main.tsx
│   ├── pages
│   │   ├── History
│   │   │   ├── History.tsx
│   │   │   └── styles.ts
│   │   └── Home
│   │       ├── components
│   │       │   ├── Countdown
│   │       │   │   ├── Countdown.tsx
│   │       │   │   └── styles.ts
│   │       │   └── NewCycleForms
│   │       │       ├── NewCycleForms.tsx
│   │       │       └── styles.ts
│   │       ├── Home.tsx
│   │       └── styles.ts
│   ├── reducers
│   │   └── cycles
│   │       ├── actions.ts
│   │       └── reducers.ts
│   ├── Router.tsx
│   ├── styles
│   │   ├── global.ts
│   │   └── themes
│   │       └── default.ts
│   ├── @types
│   │   └── styles.d.ts
│   └── vite-env.d.ts
├── tsconfig.json
├── tsconfig.node.json
├── vercel.json
├── vite.config.ts
└── yarn.lock

```

## :white_check_mark: Requerimentos ##

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/)

## :checkered_flag: Começando ##

```bash
# Clone this project
$ git clone https://github.com/alvarobraz/project-timer

# Access
$ cd project-timer

# Install dependencies
$ yarn install

# Run the project
$ yarn dev

# The server will initialize in the <http://localhost:3000>
```
