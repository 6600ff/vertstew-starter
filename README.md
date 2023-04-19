# vertstew (V<sub><sup>\[ite\]</sub></sup> + R<sub><sup>\[eact\]</sub></sup> + T<sub><sup>\[ype\]</sub></sup>S<sub><sup>\[cript\]</sub></sup> + T<sub><sup>\[ail\]</sub></sup>W<sub><sup>\[indcss\]</sub></sup>) starter

## Core

- [vite](https://vitejs.dev/)
- [react](https://react.dev/)
- [typescript](https://www.typescriptlang.org/)
- [tailwindcss](https://tailwindcss.com/)

## Linting & Formatting

- [eslint](https://eslint.org/)
- [typescript-eslint](https://typescript-eslint.io/)
- [prettier](https://prettier.io/)

## Testing

- [vitest](https://vitest.dev/)
- [happy-dom](https://github.com/capricorn86/happy-dom)
- [@testing-library/react](https://testing-library.com/docs/react-testing-library/intro)

### RATIONALE

I got a little tired of making this pile of dependencies play nice with each other and wrangling configurations every time I wanted to set up a new frontend project. This will hopefully be a good starting point to skip past that and hit the ground running.

I didn't include things like react-router or a react/tailwind component library because those don't require too much configuration to get going and I don't always need them.

### TO START

1. Clone the repo.

```
   git clone https://github.com/6600ff/vertstew-starter.git
```

2. Install dependencies.

```
    cd vertstew-starter/
    npm i
```

3. Change directory name and package name in package.json/package-lock.json if you want.

4. Edit index.html \<title> and add favicon if you have one.

5. Make something cool!

### LINTING/FORMATTING

There are scripts you can run to check for linting errors, fix linting errors, and format the .ts & .tsx files in your src directory:

```
npm run lint
npm run lint:fix
npm run format
```

### TESTING

There's a script to run your tests with vitest:

```
npm run test
```

¡GLHF!
