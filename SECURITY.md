# 🔒 Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| latest  | ✅ Yes             |
| older   | ❌ No              |

We only provide security fixes for the latest release on `main`.

## Reporting a Vulnerability

We take security seriously at Eranova Workforge. If you discover a vulnerability in this documentation site or its infrastructure, please report it responsibly.

### How to Report

1. **Do NOT** open a public GitHub issue for security vulnerabilities.
2. Email us at: **security@eranova-workforge.dev**
3. Include:
   - A clear description of the vulnerability
   - Steps to reproduce
   - Potential impact assessment
   - Any suggested fixes (optional but appreciated)

### What to Expect

- **Acknowledgment** within 48 hours of your report
- **Assessment** within 5 business days
- **Resolution timeline** communicated after assessment
- **Credit** in our security advisories (if you'd like)

### Scope

This policy covers:
- The documentation website and its deployment pipeline
- Dependencies used in the documentation build
- Configuration that could expose sensitive data

### Out of Scope

- The Eranova Workforge platform itself (report via the main platform's security policy)
- Third-party services we link to
- Social engineering attacks

## Best Practices We Follow

- Dependencies are pinned and regularly audited
- CI/CD pipeline uses least-privilege access
- No secrets are stored in the repository
- Environment variables are used for sensitive configuration

Thank you for helping keep Eranova Workforge secure! 🙏
