# Moonwake Studio

Moonwake Studio is a Windows desktop app for the Moonwake Shorts Network. It
brings your YouTube, Instagram and TikTok accounts, their analytics, uploads
and schedule, your Moonwake email and API keys into one place, with Claude Code
built in and an MCP server so other agents can work in it too.

This repository only hosts the installers. The source code is not public.

## Download

Get the latest `Moonwake-Studio-Setup-<version>.exe` from
[Releases](https://github.com/Majkyy111/moonwake-studio/releases/latest).

## Install

Run the installer. It is not code-signed yet, so Windows may say "Windows
protected your PC". Click **More info**, then **Run anyway**.

On first start:

1. **Sign in with Discord** using an account that has access to the Moonwake
   website. You see your own workspace: live views, email and keys.
2. **Connect Zernio** in Settings with your own Zernio API key to bring in your
   Shorts accounts.

Claude Code (Ctrl+`) runs with your own Claude account. If it is not installed
yet, the panel offers to install it with Anthropic's official installer.

## Updates

The app checks this page for new versions every 15 minutes, downloads them in
the background and asks you to restart. **Settings > Updates** has a manual
check.

Updating never touches your data: settings, your encrypted Zernio key and the
activity log stay in `%APPDATA%\Moonwake Studio`.

## Requirements

Windows 10 or 11, 64-bit.
