# Privacy Policy

_Last updated: September 2026_

This document describes how Orbit Launcher handles user information.

## Microsoft account authentication

Orbit Launcher can authenticate a Minecraft account using Microsoft's official OAuth 2.0 Device Authorization Grant.

Orbit Launcher does **not** request, receive, or store the user's Microsoft password.

Authentication is completed on Microsoft's official sign-in pages.

## Information processed

When Microsoft authentication is enabled, Orbit may process the minimum information required to launch Minecraft with the authenticated account, including:

- Minecraft profile name
- Minecraft UUID
- Microsoft/Xbox/Minecraft authentication tokens
- Minecraft entitlement information required to confirm ownership

## Local storage

Authentication session information is stored locally on the user's computer.

Where supported, Orbit Launcher uses Electron `safeStorage` to protect stored session information using operating-system encryption.

Authentication tokens are not intentionally transmitted to Orbit-operated analytics or advertising services.

## Local launcher data

Orbit may also store local launcher settings such as:

- selected Minecraft profiles
- game versions
- Fabric/Vanilla preference
- RAM and display settings
- locally saved server addresses
- launcher preferences

These settings are stored on the user's device.

## Third-party services

Orbit Launcher communicates with services required for its functionality, including services operated by:

- Microsoft
- Xbox
- Minecraft / Mojang
- Fabric
- Modrinth

Those services may process data according to their own privacy policies.

## Advertising and sale of data

Orbit Launcher does not sell user data.

Orbit Launcher does not require advertising tracking for Microsoft account authentication.

## Security

Users should never share Microsoft access tokens, refresh tokens, device codes, passwords, or other authentication credentials.

## Changes

This privacy notice may be updated as Orbit Launcher evolves.

## Contact

For questions or security concerns, open an issue in the public Orbit Launcher repository.
