# Platform Komunitas & Kegiatan Siswa

Proyek statis contoh: platform untuk menampilkan komunitas, kegiatan, anggota, penempatan, dan fitur client-side tambahan seperti jam pengingat dan akun profil.

File penting
- `index.html` — Halaman utama (memuat Jam Pengingat).
- `komunitas.html` — Halaman komunitas (dengan daftar yang dapat diedit).
- `kegiatan.html` — Halaman kegiatan (daftar kegiatan dapat diedit).
- `anggota.html` — Halaman profil / akun (atur nama, email, avatar).
- `eskul.html` — Halaman Eskul (informasi & daftar eskul dapat diedit).
- `penempatan.html` — Penempatan & sub-bab.
- `css/styles.css` — Gaya dan varian tema untuk masing-masing bab.
- `js/main.js` — Interaktivitas ringan (navigasi, smooth scroll).
- `js/app.js` — Fitur aplikasi: profile, reminders, data lists (menggunakan localStorage).

Cara menjalankan
1. Buka folder proyek ini di VS Code atau File Explorer.
2. Pilih salah satu:
   - Double-click `index.html` di File Explorer untuk membuka di browser.
   - Atau: di VS Code, install ekstensi Live Server, buka `index.html`, lalu klik "Go Live".

Fitur utama (client-side)
- Jam Pengingat (index): tambahkan pengingat berdasarkan jam:menit. Saat waktunya tiba, audio diputar dan notifikasi/alert ditampilkan. Pengingat disimpan di localStorage.
- Akun Profil (anggota.html): atur nama, email, dan avatar; data disimpan di localStorage.
- Eskul/Kegiatan/Komunitas: setiap halaman memiliki daftar yang dapat diedit (ditambahkan/dihapus) dan disimpan di localStorage.
- Tema visual: setiap sub-bab mendapat sedikit varian warna (tema) agar tampil berbeda.

Catatan pengembangan
- Semua data disimpan hanya di browser (localStorage). Untuk fitur nyata (auth, penyimpanan terpusat), tambahkan backend (Node/Express + DB) atau gunakan Firebase.
- Bila mau, saya bisa: menambahkan halaman admin, validasi form, export/import data, atau menyiapkan deploy (GitHub Pages / Netlify).

Butuh bantuan lanjutan?
- Jika Anda ingin saya tambahkan: form pendaftaran Eskul (menyimpan ke localStorage), halaman admin untuk mengelola semua data, atau deploy ke GitHub Pages — beri tahu mana yang mau ditambahkan.
