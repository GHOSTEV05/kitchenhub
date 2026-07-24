# Contributing Guidelines

Welcome to KitchenHub!

To keep the project organized and maintainable, we follow these development guidelines.

---

## Branch Strategy

We use the following branches:

- `main` → Stable production-ready code.
- `develop` → Main development branch.

Every new feature must be created from `develop`.

Example:

feature/auth-login

feature/product-crud

feature/orders

fix/jwt-refresh

refactor/order-service

---

## Commit Convention

We follow the Conventional Commits specification.

Examples:

feat(auth): implement login endpoint

feat(products): add CRUD operations

fix(order): prevent duplicate orders

docs(readme): update installation guide

refactor(user): simplify authentication flow

test(auth): add integration tests

style(api): format controllers

chore: configure Docker

ci: add GitHub Actions workflow

---

## Pull Requests

- Create a feature branch from `develop`.
- Keep commits small and focused.
- Open a Pull Request to `develop`.
- Wait for review before merging.

---

## Code Style

- Use ESLint and Prettier.
- Write clear and descriptive variable names.
- Keep controllers thin; business logic belongs in services.
- Follow the project's folder structure.

---

## General Rules

- Do not commit `.env` files.
- Do not commit `node_modules`.
- Write descriptive commit messages.
- Keep documentation updated when adding new features.