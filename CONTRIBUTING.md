# Contributing

Thank you for your interest in Daly Ventures projects.

## Before You Start

- Read the repository's README and understand its purpose
- Check the SECURITY.md file for vulnerability reporting and safety boundaries
- Review any AGENTS.md or repository-specific instructions

## Code Changes

### Requirements

- All changes must pass CI checks (audit, lint, typecheck, build, tests)
- Add tests at the level where failures can recur
- Document non-obvious decisions in code or commit messages
- Run all applicable checks locally before opening a pull request

### Process

1. Create a focused branch for your change
2. Make the smallest coherent change that addresses the issue
3. Open a pull request with:
   - Clear description of the problem and solution
   - Evidence that the problem exists
   - Files changed
   - Tests/checks run
   - Any deployment or migration requirements

### Testing

Prioritize tests for:
1. Deterministic business rules and scoring
2. Authorization and permissions
3. Input validation and boundaries
4. Persistence and migrations
5. External service contracts

Do not inflate coverage with tests of trivial implementation details.

## Commit Messages

- Start with a clear, actionable verb (Add, Fix, Refactor, etc.)
- Include the problem and solution
- Reference relevant issues or PRs
- Include a Co-authored-by line if appropriate

## Releases and Tags

Do not create version tags without verification:
- Code must pass all CI checks
- Deployment/production state must be verified
- Release notes must document the change

## Questions?

Check the repository's documentation or open an issue.
