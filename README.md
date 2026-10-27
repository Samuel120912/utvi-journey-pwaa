# UTVI-Journey — Prototipe Web/PWA

Prototipe awal berdasarkan makalah *New Process Innovation (Gamification Innovation)*.

## Fitur prototipe
- Dashboard ringkas dan level XP
- Pelaporan Lean/Waste
- Database temuan dengan filter pencarian, kategori, dan status
- Pembaruan Plan, Action, Result, progres, dan catatan komite
- Leaderboard demo
- Tampilan evaluasi komite / IC
- Ekspor CSV
- PWA manifest dan service worker untuk penggunaan offline dasar

## Cara menjalankan
1. Ekstrak ZIP.
2. Untuk uji cepat, buka `index.html` di browser modern.
3. Untuk menguji kemampuan PWA/service worker, jalankan melalui server lokal atau hosting HTTPS. Service worker tidak berjalan saat file dibuka langsung dengan `file://`.
4. Untuk hosting, unggah isi folder ini ke GitHub Pages atau web hosting statis HTTPS.

## Data dan batasan penting
- Semua data tersimpan di `localStorage` browser/perangkat yang sedang dipakai.
- Data tidak tersinkron ke pengguna lain, cabang, atau site.
- Login, otorisasi peran, database pusat, lampiran foto, notifikasi, dan validasi manfaat belum diimplementasikan.
- XP/ranking adalah nilai demo, bukan skema resmi. Skema poin final perlu disepakati bersama pemilik proses/komite.
- Jangan memasukkan data rahasia perusahaan, data personal sensitif, atau informasi operasional yang dibatasi ke prototipe ini.

## Langkah sebelum pilot lintas cabang/site
1. Tentukan sponsor bisnis dan pemilik produk.
2. Validasi kategori, status, matriks XP, kriteria penilaian, serta definisi manfaat/ROI.
3. Tentukan metode login/SSO dan kontrol akses sesuai standar IT/security perusahaan.
4. Pilih backend/database terpusat dan kebijakan retensi data.
5. Pilot di satu departemen/site, ukur partisipasi, waktu siklus, improvement tervalidasi, dan dampak.
6. Lakukan security review dan persetujuan tim IT sebelum penggunaan perusahaan.
