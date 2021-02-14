<p align="center">
  <a href="https://github.com/sky124380729/levi-vue-admin/">
    <img width="200" src="https://qn.antdv.com/logo.png">
  </a>
</p>

<h1 align="center">
  <a href="https://github.com/sky124380729/levi-vue-admin/" target="_blank">Levi Vue Admin</a>
</h1>

<h2 align="center" style="color:aqua">
    It's a vite+vue3+typescript+ant-design-vue project
</h2>

## Project setup

```shell
yarn
```

### Compiles and hot-reloads for development

```shell
yarn dev
```

### Create menu tree Sql

```shell
yarn run menu
```

### Create api or page

```shell
npm run new
```

### Compiles and minifies for production

```shell
yarn build
```

### Run your tests

```shell
yarn test
```

### Lints and fixes files

```shell
yarn lint
```

> this is a personal project,welcome to fork and pr

## structure
```
├── README.md
├── createMenu.js
├── index.html
├── package.json
├── public // global static files
│   └── favicon.ico
├── src // main code
│   ├── App.tsx
│   ├── apis // connect service
│   ├── assets // pic fonts ..
│   ├── components // vue compontents
│   ├── config.ts
│   ├── hooks
│   ├── layouts // global layouts
│   ├── main.ts 
│   ├── pages //
│   ├── permission.ts
│   ├── router
│   ├── store // vuex 
│   ├── styles
│   ├── types
│   ├── useApp.ts
│   ├── utils 
│   └── views
├── tsconfig.json
├── vite.config.ts
├── yarn-error.log
└── yarn.lock
```