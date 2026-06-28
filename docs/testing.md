# Testing

Tests protect behavior and help maintainers change code with confidence.

## Test What Matters

Prioritize tests for:

- user-visible behavior
- critical workflows
- security-sensitive paths
- data transformations
- error handling
- integration boundaries
- regressions

## Test Types

Use the mix that fits the project:

- unit tests for focused logic
- feature tests for user workflows
- integration tests for external boundaries
- end-to-end tests for critical paths
- visual checks for important UI changes

## Test Quality

Good tests are:

- deterministic
- readable
- focused on behavior
- fast enough to run regularly
- clear when they fail

## Pull Request Expectations

Pull requests should include appropriate tests or explain why tests are not
needed. Documentation-only changes usually do not require automated tests.

## Manual Verification

When manual testing is needed, document exactly what was checked. For UI changes,
include screenshots or visual notes.
