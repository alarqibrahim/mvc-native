# Aplikasi MVC Native PHP - Modul Praktikum

Aplikasi sederhana pengelolaan data mahasiswa menggunakan pola arsitektur **MVC (Model-View-Controller)** berbasis **PHP Native** dan **PDO** untuk koneksi database.

## Struktur Folder
- `app/controllers/`: Mengatur alur logika aplikasi.
- `app/models/`: Mengelola operasi database.
- `app/views/`: Berisi tampilan antarmuka (UI) HTML.
- `config/`: Konfigurasi koneksi database.
- `database/`: Berisi file SQL database `kampus`.
- `public/`: Entry point utama aplikasi (`index.php`).

## Cara Menjalankan
1. Pastikan XAMPP (Apache & MySQL) sudah aktif.
2. Import database `kampus.sql` melalui phpMyAdmin.
3. Akses project melalui browser di alamat:
   `http://localhost/mvc-native/public/index.php`