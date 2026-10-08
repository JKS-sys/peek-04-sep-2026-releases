# Changelog

Release notes are built from this file. Write the next release's notes under
`## Unreleased`; `update.sh` publishes them under whatever version it bumps to.
After a release, rename the heading to that version and start a new
`## Unreleased`.

## 2.0.12 — 2026-10-08

- **New look, from the icon.** The app icon's eyes are now gold, and the light and dark themes are the icon's own tiles — Anti-Flash White and warm near-black — with the same gold as the accent. Buttons, highlights and the Peek wordmark follow it.
- **Owner Panel** (Peek › Owner Panel…, ⌥⌘K) replaces the Owner Console and opens in its own window on the owner's Mac. No admin token: the Mac's serial is the credential.
  - **Subscriptions tab:** every Razorpay subscription with customer, plan, period, next charge and payments. Cancel now or at period end, pause, resume, switch plan, or create a new subscription link for a customer.
  - **Crash reports tab:** reports users sent in and the logs on this Mac, side by side — readable, deletable, and exportable as .md or .txt (one or all).
  - Codes and subscriptions export too.
- **Live welcome screen.** The eyes follow your pointer and blink; a zoom read-out pops up when you zoom; rotate and flip animate; the slideshow shows a progress line.
- **More sounds** — soft ticks for next/previous and zoom, a whirr for rotate, chimes when a slideshow starts and when an update is ready. All off with one click.
- Releases publish the full release notes as `RELEASE-NOTES.md` on GitHub and `release-notes.md` on R2, and every previous release's files are removed from GitHub and R2 once the new one is complete.
- The GitHub README shows the light and dark icons (and switches with your GitHub theme).

- **Sidebar: one click opens an image** — and the list stays put. Opening an image used to unfold every folder from "/" down to it, pushing rows in above the one you clicked, so the click seemed to do nothing.
- **Delete images from the sidebar.** Select one or more and press Delete (⌫), use the Delete button, or right-click › Move to Trash. They go to the Trash, the next image is selected, and if you were viewing one of them Peek moves on to the next.
- **Folders with no images are hidden** in the sidebar, including folders whose only pictures are inside apps or `node_modules`.
- **The sidebar no longer freezes or crashes Peek.** Folder scans no longer block the rest of the app, a slow or network drive can hold up the list for at most a moment, and if the sidebar ever fails it resets itself instead of blanking the window.
- **Colour-coded everywhere.** Each image type has its own colour — the sidebar icon, the file name, the bottom bar and Image Info all match (JPEG orange, PNG blue, WebP green, GIF violet, HEIC teal, SVG amber). Numbers, brackets, codes, menu actions and every Image Info row are coloured too, in light and dark mode.
- **Sound effects** for delete, copy, share, activation and more — short and quiet, and off with one click (the speaker in the bottom bar, or ⌥⌘S).
- **Smoother:** images fade in, panels and menus open with a little motion, and the start screen has a new animated background. All of it switches off if your Mac is set to reduce motion.
- **Keyboard shortcuts sheet** — press ? or ⌘/.
- **Crash reports.** If Peek ever closes unexpectedly, it offers to send a report next time — you see exactly what is in it first, with your name and home folder removed. Also in Help › Report a Problem….
- Move to Trash no longer depends on Finder automation permission, which could make it silently fail.
- Activation codes can now be lifetime, a set number of days, monthly or yearly. A code that is cancelled stops working at the next launch.
- **Smaller app** — about 750 KB of unused icons and a duplicate font removed from inside the app.
- **Install with one line:** `curl -fsSL https://ipconfig.co.network/updates/peek/install.sh | bash` on macOS and Linux, or `irm https://ipconfig.co.network/updates/peek/install.ps1 | iex` on Windows.
- **Windows installer and Linux AppImage/.deb**, with automatic updates on both.
- **Move to…** in the sidebar's right-click menu — send the selected images to any folder. Existing files are never overwritten; a clash becomes "name 2".

## 2.0.5 — 2026-09-27


- **Opening an image from Finder** shows that image in one window — no more duplicate or blank windows when opening several at once.
- **Menu commands only affect the window you're in.** Previously, with several windows open, commands like Move to Trash acted on every window.
- **Large images no longer crash Peek.** Very large photos open as a sharp preview instead of exhausting memory.
- **Updates download once.** An update you have not installed yet is not downloaded again when you reopen Peek, and Install & Restart is now quick and reliably brings Peek back.
- **Subscriptions** work again — Monthly ₹20 or Yearly ₹220 through Razorpay.
- The version number now shows on the start screen, in the bottom bar and in the info panel.
- **Reopens what you had open.** Quit with several images open and they all come back next launch.
- **Windows and Linux builds.**
- Updates now try three sources, so a slow or unreachable one no longer means "could not reach the update server".
- **Sidebar search**, and clicking a folder now opens or closes it — one click, whether it is a folder or an image.
- **Big folders no longer freeze the sidebar.** Opening /Volumes or a Downloads folder with thousands of files is now instant; very large folders show the first 4,000 items and say how many are left.
- **A folder you close stays closed.** Collapsing the folder holding the image you are viewing used to spring open again on the next arrow key.
- Folders no longer appear twice in the sidebar.
- New app icon, and a Sponsor link if you'd like to support Peek.
