# Node.js TypeScript Project Template

A starter template for Node.js projects using TypeScript, ESLint, Prettier, Jest, and other popular tools.

## Features

- **TypeScript** for writing modern, type-safe JavaScript.
- **ESLint** configured with TypeScript support to maintain code quality.
- **Prettier** for consistent code formatting.
- **Jest** for unit testing.
- **Nodemon** for automatic server restarts during development.
- **Husky** and **lint-staged** (optional) for pre-commit code linting and formatting.

## Getting Started

#### Clone Directly

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/typescript-node-template.git your-new-project
   ```

2. Navigate into the project directory:

   ```bash
   cd your-new-project
   ```

3. Remove the existing `.git` directory to detach from the template's history:

   ```bash
   rm -rf .git
   ```

4. Initialize a new Git repository

   ```bash
   git init
   git add .
   git commit -m "Initial commit
   ```

5. Create a new repository on GitHub and push your code.

### Project Setup

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the development server

   ```bash
   npm run dev
   ```

### Available Scripts

In the project directory, you can run:

#### `npm run dev`

Runs the app in development mode using ts-node and nodemon. The server will restart if you make edits.

#### `npm run build`

Builds the app for production to the dist folder using the TypeScript compiler.

#### `npm start`

Runs the compiled JavaScript files from the dist folder.

#### `npm test`

Runs the test suite using Jest.

#### `npm run test:watch`

Runs the tests in watch mode, re-running tests when files change.

#### `npm run lint`

Runs ESLint to analyze your code for potential errors and style issues.

#### `npm run format`

Formats your code using Prettier.

#### `npm run clean`

Deletes the dist folder to clean up compiled files.

### Project Structure

    ├── src
    │   └── index.ts       # Entry point of your application
    ├── dist               # Compiled JavaScript files (generated after build)
    ├── node_modules       # Project dependencies
    ├── .vscode            # VSCode specific settings (optional)
    ├── .env.example       # Example environment variables file
    ├── .eslintrc.js       # ESLint configuration
    ├── .prettierrc        # Prettier configuration
    ├── jest.config.js     # Jest configuration
    ├── package.json       # NPM scripts and dependencies
    ├── tsconfig.json      # TypeScript compiler options
    └── README.md          # Project documentation
