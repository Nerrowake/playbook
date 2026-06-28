# Security

Security should be considered during design, implementation, review, and release.

## Baseline Practices

- never commit secrets
- validate and sanitize external input
- escape output in user-facing contexts
- use framework security features
- keep dependencies current
- avoid logging sensitive data
- review permissions and access control
- fail safely when errors occur

## Privacy

Collect the least data needed for the product to work. Explain what is collected,
why it is needed, and how it is stored.

For telemetry tools, be especially careful with:

- request payloads
- headers and cookies
- database queries
- customer data
- authentication tokens
- environment details

## Dependencies

Review dependencies for maintenance quality, licensing, and security posture.
Remove unused dependencies.

## Reporting

Each active repository should include `SECURITY.md` with private reporting
instructions. Public issues should not be used for vulnerabilities.

## Review Questions

- Does this expose private data?
- Does this expand access to sensitive behavior?
- Are errors handled without leaking secrets?
- Are logs safe?
- Are permissions explicit?
- Does the change create a new dependency or supply-chain risk?
