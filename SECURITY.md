# Security Policy

## Reporting Vulnerabilities

**Do not open a public issue for security vulnerabilities.**

Instead, use the repository's **Security → Advisories → Report a vulnerability**
form (GitHub private vulnerability reporting). If that form is unavailable for
a repository, use <https://dalyventures.com/> to request a secure reporting
channel. Include:
- Description of the vulnerability
- Steps to reproduce
- Impact assessment
- Suggested fix (if available)

We will investigate and coordinate a fix, then work with you on public disclosure timing.

## Supported Versions

Each repository maintains a SECURITY.md file with specific version support information.

## Security Practices

We prioritize:
- Type safety and static analysis
- Input validation and boundary checking
- Least-privilege access and authorization
- Audit logging for sensitive operations
- Dependency security scanning (via Dependabot)

## Third-Party Data

We treat model output, external APIs, user input, and uploaded data as untrusted.

We fail closed when:
- Identity or permissions are unresolved
- Authoritative evidence is absent
- Data provenance is unknown

## Deployment and Operations

- Never commit secrets, tokens or credentials to repositories
- Use environment-specific configuration for sensitive values
- Document security assumptions and operational gates in deployment runbooks
- Test migrations against representative production data before deployment
