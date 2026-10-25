


> Enterprise-Grade Child Online Safety, CSAM/CSAE Prevention & NSFW Content Moderation SDK.

`child-safety-filter` is a high-performance content moderation SDK designed specifically for tech companies, social platforms, real-time messaging apps, live-streaming interactions, and online education systems. It features embedded protected sensitive wordlists, leet-speak/evasion detection rules, and an in-memory matching engine that enables enterprise servers to intercept harmful, inappropriate, and child exploitation risks in milliseconds.

---

## 📦 Core Features

- 🚀 **Zero-Latency Matching**: Powered by in-memory Trie structures and pattern matching, individual string inspections run in under **1ms**, avoiding network round-trip overhead.
- 🛡️ **CSAE & Child Safety**: Proactively prevents child online exploitation, grooming, and inappropriate NSFW content.
- 🔒 **Enterprise-Grade Security**: Core sensitive lexicons and moderation rules are bundled and protected, preventing client-side reverse engineering or dictionary leaks.
- 🔍 **Anti-Evasion & Leet-Speak Detection**: Automatically normalizes text to defeat evasion techniques such as whitespace separation, symbol substitution, and leet-speak (e.g., `p0rn`, `s3x`).
- 🛠️ **Full TypeScript Support**: Provides comprehensive type definitions and predictable moderation result objects.
- 🔄 **Multi-Tenant Dynamic Rules**: Supports runtime overlays for tenant-specific custom blocking rules.

---

## 💻 Installation

### 1. Configure GitHub Package Registry (`.npmrc`)

This SDK is a private/enterprise GitHub Package. Create or edit the `.npmrc` file in your project root directory:

```ini
@your-github-username:registry=[https://npm.pkg.github.com](https://npm.pkg.github.com)
//[npm.pkg.github.com/:_authToken=YOUR_GITHUB_PAT](https://npm.pkg.github.com/:_authToken=YOUR_GITHUB_PAT)
