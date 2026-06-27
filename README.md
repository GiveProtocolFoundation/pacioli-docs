# Pacioli Documentation

Source for **[docs.pacioli.io](https://docs.pacioli.io)** — the official documentation for [Pacioli](https://pacioli.io), an open-source, currency-agnostic accounting platform for crypto and fiat.

---

## Looking for the Pacioli app?

This repository hosts **documentation only**. If you're looking for the application itself:

| | Repository | What's there |
| --- | --- | --- |
| 🧾 | **[Pacioli](https://github.com/GiveProtocolFoundation/Pacioli)** | The desktop + web application (Tauri + React + Rust). |
| 🌐 | **[pacioli-web](https://github.com/GiveProtocolFoundation/pacioli-web)** | The pacioli.io marketing site. |
| 📚 | **[pacioli-docs](https://github.com/GiveProtocolFoundation/pacioli-docs)** *(this repo)* | This documentation site. |

Live URLs: **App** → [pacioli.io](https://pacioli.io) · **Docs** → [docs.pacioli.io](https://docs.pacioli.io)

---

## About this repository

A [Jekyll](https://jekyllrb.com/) site published via GitHub Pages at `docs.pacioli.io`. Pushes to `main` auto-deploy.

### Structure

```
api-reference/         REST, Rust, and plugin API documentation
crypto-operations/     Chain-specific guides (Polkadot, EVM, etc.)
implementation-guides/ Technical deep-dives (crypto accounting, currency arch)
self-hosting/          Installation, configuration, deployment
user-guide/            End-user documentation
index.md               Documentation home page
_layouts/              Jekyll templates
_config.yml            Jekyll configuration
```

### Local preview

```sh
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

Or for a quick HTML-only preview without Jekyll's Liquid templating:

```sh
python3 -m http.server 8000
```

---

## Contributing

Documentation contributions are welcome — typo fixes, clarifications, new guides, all of it.

1. Fork this repository.
2. Create a branch: `git checkout -b docs/your-improvement`.
3. Make and preview your changes locally.
4. Open a pull request.

### Style notes

- Clear, concise language — avoid jargon when possible.
- Show, don't just tell — include runnable examples.
- Add screenshots for UI-related guidance.
- Link to related docs to help readers navigate.
- Lowercase, hyphenated filenames: `wallet-connection-guide.md`.
- Use ATX-style headers (`#`, `##`, `###`) and fenced code blocks with language hints.

---

## Getting help

- **General questions** → [GitHub Discussions](https://github.com/GiveProtocolFoundation/Pacioli/discussions)
- **Documentation issues** → [file an issue](https://github.com/GiveProtocolFoundation/pacioli-docs/issues)
- **Application issues** → [Pacioli/issues](https://github.com/GiveProtocolFoundation/Pacioli/issues)
- **Community forum** → [community.pacioli.io](https://community.pacioli.io)

---

## License

[GNU AGPL-3.0](./LICENSE), matching the Pacioli application.

Pacioli is a project of the [Give Protocol Foundation](https://github.com/GiveProtocolFoundation).
