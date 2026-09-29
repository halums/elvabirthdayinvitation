# Undangan Elva's Sweet 17

Undangan digital (satu file `index.html`, tanpa build).

## Ganti lagu
1. Taruh file MP3 kamu di folder `music/` dengan nama `lagu.mp3`
   (atau pakai nama lain, lalu ubah `var SONG="music/lagu.mp3"` di `index.html`).
2. Commit & push.

Kalau file lagu tidak ditemukan, otomatis diputar melodi kotak musik bawaan.
Catatan: pakai lagu yang kamu punya hak/izin pakainya, dan usahakan ukuran file < 10 MB agar cepat dimuat.

## Publish lewat GitHub Pages
1. Buat repo baru di GitHub, lalu dari folder ini:
   ```bash
   git init
   git add .
   git commit -m "Undangan Elva"
   git branch -M main
   git remote add origin https://github.com/USERNAME/NAMA-REPO.git
   git push -u origin main
   ```
2. Di GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main** / folder **/ (root)** → Save
3. Tunggu ±1 menit, link undangan: `https://USERNAME.github.io/NAMA-REPO/`
