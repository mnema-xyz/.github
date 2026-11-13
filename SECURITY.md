# Security Policy

Please report security problems **privately**. Do not open a public issue or pull request, and do not
disclose the problem before a fix is released.

## How to report

Use GitHub's private vulnerability reporting in the affected repository:
*Security* → *Report a vulnerability*.

- Server and web app: <https://github.com/msch128/mnema-talk/security/advisories/new>
- Desktop app: <https://github.com/msch128/mnema-talk-desktop/security/advisories/new>
- Bot SDK: <https://github.com/mnema-xyz/bot-sdk-js/security/advisories/new>
- Mnemo bot: <https://github.com/mnema-xyz/talk-mnemo-bot/security/advisories/new>

If you cannot use GitHub, write to contact@mnema.xyz and we will open a private channel.

Helpful details: the affected component and version, steps to reproduce, and what an attacker could
achieve. You can expect an acknowledgement within 7 days.

## Rules of engagement

Only test against instances you operate yourself. Do not run scanners, brute-force or load tests
against other people's servers; run the stack locally instead.

Each repository's own `SECURITY.md` lists its supported versions and takes precedence over this file.
