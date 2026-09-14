# Support

## Getting help

- **Documentation:** start with the repository README and its `docs/` directory.
- **Issues:** search existing issues before opening a new one. Issues are the
  only discussion channel; GitHub Discussions is not enabled on these
  repositories, so do not wait for a reply there.
- **Security:** never use a public issue. Follow [SECURITY.md](SECURITY.md),
  which routes reports to the affected repository's private advisory form.

## Repository status

Every repository states its status in its own README. The status says what you
can expect from it, and nothing on this page overrides what a repository says
about itself.

| Status | What it means | What support looks like |
|---|---|---|
| **Production** | Serving real users or real decisions. | Actively maintained. Bugs are triaged and fixed. |
| **Candidate** | Complete and under verification, not yet operating in production. Deployment still requires documented setup steps. | Actively developed. Correctness issues are welcome; treat interfaces as unsettled. |
| **Labs/Prototype** | Exploring an approach. Parts are deliberately unfinished. | Limited. Read it for the approach, not as something to depend on. |
| **Research** | A published analysis or artifact. The result is the deliverable and the code exists to reproduce it. Dependencies and CI are kept current so the result stays reproducible. | Corrections to the method, data, or result are welcome. Feature requests generally are not. |
| **Historical** | Kept as a record of earlier work. Not maintained. | None. Do not build on it. |

**Research is not archived.** A repository can be actively maintained and still
be Research: the maintenance keeps the published result reproducible rather than
adding capability. Genuinely dormant work is **Historical**.

## Requesting a feature

- Check existing issues first.
- Describe the problem and who has it, not the implementation you have in mind.
- Say how it fits the repository's stated purpose and status. A feature request
  against a Research or Historical repository is unlikely to be taken up.

## Reporting a bug

Include:

- What happened and what you expected instead.
- The steps to reproduce it, with the smallest input that still shows it.
- Environment: operating system, Node or Python version, and how you installed
  dependencies.
- Any error message or log output, with secrets removed.
- What you already tried.

For a **Research** repository, the most useful bug report is one that shows a
published number cannot be reproduced from the committed data, and says which
number and what you got instead.

## Conduct

Respectful, constructive collaboration is expected. Bad faith, harassment, and
off-topic noise get issues closed and contributors blocked.

## Licence and attribution

Licensing differs by repository, so check the repository's own `LICENSE`. Some
are permissively licensed, some are source-visible for evaluation only, and
third-party code and data carry their own terms, documented separately in each
repository.
