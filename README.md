<p align="center">
  <img src="assets/tonepix-logo.png" alt="TonePix logo" width="180">
</p>

<h1 align="center">TonePix</h1>

<p align="center"><i>An all-in-one media studio for Windows</i></p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/latest-v4.1.0-3fb950?style=for-the-badge" alt="Latest version 4.1.0"></a>
  <a href="../../releases"><img src="https://img.shields.io/github/downloads/4rixxr/TonePix/total?style=for-the-badge&color=1f6feb" alt="Total downloads"></a>
  <img src="https://img.shields.io/badge/windows-10%20%7C%2011%20(64--bit)-0078d4?style=for-the-badge" alt="Windows 10/11 64-bit">
  <img src="https://img.shields.io/badge/price-free-a371f7?style=for-the-badge" alt="Free">
  <img src="https://img.shields.io/badge/status-beta-d29922?style=for-the-badge" alt="Beta">
  <a href="https://discord.gg/xQJhRzS36D"><img src="https://img.shields.io/badge/discord-join-5865f2?style=for-the-badge&logo=discord&logoColor=white" alt="Join our Discord"></a>
</p>

TonePix (formerly **MediaForge**) is a native Windows desktop application that brings media downloading,
conversion, video, audio and image editing, music playback and disc burning together in one place.

**Free. No membership, no account, no ads.**

- [FEATURES](#features)
- [DOWNLOAD](#download)
  - [Release files](#release-files)
  - [Verify your download](#verify-your-download)
- [SYSTEM REQUIREMENTS](#system-requirements)
- [INSTALLATION](#installation)
  - [Upgrading from MediaForge](#upgrading-from-mediaforge)
- [VERSION HISTORY](#version-history)
- [FAQ](#faq)
- [ROADMAP](#roadmap)
- [THIRD-PARTY COMPONENTS](#third-party-components)

## Features

| Tool | What it does |
|---|---|
| **Downloader & Converter** | Download and convert media |
| **Video Editor** | Multi-track video editing |
| **Audio Studio** | Audio editing with Retune |
| **AI Vocal Remover** | Separate vocals from a track |
| **Image Studio** | Layered photo editing and vector design |
| **Music Player** | Offline playback with online lyrics |
| **Disc Burner** | Burn CD, DVD and VCD |

## Download

Get the newest build from the **[Releases page](../../releases/latest)**.

### Release files

| File | Description |
|---|---|
| `TonePix-Setup-<version>-x64.exe` | Installer with Start Menu and desktop shortcuts, uninstaller and project file association |
| `TonePix-Portable-<version>-x64.exe` | Portable build: runs without installing and keeps its data next to the program |
| `SHA256SUMS.txt` | Checksums to confirm your download is intact |

> Releases v2.0.0 to v4.0.0 use the old file names (`MediaForge-…exe`). From v4.1.0 onward, files are named TonePix.

### Verify your download

Run this in Command Prompt, then compare the result with `SHA256SUMS.txt`:

```bat
certutil -hashfile TonePix-Setup-<version>-x64.exe SHA256
```

## System requirements

| | Minimum |
|---|---|
| **OS** | Windows 10 or 11, 64-bit |
| **CPU** | Intel Celeron N4000 |
| **RAM** | 4 GB |
| **Storage** | HDD is supported |

FFmpeg, yt-dlp, Deno, CDRDAO and VCDImager are already bundled.

## Installation

1. Download the **Setup** or **Portable** file.
2. Run it.
3. Windows SmartScreen may warn you because the EXE is not code-signed yet. After confirming the file came
   from this repository, click **More info → Run anyway**.

### Upgrading from MediaForge

If MediaForge is still installed, the TonePix installer offers to remove it. Your settings, history and
projects are kept and migrated automatically.

## Version history

| Version | Highlight |
|---|---|
| **v4.1.0** | MediaForge is now TonePix |
| **v4.0.0** | Image Studio: layered photo editing and vector design |
| **v3.0.0** | Audio Studio |
| **v2.2.0** | AI vocal remover |
| **v2.1.0** | Offline Music Player with online lyrics |
| **v2.0.0** | Installer and portable builds |

## FAQ

**Is TonePix really free?**
Yes. There is no membership, account or advertising.

**Setup or Portable?**
Choose Setup for shortcuts and file association. Choose Portable to run it without installing.

**Found a bug?**
Open an [issue](../../issues) or tell us on [Discord](https://discord.gg/xQJhRzS36D). Include your TonePix version, Windows version and the steps to reproduce it.

## Roadmap

Coming soon:

- [ ] macOS
- [ ] iOS
- [ ] Android
- [ ] OxygenOS

## Third-party components

Each component is covered by its own license.

- [FFmpeg](https://ffmpeg.org/legal.html)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [Deno](https://github.com/denoland/deno)
- [CDRDAO](https://github.com/cdrdao/cdrdao)
- [VCDImager](https://www.gnu.org/software/vcdimager/)

Only download content that you have the right to download.

---

<p align="center">
  <b>Created by FindX Studios.</b>
</p>

<p align="center">
  <img src="assets/findx-studios.png" alt="FindX Studios" width="720">
</p>
