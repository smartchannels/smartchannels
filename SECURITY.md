# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in SmartChannels, please report it responsibly.

**Do NOT open a public GitHub issue for security vulnerabilities.**

Instead, use [GitHub's private vulnerability reporting](https://github.com/smartchannels/smartchannels/security/advisories/new).

We will acknowledge your report within 48 hours and provide a detailed response within 7 days.

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest  | Yes       |

## Security Model

SmartChannels is built with a deny-by-default security model:

- No action executes unless explicitly allowed via YAML allowlist
- 7-layer defense-in-depth architecture
- All actions are audited via OpenTelemetry
- Prompt injection defense (multi-layer: sanitize, harden, validate, red-team)
- Per-user rate limiting and daily cost caps

For full details, see the security documentation (coming soon).
