# Microsoft / Minecraft App Review Information

This page summarizes the intended Microsoft authentication use case for Orbit Launcher.

## Application

- Name: Orbit Launcher
- Platform: Windows desktop
- Type: Independent Minecraft: Java Edition launcher
- Client type: Public client
- OAuth flow: Device Authorization Grant
- Application (Client) ID: `3adf926a-f972-44c2-a889-24874af484ba`

## Purpose

Orbit Launcher allows users who already own Minecraft: Java Edition to authenticate with their own Microsoft account and launch Minecraft with their official profile.

## Authentication flow

```text
Microsoft OAuth
→ Xbox Live
→ XSTS
→ Minecraft Services
→ Entitlement verification
→ Minecraft Java profile
```

Orbit does not ask users to enter their Microsoft password inside the launcher.

## Requested Minecraft Services access

Orbit requires Minecraft Services access only to:

1. exchange a valid Xbox/XSTS identity for a Minecraft access token;
2. verify Minecraft ownership/entitlements;
3. retrieve the authenticated Minecraft Java profile;
4. launch Minecraft using that official identity.

## Current development status

Microsoft OAuth, Xbox Live and XSTS are implemented.

Minecraft Services access requires the Orbit Launcher Application ID to be approved for the appropriate Minecraft Services use.

## Compliance intent

Orbit Launcher is intended for legitimate Minecraft owners and is not designed to bypass ownership checks, authentication, subscriptions, bans, or server access controls.
