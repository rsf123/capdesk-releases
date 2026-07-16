# CAP Ground Branch — downloads

Desktop companion for the Ground Branch Director: prepare sorties, push them to the team's
phones, run the status board, and finish the paperwork on a real keyboard. Works offline.

**This repository holds only the built app.** The source is private; this exists so that
downloads and auto-update work without anyone needing a GitHub account or a token.

## Get it

| | |
|---|---|
| **Windows / macOS** | [**Latest release**](https://github.com/rsf123/capdesk-releases/releases/latest) |
| **ChromeOS** | [**Open the web app**](https://rsf123.github.io/capdesk-releases/app/) — then *Install* from the browser menu. It works offline afterwards. |

### Releases marked *Pre-release*

Those are **internal test builds**. Install one only if you are testing. Once you install a
pre-release, the app keeps updating you to pre-releases — that is deliberate, and it is how test
builds are kept away from everyone else.

## First launch will warn you — the app is not yet code-signed

- **Windows** — SmartScreen: *More info → Run anyway*.
- **macOS** — right-click the app → *Open*, then confirm. (An unsigned macOS build also cannot
  auto-update; until it is signed, download new Mac versions from here by hand.)

## Your data

Everything stays on your machine. Sortie files exchanged with phones (`.capsortie`) are encrypted
with your unit's passphrase, which you set in Settings — a file that leaves your device is never
readable without it.
