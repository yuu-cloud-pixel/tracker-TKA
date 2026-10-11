# Tracker TKA 20 Hari (Aplikasi Desktop)

## Cara menjalankan
1. Install Node.js (https://nodejs.org), pilih versi LTS.
2. Buka terminal/CMD di folder ini, lalu jalankan:
   npm install
   npm start

## Cara membuat file installer (.exe / .dmg / .AppImage)
   npm run build
Hasilnya ada di folder `dist/`. Bangun installer di sistem operasi yang sama
dengan targetnya (.exe di Windows, .dmg di macOS, .AppImage di Linux).

## Catatan
- Progres tersimpan otomatis di komputer kamu (data aplikasi), jadi tidak hilang saat aplikasi ditutup.
- Untuk mengubah materi atau tampilan, edit file index.html.
