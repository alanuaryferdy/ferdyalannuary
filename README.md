# Konsul Dokter Laravel

Aplikasi Konsultasi Dokter berbasis web menggunakan Laravel. Proyek ini dirancang untuk memfasilitasi interaksi antara pasien dan dokter melalui sistem konsultasi online.

## 🚀 Fitur Utama

- Registrasi & Login untuk pasien dan dokter
- Sistem konsultasi berbasis teks
- Manajemen jadwal dokter
- Dashboard admin untuk mengelola admin, pasien dan dokter
- Notifikasi konsultasi masuk
- Tampilan responsif dengan Bootstrap

## 🛠️ Teknologi yang Digunakan

- **Laravel 10**
- **PHP 8+**
- **Bootstrap 5**
- **MySQL**
- **Blade Templating Engine**

## ⚙️ Cara Install

1. Clone repository ini:
   ```bash
   git clone https://github.com/yukinime/konsul-dokter-laravel.git
   cd konsul-dokter-laravel
2. Install dependensi PHP:
   ```bash
   composer install
3. Install dependensi node:
   ```bash
   npm install
4. Copy file .env dan atur konfigurasi database:
   ```bash
   cp .env.example .env
5. Generate key aplikasi:
   ```bash
   php artisan key:generate
6. Buat database dan jalankan migrasi:
   ```bash
   php artisan migrate
7. Jalankan server lokal:
   ```bash
   php artisan serve
