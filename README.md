# MF-RLS — Rilis MediaForge untuk Windows

File unduhan ada di halaman **[Releases](../../releases/latest)**. Tiap file terpisah (bukan ZIP):

| File | Keterangan |
|---|---|
| `MediaForge-Setup-<versi>-x64.exe` | Installer: shortcut Start Menu dan desktop, uninstaller |
| `MediaForge-Portable-<versi>-x64.exe` | Portable: langsung jalan tanpa instal |
| `SHA256SUMS.txt` | Checksum untuk memastikan file tidak rusak |

Kebutuhan: Windows 10/11 64-bit, minimal Intel Celeron N4000, RAM 4 GB, HDD.
Sudah termasuk FFmpeg, yt-dlp, Deno, CDRDAO, dan VCDImager.

Saat pertama dijalankan, Windows SmartScreen bisa memberi peringatan karena EXE belum ditandatangani:
klik **More info → Run anyway**.

## Cara kerja repositori ini

Rilis dibuat otomatis oleh GitHub Actions (`.github/workflows/release.yml`) dari kode sumber
[4rixxr/MediaForge](https://github.com/4rixxr/MediaForge). Untuk merilis versi baru, ubah
`RELEASE_TAG` dan `SOURCE_REF` di `release.env` lalu commit ke `main`, atau jalankan workflow secara manual.
