# 🏠 In the Kost

### Sistem Informasi Kost Berbasis Mobile dan Web

In the Kost adalah platform informasi kost yang membantu mahasiswa dan pendatang menemukan tempat tinggal sesuai kebutuhan. Proyek ini dikembangkan menggunakan Flutter, PHP, dan MySQL untuk memenuhi tugas mata kuliah Pemrograman Perangkat Bergerak (PBB).

---

## 📋 Daftar Isi

- [Tentang Proyek](#tentang-proyek)
- [Fitur Utama](#fitur-utama)
- [Teknologi](#teknologi-yang-digunakan)
- [Widget Flutter](#implementasi-widget-flutter)
- [Cara Menjalankan](#cara-menjalankan-proyek)
- [Tim Pengembang](#tim-pengembang)
- [Dosen Pengampu](#dosen-pengampu)

---

## 📌 Tentang Proyek

In the Kost merupakan sistem informasi yang mempermudah pencarian dan pengelolaan tempat tinggal atau kost melalui perangkat mobile dan web.

Pengguna dapat mencari kost berdasarkan lokasi, harga, fasilitas, dan jenis kost. Pengguna juga dapat melihat detail informasi serta menghubungi pemilik melalui telepon atau WhatsApp.

### 🎯 Tujuan

- Mempermudah pencarian tempat tinggal.
- Menyediakan informasi kost yang jelas.
- Memudahkan komunikasi antara pencari kost dan pemilik.
- Membantu pengelolaan data kost secara digital.
- Menerapkan teknologi mobile, web, dan basis data.

---

## ✨ Fitur Utama

### 🔍 Pencarian dan Filter

- Pencarian berdasarkan lokasi.
- Filter rentang harga.
- Filter fasilitas.
- Pilihan jenis kost: putra, putri, dan campur.

### 🏡 Informasi Kost

- Galeri foto kost.
- Informasi alamat dan harga.
- Daftar fasilitas.
- Informasi ketersediaan kamar berdasarkan data sistem.

### 📞 Kontak Pemilik

- Menghubungi pemilik melalui telepon.
- Mengirim pesan melalui WhatsApp.

### ⚙️ Dashboard Admin dan Pemilik

- Menambahkan data kost.
- Melihat daftar kost.
- Mengedit informasi kost.
- Menghapus data kost.

### 📱 Antarmuka Responsif

Tampilan dirancang untuk menyesuaikan ukuran layar perangkat yang didukung.

---

## 💻 Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| Flutter | Pengembangan aplikasi mobile |
| Dart | Bahasa pemrograman Flutter |
| HTML | Struktur halaman web |
| CSS | Desain antarmuka web |
| JavaScript | Interaksi halaman web |
| PHP | Backend dan REST API |
| MySQL | Basis data |

---

## 🧩 Implementasi Widget Flutter

| Widget | Fungsi |
|---|---|
| `StatelessWidget` | Membuat komponen tanpa state internal yang berubah |
| `StatefulWidget` | Membuat komponen yang mengelola perubahan state |
| `Column` | Menyusun elemen secara vertikal |
| `Row` | Menyusun elemen secara horizontal |
| `ListView.builder` | Menampilkan daftar yang dapat di-scroll |
| `Container` | Mengatur ukuran, warna, jarak, dan dekorasi |
| `Card` | Menampilkan informasi dalam bentuk kartu |

---

## 🚀 Cara Menjalankan Proyek

### 1. Clone Repository

```bash
git clone https://github.com/Mozithol/in-the-kost.git
cd in-the-kost
```

### 2. Jalankan Aplikasi Flutter

Buka direktori yang berisi file `pubspec.yaml`, lalu jalankan:

```bash
flutter pub get
flutter run
```

Pastikan Flutter SDK dan perangkat atau emulator sudah tersedia.

### 3. Konfigurasi Backend

1. Jalankan Apache dan MySQL melalui XAMPP atau web server yang digunakan.
2. Tempatkan source code PHP pada direktori web server.
3. Buat database MySQL sesuai konfigurasi proyek.
4. Impor file SQL jika tersedia.
5. Sesuaikan konfigurasi koneksi database.
6. Pastikan REST API dapat diakses oleh aplikasi.

> **Catatan:** Sesuaikan direktori, nama database, dan alamat API dengan struktur proyek yang sebenarnya.

---

## 👥 Tim Pengembang

**Kelompok 5 — Kelas IF24B**

| No. | Nama | NIM |
|:---:|---|:---:|
| 1 | Hafizh Akmal | 240102037 |
| 2 | Ken Harsya Lazuardi | 240102047 |
| 3 | Muhammad Fahd Ar Rizal | 240102072 |
| 4 | Muhammad Zivandya | 240102088 |
| 5 | Muhammad Viary | 254025001 |

---

## 🎓 Dosen Pengampu

**Vitradisa Pratama, S.ST., M.T.**

- **Program Studi:** Teknik Informatika
- **Universitas:** Universitas Muhammadiyah Bandung
- **Tahun:** 2026
- **Mata Kuliah:** Pemrograman Perangkat Bergerak (PBB)

---

<p align="center">
  <strong>🏠 In the Kost</strong><br>
  Temukan Kost, Temukan Kenyamanan.<br><br>
  Dikembangkan oleh Kelompok 5 IF24B · 2026
</p>
