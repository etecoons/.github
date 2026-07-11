# Contributing

Thank you for your interest in etecoons.

Product work belongs in the product repositories—not in this `.github` repo.

| Project | Repository |
|---------|------------|
| Screensaver | [etecoons/trance](https://github.com/etecoons/trance) |
| Effects | [etecoons/trance-plugins](https://github.com/etecoons/trance-plugins) |
| Archive tool | [etecoons/morphball](https://github.com/etecoons/morphball) |
| Package repos | [etecoons/packages](https://github.com/etecoons/packages) |
| Brand assets | [etecoons/brand](https://github.com/etecoons/brand) |

## Guidelines

1. Open an issue before large or cross-repository changes.
2. Branch from `main` and keep commits focused.
3. Run that repository’s checks before opening a PR (`cargo test`, `cargo clippy`,
   `cargo deny` where configured).
4. Follow install and packaging docs in the product README.
5. Do not commit secrets, GPG private keys, machine-local paths, or unrelated
   binary artifacts.
6. Report security issues via private vulnerability reporting
   ([SECURITY.md](SECURITY.md)).

## Pull requests

- Target `main`.
- Describe the change and why it is needed.
- Honor the organization web commit signoff requirement when GitHub prompts for it.
