# ukk-rpl-parkirpos
# 🚘 Pos Parkir - Sistem Manajemen Parkir & Kendaraan

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpine.js&logoColor=black)
![Live Demo](https://img.shields.io/badge/Live_Demo-posparkir.free.je-blue?style=for-the-badge)

**Pos Parkir** adalah aplikasi web berbasis Laravel yang dirancang untuk mengelola pendaftaran kendaraan, akses masuk-keluar area parkir, serta pencatatan transaksi parkir secara efisien, modern, dan responsif.

🌐 **Akses Live Demo:** [https://posparkir.free.je/?i=1](https://posparkir.free.je/?i=1)

---

## ✨ Fitur Utama

- 🚗 **Pengelolaan Data Kendaraan (CRUD):** 
  - Registrasi plat nomor, jenis kendaraan (Mobil/Motor), dan merk/model.
  - Hapus data kendaraan terdaftar.
- 📱 **Antarmuka Interaktif & Responsif:**
  - Menggunakan **Alpine.js** untuk penanganan *modal popup* yang interaktif (dukungan tombol ESC, klik luar modal, dan *auto-reset* form).
  - Tampilan responsif (Mobile & Desktop) yang dibangun dengan **Tailwind CSS**.
- 🌓 **Mode Gelap / Dark Mode:**
  - Mendukung tampilan seragam dalam skema warna terang (*light mode*) maupun gelap (*dark mode*).
- 🔒 **Validasi Form & Keamanan:**
  - Validasi *input* real-time berbasis server dan alert notifikasi status/error bawaan Laravel Session.

---

## 🛠️ Tumpukan Teknologi (Tech Stack)

- **Backend:** [Laravel](https://laravel.com/) (PHP Framework)
- **Frontend UI:** [Blade Templates](https://laravel.com/docs/blade) + [Tailwind CSS](https://tailwindcss.com/)
- **Interaktivitas JS:** [Alpine.js](https://alpinejs.dev/)
- **Database:** MySQL / MariaDB / PostgreSQL

---

## 🚀 Panduan Instalasi Lokal

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek ini di lingkungan lokal (*local development*):

### 1. Prasyarat
Pastikan server lokal Anda telah terpasang:
- PHP >= 8.1
- Composer
- Node.js & NPM
- MySQL / MariaDB Database

### 2. Kloning Repositori
```bash
git clone [https://github.com/username-anda/pos-parkir.git](https://github.com/username-anda/pos-parkir.git)
cd pos-parkir
