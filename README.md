# In the kost — Mobile & Web Sistem Informasi Kost

> **Aplikasi Portal Informasi & Pendaftaran Sewa Kost Berbasis Flutter**  
> Disusun untuk memenuhi Tugas Mata Kuliah Pemrograman Perangkat Bergerak (PBB).

---

## Kelompok 5 (Kelas IF24B / PBB)
1. **Hafizh Akmal** - 240102037
2. **Ken Harsya Lazuardi** - 240102047
3. **Muhammad Fahd Ar Rizal** - 240102072
4. **Muhammad Zivandya** - 240102088
5. **Muhammad Viary** - 254025001

**Dosen Pengampu:** Vitradisa Pratama, S.ST., M.T.  
**Program Studi:** Teknik Informatika — Universitas Muhammadiyah Bandung (2026)

---

## Tentang Project
**In the kost** adalah platform terpadu yang dirancang untuk mempermudah pencarian dan pengelolaan tempat tinggal (kost) bagi mahasiswa dan pendatang. Sistem ini menghubungkan pencari kost dengan pemilik kost secara transparan melalui fitur pencarian, filter harga/fasilitas, hingga kontak langsung via Telepon atau WhatsApp.

---

## Fitur Utama System
- **Pencarian & Filter Spesifik:** Filter berdasarkan lokasi, rentang harga, kriteria fasilitas, dan jenis kost (Putra/Putri/Campur).
- **Detail Informasi Transparan:** Galeri foto, alamat lengkap, daftar fasilitas, dan ketersediaan kamar secara *real-time*.
- **Kontak Direct Pemilik:** Integrasi langsung ke tombol Telepon dan Chat WhatsApp pemilik kost.
- **Dashboard Admin / Pemilik:** Fitur *CRUD* (Tambah, Edit, Hapus) data kost secara mandiri.
- **Tampilan Responsif:** Penyesuaian tata letak otomatis untuk perangkat *Mobile* dan *Tablet*.

---

## Arsitektur & Spesifikasi Teknis
- **Frontend Mobile:** Flutter (Bahasa Dart)
- **Frontend Web:** HTML, CSS, JavaScript, PHP
- **Backend & API:** PHP REST API
- **Database:** MySQL

---

## Implementasi Widget Flutter (Panduan Dasar)
Dalam pengembangan antarmuka aplikasi **In the kost**, digunakan kombinasi berbagai widget Flutter:
- **`StatelessWidget`**: Digunakan pada layar statis seperti *Splash Screen* dan item *Card* daftar kost.
- **`StatefulWidget`**: Digunakan pada komponen dinamis seperti *Form Filter Pencarian* dan *Dashboard Admin*.
- **`Column` & `Row`**: Menyusun tata letak elemen secara vertikal dan horizontal.
- **`ListView.builder`**: Menampilkan daftar rekomendasi kost secara efisien dan dapat di-scroll.
- **`Container` & `Card`**: Pembungkus elemen UI dengan warna, *border radius*, dan bayangan (*box shadow*).

---

## Cara Menjalankan Project (Getting Started)

1. **Clone Repository ini:**
   ```bash
   git clone [https://github.com/Mozithol/in-the-kost.git](https://github.com/Mozithol/in-the-kost.git)
