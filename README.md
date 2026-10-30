# Meera Edits

**A folder of raw clips in. A finished video out.**

Meera Edits is a free, open-source, offline AI video editor for Windows. Point it at a
folder of footage and it selects the best moments, drops junk and duplicates, keeps
speech intact, and renders polished exports — entirely on your own PC. No cloud,
no account, no subscription.

## Download

- **Website:** https://meeraedits.netlify.app
- **Latest installer:** [Releases](https://github.com/shubhamdreamworld/meera-edits-app/releases/latest)

Windows 10/11 (64-bit). Run the installer — ffmpeg and the AI models are bundled.
Every installer's SHA-256 is listed in [`site/releases.json`](site/releases.json) and on the
download page; check it with `Get-FileHash <file> -Algorithm SHA256` in PowerShell.

## Privacy

Analysis, AI and rendering run offline; your footage never leaves your PC. The only
optional internet use is the **"internet music"** setting: when you turn it on, Meera
downloads a public-domain ambient track from archive.org for the background bed (a fixed
search, nothing about your footage is sent). It is off by default; without it Meera
generates the music itself.

## Feedback

Feature requests and feedback: https://meeraedits.netlify.app/feedback.html

## Licence and source

Meera Edits is free and open source under the **MIT licence**. The application's source
code lives at https://github.com/shubhamdreamworld/meera-edits-app (`LICENSE` in that repo).
This repository holds only the website (`site/`) and the installer downloads attached to its
releases; it is published under the same MIT licence.

© 2026 Shubham Dreamworld — Meera Edits.
