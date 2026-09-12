# Security Policy

## Authentication security

Orbit Launcher uses Microsoft's official OAuth 2.0 Device Authorization Grant for Microsoft account authentication.

Orbit Launcher does not request or store Microsoft account passwords.

The launcher is designed as a public desktop client and does not embed a client secret.

## Sensitive information

Do not publish or submit any of the following in GitHub issues:

- Microsoft passwords
- access tokens
- refresh tokens
- Xbox tokens
- XSTS tokens
- Minecraft access tokens
- device codes
- payment card information
- private account recovery information

## Local credential storage

Where supported, Orbit Launcher stores Microsoft session data using Electron `safeStorage`, which relies on operating-system protected encryption.

## Reporting a vulnerability

If you discover a security issue, do not include active credentials in a public report.

Open an issue describing the affected component and reproduction steps without secrets. A private contact channel can then be arranged if necessary.

## Scope

Security reports may include:

- authentication flow problems
- unsafe token handling
- path traversal or file access issues
- unsafe external URL handling
- launcher privilege or sandbox issues
- mod installation security problems

## Supported version

The currently supported development branch is Orbit Launcher 1.2.x.
