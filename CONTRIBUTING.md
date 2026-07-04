# 🤝 Contributing to Eranova Docs

First off — thank you for considering contributing! Every improvement helps developers, partners, and users understand and build on Eranova Workforge.

## 📋 Table of Contents

- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Writing Documentation](#writing-documentation)
- [Pull Request Process](#pull-request-process)
- [Style Guide](#style-guide)
- [Community](#community)

## Getting Started

1. **Fork** the repository
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<your-username>/eranova-docs.git
   cd eranova-docs
   ```
3. **Install** dependencies:
   ```bash
   npm install
   ```
4. **Create** a feature branch:
   ```bash
   git checkout -b docs/your-topic
   ```
5. **Start** the dev server:
   ```bash
   npm start
   ```

## Development Workflow

```
main ← your-branch (PR) ← your local work
```

- Always branch from `main`
- Keep branches focused — one topic per PR
- Rebase on `main` before submitting if there are conflicts

## Writing Documentation

### File Format

All docs are written in **MDX** (Markdown + JSX). Place them in the appropriate folder:

| Content Type | Location |
|---|---|
| Docs pages | `docs/` |
| Custom pages | `src/pages/` |
| Components | `src/components/` |

### Frontmatter

Every doc page should have frontmatter:

```mdx
---
sidebar_position: 1
title: Your Page Title
description: A brief description for SEO
---
```

### Tips

- Use clear, concise language
- Include code examples where helpful
- Add screenshots or diagrams for complex flows
- Link to related pages using relative paths
- Keep paragraphs short and scannable

## Pull Request Process

1. Ensure the site builds without errors:
   ```bash
   npm run build
   ```
2. Run type checking:
   ```bash
   npm run typecheck
   ```
3. Write a clear PR title and description
4. Reference any related issues (e.g., `Closes #42`)
5. Request a review from a maintainer

### PR Title Convention

```
docs: add authentication guide
fix: correct broken link in API reference
feat: add search component
chore: update dependencies
```

## Style Guide

- **Headings**: Use sentence case (`## Getting started`, not `## Getting Started`)
- **Code blocks**: Always specify the language (` ```bash `, ` ```typescript `)
- **Links**: Use relative links for internal pages
- **Images**: Place in `static/img/` and reference from there
- **Admonitions**: Use Docusaurus admonitions for tips, warnings, etc.

```mdx
:::tip
This is a helpful tip!
:::

:::warning
Be careful with this step.
:::
```

## Community

- 💬 Join discussions in [GitHub Discussions](https://github.com/eranova-workforge/eranova-docs/discussions)
- 🐛 Report bugs via [GitHub Issues](https://github.com/eranova-workforge/eranova-docs/issues)
- 📧 Reach maintainers at **docs@eranova-workforge.dev**

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).

---

*Every line of documentation helps someone ship faster.* 🚀
