# SIBANSOS
SIBANSOS (Sistem Informasi Bantuan Sosial) – Aplikasi berbasis web untuk pendataan, monitoring, dan visualisasi penyaluran bantuan sosial.
# SIBANSOS - Sistem Informasi Bantuan Sosial

SIBANSOS adalah sistem informasi web sederhana untuk monitoring dan pengelolaan data penerima bantuan sosial (bansos) di Dinas Sosial (Dinsos). Dibuat dengan React + Tailwind CSS untuk proyek magang.

## Fitur Utama
- **Login Admin**: Akses aman dengan kredensial admin (Username: `admin`, Password: `098765`).
- **Statistik Real-time**: Total penerima, jumlah aktif/selesai/dibatalkan.
- **Filter Data Canggih**: Pencarian nama/NIK/alamat, filter berdasarkan kecamatan, jenis bantuan (PKH, KIS, BPNT, dll.), dan status.
- **Tabel Data Interaktif**: Daftar penerima dengan badge status berwarna, responsive di mobile.
- **Visualisasi Distribusi**: Progress bar untuk distribusi per kecamatan dan jenis bantuan.
- **Logout & Persist Login**: State login tersimpan di browser.

## Tech Stack
- **Frontend**: React 18, TypeScript, Vite (build tool cepat), Tailwind CSS (styling modern).
- **Data**: Mock data (7 sampel penerima bansos; mudah diganti dengan API backend seperti Node.js/Express + MySQL).
- **Deployment**: GitHub Pages (gratis & otomatis).

## Cara Install & Jalankan Lokal
1. Clone repository:  
