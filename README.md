🏠 In the Kost — Sistem Informasi Kost Mobile & Web

Temukan tempat tinggal yang nyaman, mudah, dan sesuai kebutuhanmu!

In the Kost merupakan platform informasi dan pendaftaran sewa kost berbasis Flutter dan Web yang dirancang untuk mempermudah mahasiswa maupun pendatang dalam menemukan tempat tinggal ideal. Platform ini menghubungkan pencari kost dengan pemilik kost melalui informasi yang transparan, fitur pencarian yang praktis, dan akses komunikasi langsung.

<p align="center"> <img src="https://img.shields.io/badge/Flutter-Mobile-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter Mobile"/> <img src="https://img.shields.io/badge/PHP-Backend-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP Backend"/> <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL Database"/> <img src="https://img.shields.io/badge/Project-Academic-orange?style=for-the-badge" alt="Academic Project"/> </p>

<p align="center"> <b>Kelompok 5 · IF24B · Pemrograman Perangkat Bergerak (PBB)</b> </p>

📑 Daftar Isi
Tentang Proyek
Fitur Unggulan
Teknologi yang Digunakan
Implementasi Widget Flutter
Persyaratan Sistem
Cara Menjalankan Proyek
Struktur Tim
Dosen Pengampu
📌 Tentang Proyek

In the Kost adalah sistem informasi kost yang dikembangkan untuk membantu pengguna mencari dan memperoleh informasi tempat tinggal secara praktis melalui perangkat mobile maupun web.

Melalui platform ini, pengguna dapat menjelajahi berbagai pilihan kost, menyesuaikan pencarian berdasarkan kebutuhan, melihat detail fasilitas, serta menghubungi pemilik kost secara langsung melalui telepon atau WhatsApp.

Tidak hanya membantu pencari kost, In the Kost juga menyediakan fitur pengelolaan data bagi admin atau pemilik kost agar informasi properti dapat dikelola dengan lebih mudah.

🎯 Tujuan Pengembangan
Mempermudah pencarian kost berdasarkan lokasi, harga, dan fasilitas.
Menyediakan informasi kost yang terstruktur dan mudah dipahami.
Mempercepat komunikasi antara pencari kost dan pemilik.
Membantu pengelolaan data kost melalui sistem digital.
Mengimplementasikan teknologi mobile dan web dalam satu solusi informasi.
✨ Fitur Unggulan
🔍 1. Pencarian dan Filter Kost

Temukan kost yang sesuai dengan kebutuhan melalui filter pencarian berdasarkan:

Lokasi atau alamat.
Rentang harga sewa.
Fasilitas yang tersedia.
Jenis kost: putra, putri, atau campur.
🏡 2. Informasi Kost yang Lengkap

Dapatkan informasi sebelum menentukan pilihan, meliputi:

Galeri foto kost.
Alamat dan lokasi.
Daftar fasilitas.
Informasi harga sewa.
Ketersediaan kamar sesuai data yang dikelola sistem.
📱 3. Kontak Langsung Pemilik

Hubungi pemilik kost dengan lebih mudah melalui:

Panggilan telepon.
Chat WhatsApp.
🛠️ 4. Dashboard Admin dan Pemilik

Kelola informasi kost dengan operasi CRUD (Create, Read, Update, Delete), yang mencakup:

Menambahkan data kost baru.
Melihat dan mengelola informasi kost.
Memperbarui detail kost.
Menghapus data kost yang tidak diperlukan.
📲 5. Antarmuka Responsif

Antarmuka dirancang agar dapat menyesuaikan tata letak dengan ukuran layar perangkat yang didukung, sehingga pengalaman penggunaan lebih nyaman.

💻 Teknologi yang Digunakan
Teknologi	Peran
Flutter	Pengembangan aplikasi mobile
Dart	Bahasa pemrograman aplikasi Flutter
HTML	Struktur halaman web
CSS	Desain dan tata letak halaman web
JavaScript	Interaksi pada antarmuka web
PHP	Backend dan REST API
MySQL	Penyimpanan dan pengelolaan data
🧩 Implementasi Widget Flutter

