# Project Plan — Business Management System (BMS)

## 1. Tentang Proyek

**Business Management System (BMS)** adalah aplikasi web untuk membantu mengelola bisnis jual-beli berbagai jenis barang elektronik.

Tujuan utamanya adalah mencatat stok, pembelian, penjualan, keuangan, dan keuntungan agar kondisi bisnis mudah dipantau.

## 2. Fitur MVP

Fokus pada fitur yang benar-benar dibutuhkan:

1. **Produk & Inventaris** — mengelola data produk dan persediaan. Stok dapat dicatat per unit jika perlu serial number, atau berdasarkan jumlah.
2. **Pembelian** — mencatat barang masuk, harga beli, sumber/pemasok, dan biaya tambahan.
3. **Penjualan** — mencatat barang keluar, harga jual, pelanggan, metode pembayaran, dan keuntungan.
4. **Arus Kas** — mencatat seluruh uang masuk dan uang keluar serta memantau saldo kas bisnis.
5. **Pengeluaran** — mencatat biaya operasional dan biaya lain yang berkaitan dengan bisnis.
6. **Prive & Modal** — mencatat penarikan uang untuk kebutuhan pribadi (prive) dan penambahan modal ke bisnis.

## 3. Teknologi

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **ORM:** Prisma
- **Validasi:** Zod
- **API:** REST

## 4. Arsitektur dan Deployment

Aplikasi terdiri dari frontend dan backend yang terhubung melalui REST API.

- Frontend: tampilan dan interaksi pengguna.
- Backend: API, aturan bisnis, dan perhitungan.
- Database: menyimpan data aplikasi.
- File produk/bukti transaksi: disimpan di server lokal.

## 5. Pembagian Tugas

- **Backend:** database, API, proses pembelian/penjualan, stok, dan perhitungan keuangan.
- **Frontend:** tampilan, form, tabel, dashboard, dan integrasi API.

## 6. Urutan Pengerjaan

1. Siapkan struktur project dan database.
2. Buat prototype tampilan dan sepakati alur halaman.
3. Buat produk dan pengelolaan stok.
4. Buat pembelian dan penjualan.
5. Buat pencatatan keuangan.
6. Buat dashboard dan laporan.
7. Uji alur utama dan jalankan di server lokal.

## 7. Aturan Penting

- Stok harus berubah otomatis saat pembelian atau penjualan dicatat.
- Sistem mendukung stok per unit dan stok berdasarkan jumlah.
- Saldo kas berbeda dari keuntungan.
- Prive mengurangi kas, tetapi bukan biaya operasional.
- Modal tambahan menambah kas, tetapi bukan omzet.
- Perhitungan keuntungan menggunakan harga pokok barang yang tercatat saat transaksi.

## 8. Pengembangan Berikutnya

Setelah MVP berjalan dan kebutuhan nyata sudah terlihat, baru pertimbangkan fitur tambahan seperti garansi/komplain, laporan yang lebih lengkap, atau akses dari luar jaringan lokal.

---

**Status:** Perencanaan MVP. Dokumen ini dibuat sesederhana mungkin dan dapat diperbarui jika kebutuhan bisnis berubah.
