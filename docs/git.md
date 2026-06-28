# Git

Git history should help future maintainers understand what changed and why.

## Commits

Use focused commits with clear messages. A commit should usually represent one
logical change.

Good commit messages:

- `Add issue templates`
- `Document release checklist`
- `Fix query timeline sorting`
- `Update security reporting guidance`

Avoid vague messages:

- `updates`
- `stuff`
- `fixes`
- `wip`

## Commit Message Format

A simple format is enough for most work:

```text
Short imperative summary

Optional body explaining why the change was made, important tradeoffs, or
follow-up work.
```

## Before Committing

- review the diff
- run relevant tests and checks
- remove temporary debugging output
- confirm generated files are intentional
- avoid committing secrets or local environment files

## Rebasing and Merging

Use the workflow that best preserves review clarity for the repository. For most
Nerrowake repositories, squash merges are preferred for pull requests.
