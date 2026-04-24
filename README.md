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

> macOS will block Ticket Mate the first time you open it, with a dialog like:
> *"Apple could not verify 'Ticket Mate' is free of malware that may harm your Mac…"*

This is macOS Gatekeeper being cautious — Ticket Mate is not yet notarized by Apple. The app itself is safe. Open it once and macOS remembers.

### Option A — Terminal (fastest)

```sh
xattr -dr com.apple.quarantine "/Applications/Ticket Mate.app"
```

Then double-click Ticket Mate to launch it normally. Done.

### Option B — System Settings (no Terminal)

1. Double-click **Ticket Mate.app** → you'll see the block dialog → click **Done**.
2. Open **System Settings → Privacy & Security**.
3. Scroll down to the **Security** section. You'll see a line that reads something like
   *"Ticket Mate was blocked from use because it is not from an identified developer."*
4. Click **Open Anyway** on that line.
5. Authenticate with your password or Touch ID.
6. Double-click **Ticket Mate.app** again. A new dialog appears — this one has an **Open** button. Click it.

You only need to do this once. Subsequent launches work normally, and Sparkle-delivered updates apply without re-doing the dance.

> Why the ceremony? Apple requires apps distributed outside the Mac App Store to be signed with a paid Developer ID certificate and notarized. Ticket Mate isn't yet — that switch is planned once the app has a paying userbase that justifies the $99/year membership.

## Updates

Ticket Mate checks for updates automatically in the background. You can also check manually from the menu bar: **Ticket Mate → Check for Updates…**

## Requirements

- macOS 14 (Sonoma) or later
- Apple Silicon or Intel

## Releases

All versions and their release notes are listed on the [releases page](https://github.com/Dalibaba/ticketmate-release/releases).

## Support

Questions or problems? Email **braunlinkegbr@googlemail.com**.
