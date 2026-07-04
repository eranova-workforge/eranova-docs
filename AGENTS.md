# 🤖 AI Agents — Eranova Docs

This file provides context and instructions for AI coding agents (GitHub Copilot, Cursor, Windsurf, etc.) working on this repository.

## Project Overview

- **Project**: eranova-docs
- **Purpose**: Official documentation for the Eranova Workforge platform
- **Framework**: Docusaurus 3 (React + TypeScript + MDX)
- **Node.js**: ≥ 20.0
- **Package Manager**: npm

## Architecture

```
eranova-docs/
├── docs/               # MDX documentation pages
├── src/
│   ├── components/     # Custom React components (TSX)
│   ├── css/            # Global CSS (custom properties)
│   └── pages/          # Standalone pages (TSX/MDX)
├── static/             # Static assets served as-is
├── docusaurus.config.ts  # Site configuration
├── sidebars.ts         # Sidebar navigation structure
└── tsconfig.json       # TypeScript configuration
```

## Key Commands

| Command | Purpose |
|---------|---------|
| `npm start` | Start dev server (port 3000) |
| `npm run build` | Production build |
| `npm run serve` | Serve production build locally |
| `npm run typecheck` | TypeScript type checking |
| `npm run clear` | Clear Docusaurus cache |

## Coding Conventions

### TypeScript
- Strict mode enabled
- Prefer `interface` over `type` for object shapes
- Use named exports

### Documentation (MDX)
- Always include frontmatter with `sidebar_position`, `title`, `description`
- Use Docusaurus admonitions (`:::tip`, `:::warning`, `:::danger`)
- Keep paragraphs concise and scannable
- Include code examples with language specifiers
- Use relative links for internal navigation

### Components
- Functional components with TypeScript
- CSS Modules for component-scoped styles
- Keep components in `src/components/<ComponentName>/`

### Styling
- Use CSS custom properties defined in `src/css/custom.css`
- Follow Docusaurus theming system (Infima)
- Support both light and dark themes

## Do's and Don'ts

### ✅ Do
- Write documentation in MDX format
- Use Docusaurus built-in components when possible
- Keep the sidebar structure logical and flat
- Add alt text to all images
- Test with `npm run build` before committing

### ❌ Don't
- Don't add a blog section (intentionally removed)
- Don't install unnecessary dependencies
- Don't hardcode URLs — use Docusaurus config
- Don't commit `.env.local` or secrets
- Don't use inline styles in components

## Environment

- Copy `.env.example` to `.env.local` for local development
- No secrets required for basic development
- See `.env.example` for available configuration options

## Related Repositories

- Platform: `eranova-workforge/eranova` (main application)
- Docs: `eranova-workforge/eranova-docs` (this repo)
