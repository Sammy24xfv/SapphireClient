# Sapphire Client Privacy Policy

_Last updated: 14 November 2026_

Sapphire Client is a Minecraft launcher made by Sammy24xfv. This page explains what information the launcher handles and where it goes. The short version: **we don't run any servers that collect your data, we don't track you, and we don't sell anything.**

## What we (the Sapphire Client developer) collect

**Nothing.** Sapphire Client has no accounts of its own, no analytics, no advertising and no tracking. Official builds have crash reporting switched off, so no crash reports are sent to us either.

The only things the launcher downloads from us are files anyone can see:

- The list of game versions and mod bundles, from our public [SapphireData](https://github.com/Sammy24xfv/SapphireData) repository on GitHub.
- Release notes and app updates, from our [GitHub releases](https://github.com/Sammy24xfv/SapphireClient/releases).

These downloads go through GitHub. We can't see who downloads them; GitHub's own [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) covers what GitHub logs.

## What stays on your computer

The launcher saves its data in your user folder (on Windows: `%APPDATA%\Sammy\SapphireClient`). This includes:

- **Your Minecraft accounts**: your username, account ID and the sign-in tokens Microsoft gives the launcher, so you don't have to sign in every time. Anyone who can use your computer account could read this file, so keep your computer account protected. Removing an account in Settings deletes its tokens.
- **Your settings**, including any API keys you enter under Settings → APIs.
- **Your instances (clusters)**: their mods, worlds, screenshots and logs.
- **Play statistics** such as playtime and the servers you joined. These are only shown to you and never leave your computer, except as noted under "Server icons" below.

You can delete all of it at any time by deleting that folder.

## Services the launcher talks to

To do its job, the launcher connects to these services. Each one receives your IP address, like any website you visit, plus what's listed below. Their own privacy policies apply to that information.

| Service | When | What it receives |
|---|---|---|
| **Microsoft and Xbox Live** | When you sign in | Your Microsoft sign-in, handled on Microsoft's own sign-in page. The launcher never sees your password. |
| **Mojang / Minecraft** | Signing in, launching the game, showing skins | Your account token and player ID |
| **Modrinth** | Browsing mods and installing Minecraft versions and mod loaders | Your searches and the files you download |
| **CurseForge** | Browsing mods from CurseForge | Your searches and the files you download |
| **Fabric, Forge and NeoForge** | Installing those mod loaders | The files you download |
| **Java providers** (Microsoft, Adoptium, Amazon Corretto, Azul, BellSoft) | When the launcher downloads Java for you | The files you download |
| **GitHub** | Checking for updates and loading game versions and bundles | The files you download |
| **SkyClient** (via GitHub) | Showing SkyBlock mod information | The files you download |
| **Cloudflare** | A quick check that you're online | Nothing beyond the connection itself |
| **mcsrvstat.us** | Showing icons for servers in your play statistics | The address of each server shown |
| **mclo.gs** | **Only when you click "Upload log"** | That game log, which becomes a public link you can share |
| **Discord** | If Discord is running and Rich Presence is on | Your Discord status ("Playing Sapphire Client" and the instance name), sent to the Discord app on your computer |

## Children

Sapphire Client doesn't collect personal information from anyone, including children. Minecraft and Microsoft accounts have their own age rules, set by Microsoft.

## Changes

If this policy changes, the new version will be published here with a new "Last updated" date. The full history is on GitHub.

## Contact

Questions about privacy? Open an issue at [github.com/Sammy24xfv/SapphireClient/issues](https://github.com/Sammy24xfv/SapphireClient/issues).
