# Contributing to Solution-Desk

Thanks for taking the time to contribute!

## Ways to help
- Report bugs and request features using our issue templates.
- Improve docs and examples.
- Submit small, focused pull requests.

## Development flow
1. Fork the repo and create a feature branch.
2. Run tests and linters locally before opening a PR.
3. Keep PRs small and focused; add screenshots for UI changes.

## Commit Style (Conventional Commits)

Use short, present-tense messages following **Conventional Commits**:

**Format**
<type>(optional scope): <summary>

**Common types**
- `feat:`     user-facing feature
- `fix:`      bug fix
- `chore:`    tooling/maintenance (no code behavior change)
- `docs:`     docs only
- `refactor:` code change that doesn’t fix a bug or add a feature
- `perf:`     performance improvement
- `test:`     add or fix tests
- `build:`    build system or deps
- `ci:`       CI changes

**Examples**
feat(forms): add CSV import
fix(api): handle 401 refresh
docs: update README with quickstart
chore: bump deps and run formatter

PRs should use these commit styles. Our CI checks commit messages on every PR.

## Code of Conduct
By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).
