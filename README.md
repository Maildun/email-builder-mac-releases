# Maildun for Mac

An agentic email builder for macOS. Design emails by hand with a drag-and-drop editor, or let AI design them
with you, then export HTML that renders in Outlook, Gmail and on mobile.

**[⬇ Download the latest version](https://github.com/Maildun/email-builder-mac-releases/releases/latest)** —
pick `Maildun_<version>_universal.dmg` under **Assets**.

## What it does

- **Design by hand** with the drag-and-drop editor: blocks, ready-made sections, an inspector, and desktop and
  mobile previews.
- **Design with AI**: connect Claude, ChatGPT, Gemini or Grok with your own API key. The assistant edits your
  design live, as a proposal you accept or reject.
- **Workspaces**: one per client or product, each with its own designs, brand and media.
- **Brand**: your colors, fonts and brief. New designs start in your brand, and the assistant keeps to it.
- **Saved sections**: save your header, footer or any block once and reuse it in every design.
- **Media**: upload images to your own Cloudflare R2 or Amazon S3 bucket, resized and converted to WebP first.
- **Design over MCP**: turn on the built-in MCP server and Claude Code, Codex, Claude Desktop or Cursor can
  create and edit emails in Maildun. No Node.js needed.

Your designs are plain files on your Mac, and your API keys stay in the macOS Keychain.

## Install

1. Download `Maildun_<version>_universal.dmg` from the
   [latest release](https://github.com/Maildun/email-builder-mac-releases/releases/latest).
2. Open it and drag **Maildun** to **Applications**.
3. Open Maildun from Applications.

**Requirements:** macOS 12 Monterey or later, on Apple Silicon or Intel (one universal download for both).

Maildun is signed with an Apple Developer ID and notarized by Apple, so it opens without security warnings.

## Updates

Maildun checks for new versions at launch and every few hours, and installs them in the background; the new
version applies the next time you open it. You can check by hand from **Maildun → Check for Updates…**, and turn
automatic installs off on the **Updates** page.

Every update is signed and verified before it's installed. Release notes for each version are on the
[releases page](https://github.com/Maildun/email-builder-mac-releases/releases).

## Feedback and bugs

Found a bug or have an idea? [Open an issue](https://github.com/Maildun/email-builder-mac-releases/issues/new).
Include your Maildun version (shown on the **Updates** page) and macOS version.

---

This repository holds release builds and the update feed only; Maildun's source code isn't published here.
More at [maildun.com](https://maildun.com).
