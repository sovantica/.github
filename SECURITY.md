# Security policy

## Reporting a vulnerability

Please report security vulnerabilities privately. Do **not** open a public issue.

**Email:** [security@sovantica.ai](mailto:security@sovantica.ai)

**Expected response:** initial acknowledgment within 72 hours.

**Include in your report:**

- Affected repository, version or commit SHA.
- Reproduction steps (minimal example if possible).
- Potential impact (data exposure, code execution, denial of service, etc.).
- Any suggested mitigation or patch.

You may also use GitHub's built-in private vulnerability reporting — click the "Report a vulnerability" button on the Security tab of any `sovantica` repository. Reports submitted this way are delivered directly to maintainers.

## Coordinated disclosure

We follow a coordinated disclosure timeline:

1. **Triage** — within 72 hours of report, we confirm receipt and begin assessment.
2. **Fix development** — timeline depends on severity; critical issues prioritized over feature work.
3. **Advisory** — we publish a GitHub Security Advisory with CVE request (where applicable) once a fix is available.
4. **Credit** — reporters are credited in the advisory unless they request anonymity.

We ask that you do not publicly disclose the vulnerability until we have had reasonable time to address it.

## Supported versions

Each repository documents its supported version windows in its own README. As a general rule:

- **Security fixes** are backported to the latest minor release of any actively maintained product.
- **Older versions** may receive fixes at maintainer discretion; no formal LTS commitment on the free tier.
- Paid-tier commitments, where applicable, are documented per product.

## Scope

This policy applies to code in repositories under the `sovantica` GitHub organization. It does not cover:

- Third-party services linked from our products (report those to the respective service provider).
- Social engineering of individual maintainers.
- Physical attacks on infrastructure we do not operate.

## Contact

- Security reports: [security@sovantica.ai](mailto:security@sovantica.ai)
- General inquiries: [hello@sovantica.ai](mailto:hello@sovantica.ai)
