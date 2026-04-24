# Ticket Mate

**Turn messy notes into structured ticket drafts — on your Mac, with the AI you already use.**

👉 **[Visit the website](https://dalibaba.github.io/ticketmate-release/)**
👉 **[Download the latest version](https://github.com/Dalibaba/ticketmate-release/releases/latest)**
👉 **[Buy a license](https://buy.polar.sh/polar_cl_iqBuqdktpPDAiIIznf5h37LaQ2rM4NuyTJP6B4E6gI0)**

## What is Ticket Mate?

Ticket Mate is a macOS app that helps you turn unstructured notes — meeting scribbles, Slack threads, bug reports, half-formed ideas — into clean, structured ticket drafts. Define your own templates once (title, context, acceptance criteria, Jira Wiki format, whatever your team uses), pick an AI provider (local Ollama, or Claude / Codex / Kiro if you already have them), and get usable drafts in seconds.

## Install

1. Download the latest `.zip` from the [releases page](https://github.com/Dalibaba/ticketmate-release/releases/latest).
2. Unzip it and drag **Ticket Mate.app** into your `Applications` folder.
3. Follow the **First launch** steps below.

## First launch on macOS

> macOS will show a warning the first time you open Ticket Mate:
> *"Ticket Mate cannot be opened because the developer cannot be verified"*
> or
> *"Ticket Mate is damaged and can't be opened."*

This is macOS Gatekeeper being cautious — Ticket Mate is not yet notarized by Apple. The app itself is safe. To open it:

1. In Finder, open your **Applications** folder.
2. **Right-click** (or Control-click) **Ticket Mate.app** → **Open**.
3. In the dialog, click **Open** again.

You only need to do this once. Subsequent launches work normally.

If the warning persists or you see *"is damaged"*, run this once in Terminal:

```sh
xattr -dr com.apple.quarantine "/Applications/Ticket Mate.app"
```

Then launch the app normally.

## Updates

Ticket Mate checks for updates automatically in the background. You can also check manually from the menu bar: **Ticket Mate → Check for Updates…**

## Requirements

- macOS 14 (Sonoma) or later
- Apple Silicon or Intel

## Releases

All versions and their release notes are listed on the [releases page](https://github.com/Dalibaba/ticketmate-release/releases).

## Support

Questions or problems? Email **braunlinkegbr@googlemail.com**.
