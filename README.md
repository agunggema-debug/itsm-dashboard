# 📊 ITSM Service Management Dashboard

[![Framework - TailwindCSS](https://img.shields.io/badge/Framework-TailwindCSS-06B6D4?style=flat&logo=tailwind-css)](https://tailwindcss.com/)
[![JS - Chart.js](https://img.shields.io/badge/Library-Chart.js-FF6384?style=flat&logo=chart.js)](https://www.chartjs.org/)
[![UI - Responsive](https://img.shields.io/badge/UI-Responsive-brightgreen?style=flat)](https://agunggema-debug.github.io/itsm-dashboard/)

Dashboard Manajemen Layanan TI (ITSM) modern yang responsif, dirancang untuk membantu tim IT memantau tiket, insiden, dan permintaan layanan secara *real-time*. Dibangun menggunakan **Tailwind CSS** untuk antarmuka yang bersih dan **Chart.js** untuk visualisasi data.

## 🚀 Demo Live
Lihat tampilan dashboard di sini: [Demo Live Dashboard ITSM](https://agunggema-debug.github.io/itsm-dashboard/)

## ✨ Fitur Utama
- **Layout Responsif:** Mendukung tampilan HP, Tablet, dan Desktop (Sidebar otomatis menjadi overlay di layar kecil).
- **Interaktivitas Sidebar:** Navigasi antar halaman (Dashboard, Tiket, Knowledge Base) tanpa *reload* halaman.
- **Visualisasi Data:** Grafik status tiket (Doughnut Chart) menggunakan Chart.js.
- **Manajemen Tiket:** Halaman daftar tiket dengan status prioritas berwarna dan fungsionalitas modal (Pop-up) untuk membuat tiket baru.
- **Header & Footer Fixed:** Navigasi tetap yang memberikan aksesibilitas tinggi saat pengguna melakukan *scrolling*.

## 🛠️ Teknologi yang Digunakan
- **HTML5:** Struktur semantik aplikasi.
- **Tailwind CSS:** Untuk desain UI yang cepat, modern, dan responsif.
- **Vanilla JavaScript:** Logika navigasi, kontrol modal, dan manipulasi DOM.
- **Chart.js:** Library untuk pembuatan grafik status tiket.
- **Heroicons:** Ikon SVG yang ringan dan konsisten.

## 📂 Struktur Proyek
```text
itsm-dashboard/
├── index.html          # File utama (Struktur, UI, & Logika JS)
└── README.md           # Dokumentasi proyek
