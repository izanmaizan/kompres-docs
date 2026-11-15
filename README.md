# Kompres

Aplikasi web untuk mengompres video, foto, dan PDF dengan beberapa level kompresi, bisa banyak berkas sekaligus.

## Kegunaan

- Kompres video (H.264/AAC), foto (JPG/PNG/WebP), dan PDF.
- Empat level: Ringan, Sedang, Kuat, Maksimal.
- Proses banyak berkas atau satu folder, termasuk subfolder.
- Progres real-time dan unduhan hasil.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Server | Node.js + Express, Multer |
| Pengolah | ffmpeg, Sharp, Ghostscript |
| Antarmuka | HTML/CSS/JS, progres lewat SSE |

## Alur singkat

1. Berkas diunggah dari browser.
2. Server memilih pengolah sesuai jenis berkas.
3. Progres dikirim balik ke browser.
4. Hasil diunduh; jika lebih besar dari asli, berkas asli dikembalikan.

## Ringkasan

| | |
|---|---|
| Mulai dikembangkan | September 2026 |
| Status | Selesai, dipakai untuk kebutuhan harian |

> Kode sumber tidak dipublikasikan. Repo ini hanya menjelaskan kegunaan, stack, dan alur kerja. Tidak ada data pengguna, data pasien, atau kredensial di sini.
