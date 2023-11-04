# Node CLI Leaven

This project is created as a scaffold for creating Node CLI applications.

## Usage 

To use this project as a scaffold for your own CLI application, 
simply clone this repository and remove the `.git` directory.

```bash
git clone https://github.com/tomaszbawor/node-cli-leaven --depth=1 my-cli-app
cd my-cli-app
rm -rf .git
```

Now you can install dependencies and start developing your own CLI application.

```bash
npm install
```

## Features

- [x] [NPM](https://www.npmjs.com/) scripts for common operations
- [x] [TypeScript](https://www.typescriptlang.org/) support
- [x] [ESLint](https://eslint.org/) configuration based on [antfu configuration](https://github.com/antfu/eslint-config)
- [x] [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) with [Commitlint](https://commitlint.js.org/#/) and [Husky](https://typicode.github.io/husky/#/)
- [x] Commit lint for [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [x] Automatic changelog generation based on commits

