# Basic React Setup with Vite and ESLint

This is a starter React project using Vite as the build tool and ESLint for code linting.

## Included Packages

- **react** and **react-dom** — React library and DOM renderer
- **vite** — Fast build tool and dev server
- **eslint** — Code linter to keep code clean and consistent
- **@babel/eslint-parser** — ESLint parser to support modern JS and JSX syntax
- **eslint-plugin-react** — React specific linting rules
- **eslint-plugin-react-hooks** — Linting for React Hooks rules
- **eslint-plugin-react-refresh** — Support for React Fast Refresh in ESLint
- **@vitejs/plugin-react** — Vite plugin for React support
- **prettier** — Code formatter (optional)

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/Charlosus/basic-setup.git
   cd basic-setup
Install dependencies:

```bash

npm install
Start the development server:

```bash

npm run dev

Run ESLint to check for code issues:

```bash

npm run lint

Build the project for production:

```bash
npm run build

Preview the production build:

```bash
npm run preview
Notes
ESLint config is in eslint.config.js using the flat config system.

React Fast Refresh is enabled via ESLint plugin.

Adjust .eslintrc or eslint.config.js if you want to customize linting rules.

