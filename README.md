# 📊 ITSM Dashboard Sederhana (Simple IT Service Management Dashboard)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Technology: Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-06B6D4.svg)](https://tailwindcss.com/)
[![Technology: Chart.js](https://img.shields.io/badge/Charts-Chart.js-FF6384.svg)](https://www.chartjs.org/)

Dashboard ITSM ini dibangun sebagai *proof-of-concept* untuk menampilkan metrik layanan teknologi informasi (TI) utama secara visual dan interaktif. Dashboard ini memanfaatkan *utility-first* dari Tailwind CSS untuk *styling* modern dan Chart.js untuk visualisasi data yang dinamis.

Proyek ini sepenuhnya berbasis *frontend* (HTML/CSS/JavaScript) dan menggunakan data simulasi sebagai pengganti koneksi API *backend* sungguhan.

## ✨ Fitur Utama

* **Layout Sidebar Responsif:** Navigasi *sticky* di sebelah kiri untuk memudahkan akses ke berbagai modul.
* **Header Fixed:** Header konten utama tetap diam saat pengguna menggulir konten, memastikan akses cepat ke judul halaman.
* **Kartu Metrik Dinamis:** Menampilkan metrik ITSM penting (Tiket Terbuka, Tiket Kritis, CSAT) yang dimuat melalui simulasi **JavaScript Promise/Async**.
* **Visualisasi Data:** Menggunakan **Chart.js** untuk menampilkan distribusi status tiket secara proporsional.
* **Navigasi Halaman Single-Page:** Perpindahan antar halaman (**Dashboard**, **Semua Tiket**, **Basis Pengetahuan**) tanpa *reload* halaman (*Simulated SPA*).
* **Tabel Tiket Interaktif:** Halaman "Semua Tiket" memiliki tabel yang *styled* dengan jelas (menggunakan *badge* warna untuk Status dan Prioritas).
* **Pop-up Modal:** Fungsionalitas modal untuk **"Buat Tiket Baru"** yang dapat dibuka dan ditutup menggunakan JavaScript.

## 🛠️ Teknologi yang Digunakan

| Kategori | Teknologi | Deskripsi |
| :--- | :--- | :--- |
| **Struktur** | `HTML5` | Struktur markup dasar. |
| **Styling** | **Tailwind CSS** (via CDN) | Framework CSS *utility-first* untuk *styling* yang cepat dan fleksibel. |
| **Interaktivitas** | `Vanilla JavaScript` | Logika untuk simulasi data, navigasi *sidebar*, dan kontrol modal. |
| **Grafik** | **Chart.js** (via CDN) | Library JavaScript untuk membuat grafik data yang dinamis dan responsif. |
| **Ikon** | [**Heroicons**](https://heroicons.com/) | Set ikon modern yang terintegrasi dengan baik. |

## 🚀 Instalasi dan Penggunaan

Karena proyek ini menggunakan CDN (Content Delivery Network), langkah instalasi sangatlah sederhana:

1.  **Kloning Repositori** (Jika sudah ada di GitHub):
    ```bash
    git clone [https://github.com/agunggema-debug/itsm-dashboard.git]
    cd itsm-dashboard
    ```
2.  **Buka File:** Buka file `index.html` (atau nama file HTML utama Anda) langsung di *browser* Anda.

### ⚠️ Catatan Penting

Proyek ini menggunakan **Tailwind CSS CDN** dan **Chart.js CDN**. Pastikan Anda memiliki koneksi internet aktif saat membuka file.

## 💡 Pengembangan Lebih Lanjut (To-Do)

* [ ] Mengganti simulasi data JavaScript dengan koneksi ke API *backend* sungguhan (misalnya, menggunakan **Fetch API** ke Node.js/Python server).
* [ ] Implementasi fungsionalitas *Filter*, *Sorting*, dan *Pagination* pada tabel **Semua Tiket**.
* [ ] Menambahkan *toggle* untuk *sidebar* (hamburger menu) pada tampilan *mobile* agar lebih responsif.
* [ ] Mengganti *Doughnut Chart* dengan jenis grafik lain (misalnya *Bar Chart* untuk Prioritas).

## 📄 Lisensi

Proyek ini dilisensikan di bawah **Lisensi MIT**. Lihat file `LICENSE` untuk detail lebih lanjut.

---
