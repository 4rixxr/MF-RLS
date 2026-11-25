# TonePix [Beta Ver.] for Windows

**TonePix** (sebelumnya bernama **MediaForge**) adalah aplikasi desktop native untuk Windows. Satu aplikasi untuk:
- unduh dan konversi media;
- editor video multi-track;
- Audio Studio dan Retune;
- pemisah vokal AI;
- Image Studio (foto + vektor);
- pemutar musik dengan lirik;
- pembakar CD/DVD/VCD.

**Gratis, tanpa membership, tanpa akun, tanpa iklan.**

Penjelasan lengkap fitur ada di README kode sumber: [4rixxr/MediaForge](https://github.com/4rixxr/MediaForge#readme).

## Unduh

File ada di halaman **[Releases](../../releases/latest)**. Tiap file terpisah (bukan ZIP):

| File | Keterangan |
|---|---|
| `TonePix-Setup-<versi>-x64.exe` | Installer: shortcut Start Menu dan desktop, uninstaller, asosiasi file proyek |
| `TonePix-Portable-<versi>-x64.exe` | Portable: langsung jalan tanpa instal, data disimpan di samping program |
| `SHA256SUMS.txt` | Checksum untuk memastikan file tidak rusak |

Rilis v2.0.0 – v4.0.0 masih memakai nama lama (`MediaForge-…exe`). Mulai v4.1.0 semua file bernama TonePix.
Bila MediaForge masih terpasang, installer TonePix menawarkan untuk menghapusnya. Pengaturan, riwayat, dan proyek
Anda tetap ada dan dipindahkan otomatis.

Kebutuhan: Windows 10/11 64-bit, minimal Intel Celeron N4000, RAM 4 GB, HDD.
Sudah termasuk FFmpeg, yt-dlp, Deno, CDRDAO, dan VCDImager.

Saat pertama dijalankan, Windows SmartScreen bisa memberi peringatan karena EXE belum ditandatangani:
klik **More info → Run anyway**.

## Cara kerja repositori ini

Rilis dibuat otomatis oleh GitHub Actions (`.github/workflows/release.yml`) dari kode sumber
[4rixxr/MediaForge](https://github.com/4rixxr/MediaForge). Workflow tersebut:
- membangun aplikasi;
- menjalankan self-test;
- menerbitkan installer, portable, dan checksum.

Coming soon porting to MacOS, iOS, Android & OxygenOS.
