# GitHub Standards

GitHub should make project work easier to understand and review.

## Repository Settings

Recommended baseline:

- default branch: `main`
- squash merge enabled
- delete branches after merge
- branch protection for active projects
- required checks before merge when CI exists
- private vulnerability reporting enabled when available
- discussions enabled only when the project benefits from them

## Labels

Recommended labels:

- `type: bug`
- `type: feature`
- `type: enhancement`
- `type: documentation`
- `type: discussion`
- `priority: critical`
- `priority: high`
- `priority: medium`
- `priority: low`
- `area: backend`
- `area: frontend`
- `area: design`
- `area: docs`
- `area: testing`
- `area: security`
- `area: performance`
- `area: infrastructure`
- `status: needs review`
- `status: needs reproduction`
- `status: blocked`
- `status: ready`
- `status: in progress`
- `status: released`
- `good first issue`
- `help wanted`
- `breaking change`

## Issues

Issues should describe a problem, request, or task clearly enough that someone
can act on it. Use templates where possible.

Bug reports should include reproduction steps, expected behavior, actual
behavior, environment details, and logs or screenshots when useful.

## Pull Requests

Pull requests should be scoped and reviewable. They should include a summary,
testing notes, documentation updates, and any risk or follow-up work.

## Automation

Use GitHub Actions for repeatable checks. Keep workflows readable and project
specific. Avoid automation that blocks work without providing useful feedback.
