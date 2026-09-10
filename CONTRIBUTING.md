# Contributing to Penny Wise

Welcome to

## Claiming an issue

1. Find an open issue that isn't already claimed,
2. Comment on the issue to claim it (e.g. "I'm claiming this one"),

Please only work on one onesuue at a time so everyone gets a fair chance to contribute to tnis project.

## Making changes

1. Fork the repository,
2. Create a branch with a name containing a short description of what you're working on,
3. Make your changes. Keep the Pull Request scoped to the claimed issue - if you spot something else in need of fixing, open a separate issue for it,
4. When naming commits, try to stick to the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) naming convention ([A freeCodeCamp guide about using Conventional Commits](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/)),
5. If applicable, create and run tests for your changes before opening a Pull Request,
6. Open your PR against the `main` branch, and in its description, reference the issue it closes (e.g. `Closes #9`).

## Code Style Guide

1. Keep functions small and readable.
2. Use double quotation marks (`""`),
3. End files with a "Line Feed" (`LF`),

### Tools for Frontend

Before submitting your changes, you can run `npm run lint` from the `/frontend` directory, to check for potential issues, like declared but unused variables,

### Tools for Backend

> [!CAUTION]
> `prettier` might not be configured correctly yet - please make sure if the `backend/.prettierc` file exists, and the settings correspond to the rules laid out in this guide before running the commands

Before submitting your changes, you can run `npm run format:check` to make sure the style in your changes correspond to the guidelines.
- Alternatively, you can run `npm run format` to automatically format your code according to the rules.

---

If anything here is still unclear, please reach out to the team's Discord channel.