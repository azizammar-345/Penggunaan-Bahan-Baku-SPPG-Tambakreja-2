# MBG Smart Kitchen

Prototipe aplikasi web untuk perencanaan bahan baku, database resep, riwayat produksi, evaluasi kesukaan menu, food waste, rekomendasi menu, dan ekspor data.

## Menjalankan secara lokal

1. Unduh atau clone repository ini.
2. Buka `index.html` menggunakan browser modern (Chrome, Edge, atau Firefox).

## Publikasi menggunakan GitHub Pages

1. Buat repository baru di GitHub, misalnya `mbg-smart-kitchen`.
2. Unggah seluruh isi folder ini ke root repository:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. Buka **Settings → Pages** pada repository.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu tekan **Save**.
6. Tunggu proses deployment selesai. GitHub akan menampilkan alamat situs pada bagian Pages.

Jika nama repository bukan `username.github.io`, alamat situs umumnya:
`https://USERNAME.github.io/NAMA-REPOSITORY/`

## Catatan penting tentang data

- Prototipe ini menyimpan data menggunakan `localStorage` pada browser/perangkat yang sedang digunakan.
- Data tidak otomatis tersinkron antar pengguna atau perangkat, meskipun situs sudah dipublikasikan melalui GitHub Pages.
- Bersihkan cache/data situs atau gunakan browser/perangkat lain dapat menyebabkan data lokal tidak tersedia. Gunakan menu **Laporan & Data → Unduh backup JSON** secara berkala.
- Fitur login dan hak akses yang terlihat pada prototipe masih berupa rancangan tampilan, belum autentikasi sungguhan.
- Untuk penggunaan multiuser operasional, perlu ditambahkan backend/database online, autentikasi, aturan akses, validasi data, serta backup server.
- Angka resep contoh harus divalidasi Ahli Gizi dan disesuaikan dengan standar produksi SPPG sebelum digunakan untuk pengadaan atau produksi.

## Struktur proyek

```text
mbg-smart-kitchen/
├── index.html
├── .nojekyll
└── README.md
```
