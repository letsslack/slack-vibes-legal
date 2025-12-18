# Slack Vibes Privacy Policy

**Last updated:** December 18, 2025

Slack Vibes is a developer tool that generates Slack app projects (code + Slack manifest) from user-provided descriptions and can optionally automate Slack app creation and installation. Slack Vibes does **not** host or run your Slack bot.

## What data Slack Vibes processes

### Data you provide
Slack Vibes may process:
- Your app description (plain-English prompt)
- Build options you choose (planner mode, export type, manifest automation, install flow)
- Technical metadata needed to generate the project (e.g., derived app name)

### OAuth / Slack installation data (optional)
If you choose to create and install a Slack app using the OAuth install flow, Slack Vibes may temporarily process:
- OAuth authorization `code` returned by Slack
- Slack access tokens (e.g., bot token)
- Slack signing secret
- Workspace/team identifiers and bot user identifiers
- Granted scopes

## How Slack Vibes uses data

Slack Vibes uses the above data only to:
- Generate the requested Slack app project
- Validate/create/update the Slack app manifest (if you enable it)
- Complete the Slack OAuth install flow (if you enable it)
- Provide one-time retrieval of installation credentials (if requested)

Slack Vibes does **not** use your data for advertising and does **not** sell your data.

## Credential storage and retention

- Installation credentials are stored **temporarily** for the purpose of one-time retrieval.
- Installation sessions expire automatically (time-limited) and are deleted after retrieval.
- Slack Vibes is designed to avoid long-term credential storage.

## Generated artifacts

If you export a ZIP or GitHub repo, Slack Vibes generates code artifacts that you control. You are responsible for where you store, deploy, and run the generated app.

## Logging

Slack Vibes may log operational data (e.g., request timestamps, latency, status codes, request IDs) to maintain reliability and security. Logs should not intentionally contain secrets.

## Third parties

Slack Vibes interacts with:
- **Slack APIs** (only if you enable manifest automation and/or install flow)
- **GitHub APIs** (only if you enable GitHub export)
- **Hosting provider (Render)** for serving the Slack Vibes API

## Your responsibilities

You are responsible for:
- Reviewing generated code before deploying
- Keeping your Slack tokens and signing secret secure
- Operating your generated Slack app in compliance with Slack’s policies and applicable law

For Terms of Service, see:
https://letsslack.github.io/slack-vibes-legal/terms 

## Contact

For privacy questions or requests, contact:
**letsslack@gmail.com**
