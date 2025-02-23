# template-playwright

Template repository using Playwright and Devcontainer

## Overview

This repository is a template using **Playwright** and **Devcontainer**, allowing you to quickly and efficiently start projects for end-to-end testing or web scraping.

### Note

This template is `headless` by default, meaning that the browser will not be visible when running the tests. If you want to see the browser, you should add settings for X11 to the container.

## Features

- Utilize a powerful test framework with **Playwright**
- Type-safe coding with **TypeScript**
- **Yarn v4** is used as the package manager
- Consistent development environment provided by **Devcontainer**
  - Using playwright official docker image: `mcr.microsoft.com/playwright:v1.49.0-jammy`
  - **ESLint** and **Prettier** for code linting and formatting
  - Further more information, please refer to the `extensions` section in `.devcontainer/devcontainer.json`

## Setup

1. Clone the repository:

```bash
git clone https://github.com/mediee/template-playwright.git
```

2. Open the repository in Visual Studio Code:

```bash
cd template-playwright
code .
```

3. Reopen the repository in the Devcontainer:

- Click on the green icon in the bottom left corner of the window
- Select "Reopen in Container"
- Wait for the Devcontainer to build and automatically install the dependencies

## Usage

- Run the tests (headless mode only):

```bash
yarn test
```

- View the test results:

```bash
yarn test:report
```
