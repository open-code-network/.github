# Contributing to Open Code Network (OCN)

Thank you for your interest in contributing to **Open Code Network (OCN)**! We are an independent software engineering foundry building production-grade, public-good digital infrastructure. 

We maintain an uncompromising bar for code quality, system architecture, security, and documentation. Whether you are a student fellow at our flagship hub or an external open-source contributor, please follow these guidelines carefully.

---

## 🛠️ The OCN Engineering Workflow

We do not accept direct pushes to `main` or `master`. All contributions—bug fixes, features, optimizations, or documentation—must flow through our peer-reviewed Git pipeline.

### 1. Find or Open an Issue
*   Before writing code, check the existing **GitHub Issues** or open a new one detailing the bug, feature request, or architectural improvement you want to address.
*   Comment on the issue to let the core maintainers know you are working on it.

### 2. Branch Naming Convention
Create a descriptive feature branch off `main` using standard prefixes:
*   `feature/short-description` (for new features)
*   `fix/short-description` (for bug fixes)
*   `docs/short-description` (for documentation updates)
*   `refactor/short-description` (for code refactoring without feature changes)

### 3. Commit Message Standards
We follow clean, descriptive commit conventions. Use clear prefixes:
*   `feat: add user session authentication via JWT`
*   `fix: resolve database connection timeout under heavy load`
*   `docs: update API routing documentation`
*   `test: add integration test suite for campus ballot voting`

---

## 🔍 Pull Request (PR) Requirements

When your code is ready, open a Pull Request against the repository's `main` branch. Your PR must meet the following criteria before approval:

1.  **Tested & Verified:** Ensure your code runs locally without breaking existing features. Include unit tests or integration tests where applicable.
2.  **Cross-Squad QA Review:** All PRs require at least **two peer reviews** from members outside your immediate development squad (enforcing our cross-testing protocol).
3.  **Clean Code & Linting:** Code must pass all project linters and formatters (e.g., ESLint, Prettier, Black) with zero unhandled exceptions or console errors.
4.  **"Docs or It Didn't Happen":** If you add or modify a feature or API endpoint, update the corresponding documentation (`README.md`, OpenAPI specs, or wiki) inside the PR.

---

## 🛡️ Code Review Code of Conduct

When reviewing code from fellow builders:
*   Be respectful, objective, and constructive. Focus on the code, not the coder.
*   Explain the *why* behind requested changes (e.g., performance impact, security vulnerability, maintainability).
*   Approve and merge only when the system is production-ready.