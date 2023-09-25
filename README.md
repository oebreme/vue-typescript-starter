# vue-typescript-starter

This project is a custom Vue 3 template with TypeScript set up. 

It bears recommendations from the official docs at [vuejs.org](https://vuejs.org/guide/introduction.html), but also my personal preferences as someone coming from Angular.

---
### Important

resolver aliases
: ```Note that resolver aliases are not set in the tsconfig compilerOptions. 
This causes imports using '@/* to not work'. You instead must set up your imports via path-reference.```

---

### Project Setup

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

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
