# Boilerplate NodeJS 22.11.0 LTS + Typescript

This boilerplate is designed to streamline the initial development of NodeJS projects with **TypeScript**. The structure is optimized and includes integrated tools to ensure best development practices.

## Features

- **TypeScript**: Provides static typing and a robust development experience.
- **Husky**: Automates the execution of Git hooks, such as commit checks and linting before pushing.
- **Commitlint**: Ensures your commit messages follow a defined pattern.
- **Prettier**: Keeps the code consistently formatted.
- **Lint-Staged**: Runs checks and formatting only on modified files.
- **Nodemon**: Facilitates development with automatic reloading during code changes.
- **Configuração de produção e desenvolvimento**: Scripts for compiling and running the project in both development and production environments.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 22.11.0)
- [npm](https://www.npmjs.com/) (Node.js package manager)

## Initial Setup

1. **Clone this repository**:

   ```bash
   git clone git@github.com:jefferson-alves-dev/Boilerplate-NodeJS-22.11-LTS-TypeScript-.git
   ```

   ```bash
   cd Boilerplate-NodeJS-22.11-LTS-TypeScript-
   ```

2. **Install dependencies**:

   ```bash
   npm run install:base
   ```

## Available Scripts

### `npm run exec:dev`

Runs the code in development mode using `ts-node`.

### `npm run build:dev`

Compiles TypeScript code to JavaScript and runs it in development mode with automatic reloading using `nodemon`.

### `npm run build:prod`

Compiles TypeScript code to JavaScript and runs it in production mode.

## Development

During development, use the `exec:dev` script to run the bot directly in the TypeScript environment without needing to compile.
If you prefer automatic reloading, use `build:dev`.

## Contributing

Feel free to contribute to this project by submitting pull requests or reporting issues in the issues tab.
