# Contributing to Itaja

Thank you for helping. This guide applies to every public repository of the organisation unless the repository has its own `CONTRIBUTING.md`.

## Before you start

- **Security issue?** Do not open an issue: follow [SECURITY.md](SECURITY.md).
- **Question about your integration?** See [SUPPORT.md](SUPPORT.md).
- **Bug or idea?** Search the open issues first, then open one with the matching template.
- For anything larger than a small fix, open an issue before the pull request so we can agree on the approach.

## Pull requests

- One change per pull request, on a branch named after it (`fix/…`, `feat/…`, `docs/…`).
- Commit messages and pull request titles follow [Conventional Commits](https://www.conventionalcommits.org): `feat:`, `fix:`, `docs:`, `ci:`, `chore:`, `test:` — `feat!:` for a breaking change. Releases and changelogs are generated from them.
- Fill in the pull request template; say how you verified the change.
- The CI must be green. Never commit a secret, a real API key or customer data — use sandbox keys from your environment.
- Never edit a version number, a changelog or a tag by hand where a release workflow owns them.

## Code of conduct

Be respectful and constructive. Harassment, discrimination or personal attacks are not tolerated; maintainers may remove content and block participants who cross that line. Report conduct issues to [hello@getitaja.com](mailto:hello@getitaja.com).
