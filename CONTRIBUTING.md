# Contributing to Teja Game Hub

First off, thank you for taking the time to contribute! 🎮

The following is a set of guidelines for contributing to **Teja Game Hub**. This is a
small, dependency-free project, and every contribution helps.

---

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [How to Contribute](#how-to-contribute)
3. [Commit Messages](#commit-messages)
4. [Style Guidelines](#style-guidelines)
5. [Testing Changes](#testing-changes)
6. [Opening an Issue](#opening-an-issue)
7. [Opening a Pull Request](#opening-a-pull-request)

---

## Code of Conduct

By participating in this project you agree to abide by the
[Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

---

## How to Contribute

There are many ways to contribute:

- 🐛 **Report a bug** — open an issue with a clear title and description.
- ✨ **Request a feature** — open an issue describing the improvement you'd like.
- 🕹️ **Add a new game** — the best kind of contribution!
- 📝 **Improve docs** — fix typos, clarify instructions, add examples.
- 🔧 **Fix bugs / refactor** — submit a pull request.

### Reporting a bug

Please use the [Bug Report](.github/ISSUE_TEMPLATE/bug_report.yml) template. Include:

- A clear, descriptive title.
- Steps to reproduce.
- What you expected vs. what actually happened.
- Browser / OS and any relevant console errors.

### Requesting a feature

Use the [Feature Request](.github/ISSUE_TEMPLATE/feature_request.yml) template and describe
the problem the feature solves, not just the feature itself.

---

## Commit Messages

We use [Conventional Commits](https://www.conventionalcommits.org/) style:

```
<type>(optional scope): <short description>

<optional body>
```

Examples:

```
feat: add Neon Pong two-player mode
fix(snake): prevent snake reversing into itself
docs: update game list in README
style: adjust neon glow on game cards
refactor: extract scoreboard into its own module
```

Common types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `perf`, `chore`.

---

## Style Guidelines

This project intentionally keeps everything in a single `index.html`, so please match the
existing code style:

- **HTML / CSS** — follow the compact, one-liner style already used for rules and elements.
  Keep using the CSS custom properties defined in `:root`.
- **JavaScript** — use modern (ES6+) vanilla JS. Prefer `const`/`let`, arrow functions, and
  template literals. Keep functions well-named and reasonably small.
- **Naming** — descriptive names; games are registered via `data-game="<name>"` attributes.
- **No dependencies** — do not add frameworks or build tools. The project must remain a
  single file that runs by opening it in a browser.

> ⚠️ New games should be added to the games grid with a `data-game` attribute, wired into
> the `openGame()` handler, and listed in the `README.md` games table.

---

## Testing Changes

There is no automated test suite. To verify your changes:

1. Open `index.html` in a modern browser (Chrome, Edge, Firefox, Safari).
2. Make sure the page loads without console errors.
3. Play each game you touched, on both **desktop keyboard** and **mobile/touch** if possible.
4. Check the responsive layout at a few viewport sizes.

---

## Opening an Issue

Before opening an issue, please:

- Search existing issues to avoid duplicates.
- Use the appropriate issue template.
- Give a clear, reproducible description.

---

## Opening a Pull Request

1. **Fork** the repository and create a branch from `main`.
2. Make your changes — ideally scoped to a single logical improvement.
3. Test locally as described above.
4. Commit using the [Conventional Commit](#commit-messages) format.
5. Ensure your branch is up to date with `main`.
6. Open a pull request and fill out the
   [PR template](.github/PULL_REQUEST_TEMPLATE.md).
7. A maintainer will review and, once approved, merge your changes.

Thank you for contributing! 🚀
