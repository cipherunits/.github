# Security Policy

## Supported repositories

This policy applies to all actively maintained repositories under the Cipher Units organization, including:

- `CipherPortfolio`
- `CipherToken`
- `CipherLogger`
- `CipherScope`
- `npm-mirror`
- `fusion-gui`
- `fusion-tool`
- `fusion-framework`
- `fusion-docs`
- `fusion-snippet`

## Reporting a vulnerability

**Please do not open a public GitHub issue for security vulnerabilities.**

Instead, report it privately by emailing **cipherunit.dev@gmail.com** with:

- A description of the vulnerability and its potential impact
- Steps to reproduce it (proof-of-concept code, if available)
- The affected repository, file(s), and version/commit hash
- Any suggested fix, if you have one

If the repository has [GitHub private vulnerability reporting](https://docs.github.com/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability) enabled, you can also use the "Report a vulnerability" tab under the repo's **Security** section.

## What to expect

- **Acknowledgment:** we aim to confirm receipt within a few days.
- **Assessment:** we'll investigate and let you know if it's confirmed as a valid issue.
- **Fix & disclosure:** once a fix is ready, we'll coordinate a release and credit you (if you'd like) in the release notes, unless you prefer to remain anonymous.

## Scope notes

- `CipherToken` handles cryptographic/token utilities — please pay special attention to correctness and side-channel issues here, as these carry higher real-world risk.
- Dependency vulnerabilities (e.g. via `npm-mirror` cached packages) are also in scope — let us know if a mirrored package is known to be compromised.

Thank you for helping keep Cipher Units and its users safe.
