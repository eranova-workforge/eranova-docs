<p align="center">
  <img src="static/img/logo.svg" alt="Eranova Workforge" width="80" />
</p>

<h1 align="center">Eranova Workforge — Documentation</h1>

<p align="center">
  <strong>One platform connecting talent, funding, and procurement.</strong><br/>
  Find opportunities, grow your network, raise capital, and build teams — all in one place.
</p>

<p align="center">
  <a href="https://github.com/eranova-workforge/eranova-docs/actions"><img src="https://img.shields.io/github/actions/workflow/status/eranova-workforge/eranova-docs/deploy.yml?branch=main&style=flat-square" alt="Build Status" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="License" /></a>
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome" /></a>
  <a href="https://github.com/eranova-workforge/eranova-docs/stargazers"><img src="https://img.shields.io/github/stars/eranova-workforge/eranova-docs?style=flat-square" alt="Stars" /></a>
</p>

---

## 🚀 What is Eranova Workforge?

Eranova Workforge is an all-in-one platform designed for the modern workforce economy. Whether you're a freelancer hunting for your next gig, a startup raising capital, or an enterprise building distributed teams — Workforge brings everything under one roof.

**Core pillars:**

- 🔍 **Discover** — Browse and match with opportunities tailored to your skills
- 🤝 **Connect** — Grow your professional network with verified talent and partners
- 💰 **Fund** — Access capital-raising tools, investor matching, and grant discovery
- 🏗️ **Build** — Assemble and manage teams with integrated procurement workflows

## 📚 About This Repository

This is the official documentation site for Eranova Workforge, built with [Docusaurus 3](https://docusaurus.io/). It powers the public-facing docs at our documentation portal.

## 🛠️ Getting Started

### Prerequisites

- **Node.js** ≥ 20.0
- **npm** (comes with Node.js)

### Installation

```bash
npm install
```

### Local Development

```bash
npm start
```

Launches a local dev server at `http://localhost:3000` with hot-reload. Most edits are reflected instantly.

### Build

```bash
npm run build
```

Generates optimized static output in the `build/` directory, ready for deployment.

### Serve Production Build Locally

```bash
npm run serve
```

### Type Check

```bash
npm run typecheck
```

## 🗂️ Project Structure

```
eranova-docs/
├── docs/               # Documentation pages (MDX)
├── src/
│   ├── components/     # Custom React components
│   ├── css/            # Global styles
│   └── pages/          # Standalone pages
├── static/             # Static assets (images, fonts)
├── docusaurus.config.ts
├── sidebars.ts
└── package.json
```

## 🌐 Deployment

This site is configured for static hosting. Use any platform — GitHub Pages, Vercel, Netlify, Cloudflare Pages, or your own CDN.

```bash
npm run build
# Deploy the build/ directory to your host
```

## 🤝 Contributing

We love contributions! Please read our [Contributing Guide](CONTRIBUTING.md) before submitting a PR.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🔗 Links

- [Changelog](CHANGELOG.md)
- [Roadmap](ROADMAP.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Security Policy](SECURITY.md)

---

<p align="center">
  Built with 🧡 by the <a href="https://github.com/eranova-workforge">Eranova Workforge</a> team
</p>
