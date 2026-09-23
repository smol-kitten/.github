# Security Policy

This is the default security policy for every repository in the
[smol-kitten](https://github.com/smol-kitten) organisation that does not ship
its own `SECURITY.md`.

## Reporting a vulnerability

1. **Preferred:** use GitHub private vulnerability reporting on the affected
   repository. Open the repository's **Security** tab and choose
   **Report a vulnerability**. This channel is enabled on all public repositories.
2. **Second channel:** email [security@catboy.systems](mailto:security@catboy.systems).
   Include the repository name, affected version or commit, steps to reproduce,
   and the impact you expect.

Please do not open a public issue for security findings.

## What to expect

- **Acknowledgement** within **72 hours** of your report.
- **Coordinated disclosure.** We work with you on a fix and a disclosure date
  before details go public. We ask that you keep the finding private until then.
- **Credit** in the advisory and release notes on request. If you prefer to stay
  anonymous, say so and we respect that.

## Supported versions

| Version | Supported |
|:--------|:---------:|
| Latest release | ✅ |
| `main` branch | ✅ |
| Older releases | ❌ |

Fixes land on `main` and ship with the next release. Older releases do not
receive backports.

## Scope

This policy covers the source code and release artifacts published under the
smol-kitten organisation. For anything hosted at catboy.systems that is not
tied to a repository, email [security@catboy.systems](mailto:security@catboy.systems).
