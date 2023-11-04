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

### Git Hooks
- [x] Pre-commit hook to lint staged files
- [x] Commit-msg hook to lint commit messages

#### Commitlint
Commitlint is a tool to lint your commit messages. It ensures that your commit messages meet the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) format.

You may use helper node script to commit changes with message following proper format:

```bash
npm run cz
```

