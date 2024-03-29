# NJS's Vue Template

A nice and simple Vue template to let me (or anyone else) quickly whip up new projects.

## Features

- [Vue](https://vuejs.org/) + TypeScript
- [Vue Router](https://router.vuejs.org/)
(Router and routes are found in `./src/routes`)
- [Vite](https://vitejs.dev/)
- [Yarn](https://yarnpkg.com/) for package management
- [ESLint](https://eslint.org/) and [Prettier](https://prettier.io/)
    with some sensible defaults.
- [Tailwind CSS](https://tailwindcss.com/) + [DaisyUI](https://daisyui.com/)

### VS Code Extensions

- [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
- [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)
- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next)
- [Tailwind CSS Intellisense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
with some basic settings.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)

## Coding style

This ESLint and Prettier config uses double-quotes and semicolons.

```ts
const msg = "wow";
```

## Installation

You can download this repo as a .zip or clone it with git,
but a cleaner approach is with [degit](https://github.com/Rich-Harris/degit).

```bash
npx degit njs-templates/njs-vue new-project
cd new-project
yarn
```

## Recommended IDE

This was meant to be used with VS Code, but it should work with any editor.
You'll be prompted to install any recommended extensions that aren't installed.
If no one on your team is using VS Code, just delete the `.vscode/` folder.

## Next steps

- [ ] Run `yarn dev` to start Vite and make sure everything's working.
- [ ] In `package.json`, change the project name and version.
- [ ] Delete the following:
    - [ ] `LICENSE.txt` from the root of the directory.
        - If your project still uses an MIT License, just edit the author and year.
    - [ ] Either delete `CHANGELOG.md` or remove its contents.
    - [ ] The boilerplate from `src/App.vue`,
`src/components/HelloWorld.vue` and `src/style.css`.
        - You can easily do this from the Todo Tree tab in VS Code.
    - [ ] The `.git/` folder if you cloned this repo.
- [ ] Run a `git init` to start tracking changes.
- [ ] Do whatever. This code is yours now. Credit is appreciated but not needed.
