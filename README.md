# 🏪 Sistem Operasional Toko Boga Jaya

Aplikasi desktop manajemen operasional toko grosir bahan makanan, dibangun menggunakan **Python (Tkinter)** dan **MySQL**. Proyek ini dibuat sebagai tugas akhir mata kuliah pemrograman.

---

## 📋 Deskripsi

**Sistem Operasional Toko Boga Jaya** adalah aplikasi GUI berbasis desktop yang dirancang untuk membantu pengelolaan operasional toko grosir secara terintegrasi. Aplikasi ini menghubungkan antarmuka pengguna (GUI) dengan basis data relasional MySQL untuk menyimpan dan mengelola data secara persisten.

---

## ✨ Fitur Utama

| Modul | Fungsi |
|---|---|
| **Penjualan** | Catat transaksi penjualan, hitung subtotal & total otomatis, kelola detail barang per transaksi |
| **Stok Barang** | Lihat dan kelola inventaris barang beserta harga jual |
| **Pengeluaran** | Catat pengeluaran toko (pembelian dari pemasok, gaji pegawai, dll.) |
| **Pengiriman** | Kelola status pengiriman dan penugasan kurir |
| **Pemasok** | Manajemen data pemasok dan riwayat pemasokan barang |
| **Pegawai** | Kelola data pegawai beserta posisi dan gaji |
| **Pelanggan Grosir** | Simpan data pelanggan grosir beserta alamat lengkap |

Setiap modul mendukung operasi **CRUD** penuh:
- ➕ **Create** — tambah data baru dengan Auto ID
- 🔍 **Find** — cari data berdasarkan ID
- ✏️ **Update** — perbarui data yang dipilih dari tabel
- 🗑️ **Delete** — hapus data dengan konfirmasi

---

## 🛠️ Teknologi yang Digunakan

- **Python 3** — bahasa pemrograman utama
- **Tkinter** — library GUI bawaan Python untuk tampilan antarmuka
- **MySQL** — sistem manajemen basis data relasional
- **mysql-connector-python** — koneksi Python ke MySQL

---

## 🗄️ Struktur Database

Database `tokobogajaya` terdiri dari **13 tabel** yang saling berelasi:

```
barang              — Data produk/barang
penjualan           — Header transaksi penjualan
detail_penjualan    — Detail item per transaksi
pemasok             — Data supplier
detail_pemasokan    — Riwayat pengadaan barang
pelanggan_grosir    — Data pelanggan grosir
pengiriman          — Data pengiriman
pengantaran         — Relasi pegawai & pengiriman
kiriman             — Relasi pelanggan & pengiriman
pesanan             — Relasi penjualan & pengiriman
pegawai             — Data karyawan
pekerjaan           — Posisi & gaji pekerjaan
gudang              — Data gudang penyimpanan
penyimpanan         — Relasi barang & gudang
pengeluaran         — Catatan pengeluaran toko
```

---

## 👤 Author

Dibuat sebagai **Tugas Akhir Mata Kuliah Intermediate Programming** — *[Grace L.R. Pangaribuan dan Gloriana Monica]*

---

Tampilan:

<img width="742" height="471" alt="image" src="https://github.com/user-attachments/assets/49e828d9-8acd-44b5-804c-b10d989573dd" />

