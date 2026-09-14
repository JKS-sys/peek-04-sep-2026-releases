<div align="center">

# Peek

**A fast, minimal image viewer for macOS, Windows and Linux.**

Opens instantly. Gets out of the way. Shows you the picture.

[**Download v1.0.9**](https://github.com/JKS-sys/peek-04-sep-2026-releases/releases/latest) · [Product page](https://ipconfig.co.network/peek) · [Report an issue](https://github.com/JKS-sys/peek-04-sep-2026-releases/issues)

</div>

---

## Download

Grab the file for your platform from the [latest release](https://github.com/JKS-sys/peek-04-sep-2026-releases/releases/latest).

| Platform | File | Notes |
|---|---|---|
| **macOS** (Apple Silicon — M1/M2/M3/M4) | `Peek-1.0.9-arm64.dmg` | Most Macs sold since 2020 |
| **macOS** (Intel) | `Peek-1.0.9.dmg` | Macs from before 2020 |
| **Windows** 10 / 11 | `Peek-1.0.9-win.zip` | Extract, then run `Peek Setup 1.0.9.exe` |
| **Linux** (any distro) | `Peek-1.0.9.AppImage` | `chmod +x` then run |
| **Linux** (Debian / Ubuntu) | `peek_1.0.9_amd64.deb` | `sudo dpkg -i peek_1.0.9_amd64.deb` |

Not sure which Mac you have? Apple menu → About This Mac. If it says "Apple M…",
take the **arm64** build.

### macOS — the first launch

Peek is signed but not distributed through the App Store, so Gatekeeper stops it once.
Open Terminal and run:

```bash
xattr -cr /Applications/Peek.app
```

Then open Peek normally. You only ever do this once.

### Windows

SmartScreen may warn you because the installer is new. Click **More info → Run anyway**.

---

## What it does

- **Opens fast.** Straight to the image, no splash screen, no spinner.
- **Every common format** — JPEG, PNG, GIF, WebP, AVIF, HEIC/HEIF, TIFF, BMP, SVG, ICO.
- **Folder browsing** with a collapsible file tree (`⌘B`), and drag across it to select many images at once.
- **Multiple windows.** Select several images in Finder and press Return — each one opens in its own window.
- **Share / AirDrop** straight from the toolbar (`⌘⇧A`).
- **Zoom, pan, rotate, flip**, fit-to-window and 1:1.
- **Wrap-around navigation** — arrow past the last image and you land back on the first.
- **Dark and light themes**, following the system or pinned to your preference.
- **Updates itself** — Update → Check for Updates, then one button to install and restart.

### Pro features

A subscription or an activation code unlocks:

Slideshow · Colour picker · Batch rename · Batch format conversion · Crop & resize ·
Watermarking · Histogram · Lossless JPEG rotation · Contact-sheet export · Print layout ·
RAW preview · GPU filters

| Plan | Price |
|---|---|
| Pro Monthly | ₹20 / month |
| Pro Yearly | ₹220 / year |

Buy in-app (Peek → Subscription…), or redeem an activation code at
Peek → **Enter Activation Code…** (`⌘⇧K`). A code needs internet once, then
works offline for its whole term.

---

## Keyboard shortcuts

| | |
|---|---|
| `←` `→` | Previous / next image (wraps around) |
| `Space` | Next image |
| `Home` / `End` | First / last image |
| `⌘O` / `⌘⇧O` | Open image / open folder |
| `⌘N` | New window |
| `⌘B` | Toggle sidebar |
| `I` | Toggle info panel |
| `F` | Fullscreen |
| `⌘=` / `⌘-` | Zoom in / out |
| `⌘0` / `⌘1` | Fit to window / actual size |
| `⌘R` | Rotate right |
| `⌘⇧A` | Share / AirDrop |
| `⌘⇧R` | Reveal in Finder |
| `⌘⌫` | Move to Trash |
| `⌘W` / `⌘Q` | Close window / quit |

---

## Release notes

Every release carries full notes. See the [releases page](https://github.com/JKS-sys/peek-04-sep-2026-releases/releases), or fetch them directly:

- Markdown — `https://ipconfig.co.network/updates/peek/release-notes-1.0.9.md`
- JSON — `https://ipconfig.co.network/updates/peek/release-notes-1.0.9.json`
- Index of all releases — `https://ipconfig.co.network/updates/peek/release-notes.json`

---

## About this repository

This repo hosts **downloads and release notes only** — the source code is private.
If you hit a bug or want a feature, open an [issue](https://github.com/JKS-sys/peek-04-sep-2026-releases/issues);
it is read.

## Support the work

Peek is built and maintained by **Jagadeesh Kumar S** of
[NewsCraft Studio](https://www.youtube.com/@JKS-sys).

- Product page — https://ipconfig.co.network/peek
- Sponsor / donate — https://razorpay.me/@NSBJKS
- Email — JKS.sys@icloud.com

## Licence

Peek is proprietary software. © 2026 Jagadeesh Kumar S. All rights reserved.
The binaries here are free to download and use under the terms shown in-app;
they may not be redistributed, repackaged or resold.
