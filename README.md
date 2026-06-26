# Foode Master - Premium F&B Web Application

[![PHP Version](https://img.shields.io/badge/php-%5E8.0-blue.svg)](https://www.php.net/)
[![Bootstrap](https://img.shields.io/badge/bootstrap-v5.3-purple.svg)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Foode Master** adalah platform web premium yang dirancang khusus untuk industri Food & Beverage (F&B). Mengusung konsep visual yang *simpel, elegan, dan premium*, website ini mengombinasikan estetika modern dengan performa backend yang tangguh untuk memberikan pengalaman terbaik bagi pelanggan dalam menjelajahi menu kuliner kelas dunia.

## 🌟 Filosofi Desain & Kombinasi Visual

Website ini dibangun dengan pendekatan minimalis namun tetap memancarkan kesan mewah (*premium feel*):
* **Simpel (Simple):** Tata letak (layout) yang bersih tanpa distrasi visual yang tidak perlu. Kami mengutamakan kemudahan navigasi agar pengguna dapat menemukan menu favorit mereka dalam hitungan detik.
* **Elegan (Elegant):** Penggunaan tipografi yang anggun (sans-serif modern dikombinasikan dengan serif premium), transisi elemen yang halus, dan pemanfaatan *whitespace* (ruang kosong) yang proporsional untuk menciptakan harmoni.
* **Premium:** Palet warna yang dikurasi secara eksklusif (perpaduan *deep charcoal/matte black*, aksen emas redup/*warm gold*, dan latar belakang putih bersih) berpadu dengan fotografi makanan resolusi tinggi yang menggugah selera.

## 🛠️ Tech Stack & Fitur Utama

### Teknologi yang Digunakan:
* **Frontend:** HTML5, CSS3, **Bootstrap 5** (untuk tata letak responsif, sistem grid, dan komponen UI modern), JavaScript (ES6 / Vanilla JS untuk interaksi dinamis).
* **Backend:** **PHP Native / OOP** (Pemrosesan logika bisnis, manajemen sesi, keamanan, dan routing data).
* **Database:** MySQL (Penyimpanan data produk, kategori menu, reservasi meja, dan data pengguna).
* **Pendukung:** FontAwesome Icons & Google Fonts (Playfair Display & Inter/Roboto).

### Fitur Utama:
1.  **Premium Digital Menu:** Katalog menu interaktif dengan filter kategori dinamis, deskripsi mendalam, serta visualisasi yang eksklusif.
2.  **Table Reservation System:** Sistem reservasi meja online yang simpel dan intuitif, lengkap dengan validasi kapasitas dan waktu.
3.  **Responsive Layout:** Pengalaman pengguna yang konsisten dan luar biasa di semua resolusi layar, baik ponsel pintar, tablet, maupun desktop.
4.  **Admin Dashboard (CMS):** Panel kontrol bagi manajemen untuk mengubah harga, menambah menu baru, dan mengelola data reservasi yang masuk secara real-time.
5.  **Secure Contact Form:** Fitur komunikasi langsung terintegrasi untuk menangani keluhan, saran, atau kerja sama bisnis (catering/event).

## 🚀 Panduan Instalasi Lokal

Ikuti langkah-langkah berikut untuk menjalankan proyek ini di komputer lokal Anda:

1.  **Clone Repositori:**
    ```bash
    git clone https://github.com/username/foode-master.git
    ```
2.  **Pindahkan Proyek:**
    Pindahkan folder hasil clone ke direktori root server lokal Anda (misalnya `htdocs` jika menggunakan XAMPP, atau `www` jika menggunakan Laragon/WampServer).
3.  **Konfigurasi Database:**
    * Buka browser dan akses `http://localhost/phpmyadmin`.
    * Buat database baru dengan nama `foode_master`.
    * Import file SQL yang berada di dalam folder `database/foode_master.sql`.
4.  **Atur Koneksi PHP:**
    Buka file konfigurasi database (misalnya `config/database.php` atau sejenisnya) dan sesuaikan kredensial server lokal Anda:
    ```php
    <?php
    define('DB_HOST', 'localhost');
    define('DB_USER', 'root');
    define('DB_PASS', '');
    define('DB_NAME', 'foode_master');

    // Membuat koneksi
    $conn = new mysqli(DB_HOST, DB_USER, DB_PASS, DB_NAME);
    if ($conn->connect_error) {
        die("Koneksi gagal: " . $conn->connect_error);
    }
    ?>
    ```
5.  **Jalankan di Browser:**
    Akses website melalui URL: `http://localhost/foode-master`.

## 📸 Pratinjau Tampilan (Screenshots)

*(Ganti placeholder di bawah ini dengan screenshot asli dari website Anda setelah siap)*

| Landing Page (Hero Section) | Menu Katalog Premium | Dashboard Admin |
| :---: | :---: | :---: |
| `[Link Gambar Beranda]` | `[Link Gambar Menu]` | `[Link Gambar Dashboard]` |

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License** - lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.

---
Dibuat dengan penuh dedikasi oleh [Nama Anda](https://github.com/username)
