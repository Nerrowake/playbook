# Code Style

Code style exists to reduce friction. It should make code easier to read, review,
and maintain.

## General Rules

- Follow the conventions already present in the repository.
- Use formatter and linter tools when the project provides them.
- Prefer descriptive names.
- Keep functions and modules focused.
- Avoid unnecessary abstraction.
- Handle expected errors explicitly.
- Keep comments useful and sparse.

## Naming

Names should describe purpose. Avoid abbreviations unless they are common in the
domain.

## Structure

Group code by responsibility. Keep boundaries clear between domain logic,
interface code, persistence, infrastructure, and tests.

## Comments

Comments should explain why something is done, not restate what the code already
says. Use comments for constraints, tradeoffs, and non-obvious decisions.

## Dependencies

Add dependencies only when they solve a real problem and are likely to be
maintained. Prefer standard library or framework features when they are clear and
sufficient.

## Performance

Write correct code first. Optimize when there is evidence that performance
matters for the user or system.
