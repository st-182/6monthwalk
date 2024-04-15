# 6monthwalk - lose weight in 6month :)

## Website structure

1. Homepage - what this project is all about, our partners or providers 
2. Account page
3. List of technicks (with ability to select if for you, you can select one for a certain time period, the history of selection will be shown in your profile as well as ration of that period)
4. New blog posts (each post can be liked, disliked, added to favorites, commented)

## Features

1. Search 
    1) By product callories
    2) By technicks of losing weight
    3) By Personal blogs
        - you can do bloging on any platform you want 
        - you need to integrate it with our platform if you dont want to share experience only on this platform
    4) Search takes into consideration like/dislike ration
2. Day Ration
   1) Schedule - every 1-3 hours you recive notification untill it becomes a rutine.
      a) Access to set alarms, CRUD operations.
      b) Set possibility to chose from alarm/notification/any other form of reminder.
   2) Easy access to what you eat and how much kcal it has it it.  


# Technical information
## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
