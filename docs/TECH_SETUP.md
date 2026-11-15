# TaskFlow — Technology Stack and Development Setup

## 1. Project Overview

TaskFlow is a task management web application developed using React and Vite.

This document describes the technology stack, development environment, installation process, and code quality tools.

## 2. Technology Stack

### React

React is a JavaScript library used to build reusable user interface components.

In TaskFlow, React provides the foundation for the interactive task management interface.

### Vite

Vite is a modern frontend development and build tool.

It provides a development server, fast module updates, and optimized production builds.

### JavaScript

JavaScript is used to implement application logic and interactive functionality.

### CSS

CSS is used to style the application, define layouts, and support responsive design.

## 3. Development Environment

The project can be developed using:

- Windows or macOS.
- Node.js and npm.
- WebStorm, IntelliJ IDEA, or another compatible IDE.
- Git for version control.
- GitHub for collaboration.

## 4. Installation

Clone the repository:

```bash
git clone https://github.com/dasqiee/taskflow-team-project.git
```

Navigate to the project directory:

```bash
cd taskflow-team-project
```

Install dependencies:

```bash
npm install
```

## 5. Running the Application

Start the development server:

```bash
npm run dev
```

Open the local address displayed by Vite, typically:

http://localhost:5173/

## 6. ESLint

ESLint is used to detect JavaScript code quality issues.

Configuration file: `eslint.config.js`

Run ESLint:

```bash
npm run lint
```

## 7. Stylelint

Stylelint is used to check CSS code quality and enforce consistent styling rules.

Configuration file: `.stylelintrc.json`

Run Stylelint:

```bash
npm run lint:css
```

To automatically fix supported CSS issues:

```bash
npx stylelint "src/**/*.css" --fix
```

## 8. Production Build

To generate an optimized production build:

```bash
npm run build
```

The generated files are stored in the `dist` directory.

## 9. Git Workflow

The project uses feature branches and pull requests.

Development workflow:

1. Update the local main branch.
2. Create a feature branch.
3. Implement changes.
4. Run code quality checks.
5. Commit changes.
6. Push the branch to GitHub.
7. Create a pull request.
8. Review and merge the pull request.

## 10. Validation

The project uses the following validation commands:

```bash
npm run lint
npm run lint:css
npm run build
```

All commands should complete successfully before changes are merged into the main branch.

## 11. Expected Result

The development environment should allow both contributors to install dependencies, run the application, validate source code, and collaborate through GitHub.
