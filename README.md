# template-playwright

Template repository using Playwright and Devcontainer

## Overview

This repository is a template using **Playwright** and **Devcontainer**, allowing you to quickly and efficiently start projects for end-to-end testing or web scraping.

## Features

- Utilize a powerful test framework with **Playwright**
- Type-safe coding with **TypeScript**
- Consistent development environment provided by **Devcontainer**
- Improved development efficiency with **VSCode customizations**
- **Yarn v4** is used as the package manager
- **Linters and formatters** like Prettier are set up by default in the devcontainer

## Prerequisites

- Install [Git](https://git-scm.com/)
- Install [Visual Studio Code](https://code.visualstudio.com/) and the [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- Install [Docker](https://www.docker.com/)

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

- Run the tests:

```bash
yarn test
```

- View the test results:

```bash
yarn test:report
```