Pengembangan antarmuka mobile memanfaatkan berbagai widget Flutter untuk menghasilkan tampilan yang terstruktur dan interaktif.

Widget	Fungsi
StatelessWidget	Membuat komponen yang tidak mengelola perubahan state internal, seperti tampilan statis dan kartu informasi
StatefulWidget	Membuat komponen yang memerlukan pengelolaan state, seperti formulir filter dan dashboard dinamis
Column	Menyusun komponen secara vertikal
Row	Menyusun komponen secara horizontal
ListView.builder	Menampilkan daftar kost secara efisien dan dapat di-scroll
Container	Mengatur ukuran, warna, margin, padding, dan dekorasi elemen
Card	Menampilkan informasi dalam bentuk kartu yang terstruktur
⚙️ Persyaratan Sistem

Sebelum menjalankan proyek, pastikan perangkat pengembangan telah memiliki:

Flutter SDK
Dart SDK (umumnya sudah disertakan dalam Flutter SDK)
Git
Web server yang mendukung PHP, misalnya XAMPP atau lingkungan sejenis
MySQL atau MariaDB
Browser modern atau emulator/perangkat Android untuk pengujian aplikasi mobile
🚀 Cara Menjalankan Proyek
1. Clone Repository

Unduh source code proyek dari GitHub:

git clone https://github.com/Mozithol/in-the-kost.git


Masuk ke direktori proyek:

cd in-the-kost

2. Jalankan Aplikasi Flutter

Masuk ke direktori aplikasi Flutter jika proyek memiliki folder khusus untuk aplikasi mobile.

cd nama-folder-flutter


Unduh seluruh dependensi:

flutter pub get


Periksa konfigurasi perangkat yang tersedia:

flutter devices


Jalankan aplikasi:

flutter run

Catatan: Ganti nama-folder-flutter dengan direktori aplikasi Flutter yang sebenarnya. Jika pubspec.yaml berada langsung di direktori utama repository, jalankan perintah Flutter dari direktori tersebut.
3. Konfigurasi Backend PHP dan MySQL
Jalankan Apache dan MySQL melalui XAMPP atau web server yang digunakan.
Tempatkan source code backend pada direktori web server sesuai konfigurasi lingkungan lokal.
Buat database MySQL untuk proyek.
Impor file database SQL jika tersedia di repository.
Sesuaikan konfigurasi koneksi database pada backend PHP.
Pastikan endpoint REST API dapat diakses oleh aplikasi.
4. Hubungkan Aplikasi dengan REST API

Sesuaikan alamat API pada aplikasi dengan lingkungan pengembangan yang digunakan.

Penting: Jika menggunakan emulator Android, localhost pada emulator merujuk ke emulator itu sendiri, bukan komputer host. Gunakan alamat host yang sesuai, misalnya 10.0.2.2 untuk Android Emulator standar atau alamat IP lokal komputer untuk perangkat fisik.

Catatan: Nama direktori, lokasi file konfigurasi, nama database, dan endpoint API perlu disesuaikan dengan struktur repository yang sebenarnya.

👥 Struktur Tim

Proyek ini dikembangkan oleh Kelompok 5 — Kelas IF24B untuk memenuhi tugas mata kuliah Pemrograman Perangkat Bergerak (PBB).

No.	Nama Anggota	NIM
1	Hafizh Akmal	240102037
2	Ken Harsya Lazuardi	240102047
3	Muhammad Fahd Ar Rizal	240102072
4	Muhammad Zivandya	240102088
5	Muhammad Viary	254025001
🎓 Dosen Pengampu

Vitradisa Pratama, S.ST., M.T.

Program Studi Teknik Informatika
Universitas Muhammadiyah Bandung
Tahun 2026

📚 Tujuan Akademik

Proyek ini disusun sebagai bagian dari pemenuhan tugas mata kuliah Pemrograman Perangkat Bergerak (PBB), dengan fokus pada penerapan konsep pengembangan aplikasi mobile, antarmuka pengguna, integrasi backend, dan pengelolaan basis data.

<p align="center"> <b>🏠 In the Kost — Temukan Kost, Temukan Kenyamanan.</b> <br/> Dikembangkan dengan semangat kolaborasi dan pembelajaran. </p>
