# Repository Standards

Every Nerrowake repository should eventually include:

- `README.md`
- `LICENSE.md`
- `CHANGELOG.md`
- `ROADMAP.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `SUPPORT.md`
- `docs/`
- `.github/`
- `tests/`

Some early repositories may start smaller, but the expectation is that active
projects grow toward this structure before public release.

## README

The README should explain:

- what the project is
- who it is for
- current project status
- installation or setup
- basic usage
- development commands
- testing commands
- links to docs, roadmap, changelog, support, and security policy

## Docs

Use `docs/` for durable project documentation. Keep the README focused on
orientation and the most common path.

## Tests

Use `tests/` for automated tests when the project includes code. Repositories
that are documentation-only may omit tests until code or scripts are added.

## GitHub Files

Use `.github/` for repository-specific workflows, issue templates, pull request
templates, and automation. Organization defaults live in `Nerrowake/.github`.

## Naming

Use clear repository names. Prefer lowercase words separated by hyphens unless a
project has a proper product name.

## Status

Public repositories should state their maturity:

- experimental
- active development
- stable
- maintenance
- archived
