# Branching

Nerrowake repositories use `main` as the default branch.

## Branch Names

Use short, descriptive branch names:

- `feature/add-query-timeline`
- `fix/job-status-filter`
- `docs/update-installation`
- `chore/refresh-dependencies`

For Codex-created branches, use the `codex/` prefix unless a repository states a
different convention.

## Branch Types

- `feature/` for new behavior
- `fix/` for bug fixes
- `docs/` for documentation-only changes
- `test/` for test-only changes
- `chore/` for maintenance
- `refactor/` for behavior-preserving structure changes

## Main Branch

The `main` branch should remain releasable for active projects. Work should move
through pull requests once a project has collaborators, CI, or public users.

## Long-Running Branches

Avoid long-running branches when possible. If a larger effort needs one, keep it
up to date and merge smaller completed slices into `main`.
