# Contributing to MYL (My Last [Whatever].zip)

Thanks for helping build MYL in public. This is a personal-first project that earns trust step by step. Please keep security and clarity front-and-center.

## Ground Rules
- No secrets in code or config. Ever.
- Favor small, focused PRs with clear intent.
- Document user-visible behavior and security implications.

## Project Setup
- Python 3.11+
- Install dev deps: `pip install -e ".[dev]"`
- Run linters: `ruff check . && black --check . && mypy .`
- Run tests: `pytest -q`

## Branching
- `main` – stable
- `feat/<name>` – features
- `fix/<name>` – bugfixes
- `docs/<name>` – documentation

## Commit Style
Use concise, imperative messages:
- `feat(journal): add encrypted note create command`
- `fix(auth): handle missing keyring backend gracefully`

## Pull Requests
Include:
- What changed and why
- Security considerations (data, secrets, attack surface)
- Testing notes (commands run, expected output)
- Docs updated (if applicable)

Checklist:
- [ ] Code formatted (Black) & linted (Ruff)
- [ ] Types pass (mypy)
- [ ] Tests added/updated
- [ ] No secrets or personal data

## Issue Labels
- `enhancement`, `bug`, `security`, `documentation`, `good first issue`

## Security
Report vulnerabilities privately via GitHub Security Advisories. See `SECURITY.md`.

## Code of Conduct
Be respectful. See `CODE_OF_CONDUCT.md`.
