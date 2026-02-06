# 🕒 Sistem Presensi KPRI Bina Sejahtera

Sistem Presensi KPRI Bina Sejahtera adalah sistem terintegrasi untuk **manajemen presensi karyawan** berbasis **lokasi** dan **pelaporan kehadiran**, yang terdiri dari:

- **Aplikasi Android** untuk presensi karyawan
- **Web Admin/Dashboard** untuk monitoring & rekap
- **Backend API** sebagai pusat autentikasi, data, dan aturan presensi

**🎯 Presensi lebih rapi, data lebih akurat, monitoring lebih cepat.**

---

## 🌍 Latar Belakang

Dalam operasional koperasi/toko/cabang, pencatatan kehadiran manual sering memicu masalah seperti keterlambatan rekap, data tidak konsisten, dan sulitnya verifikasi lokasi. Sistem ini dibangun untuk:

- Menyediakan pencatatan hadir/pulang yang lebih **terstruktur**
- Membantu verifikasi presensi berbasis **lokasi (GPS/peta)**
- Memudahkan admin dalam **monitoring** dan **rekap kehadiran**
- Menjadi fondasi integrasi fitur lanjutan (pelaporan, audit, dan administrasi)

---

## 🚀 Modul Utama

### 1. Presensi Karyawan (Mobile)

Fokus pada aktivitas karyawan saat presensi:

- Presensi **datang/pulang**
- Pengambilan **lokasi** (GPS)
- Tampilan peta untuk konteks lokasi presensi

### 2. Manajemen Lokasi Presensi

Pengelolaan titik presensi yang valid:

- Lokasi presensi per **toko/cabang**
- Informasi titik lokasi dan kebutuhan validasi jarak

### 3. Manajemen Karyawan & Role

Pengaturan akun dan akses:

- Database karyawan
- Role/akses (admin vs pengguna)

### 4. Dashboard Admin & Monitoring

Mendukung kebutuhan pengelola untuk:

- Melihat aktivitas presensi
- Monitoring data kehadiran
- Monitoring ringkasan pendapatan dan pengeluran serta setoran anggota koperasi

### 5. Pelaporan & Rekap Kehadiran

Ringkasan data untuk administrasi:

- Rekap kehadiran
- Pelaporan periodik sesuai kebutuhan operasional

---

## 🧩 Arsitektur Sistem (Ringkas)

- **Android App**: Kotlin + Jetpack Compose, Hilt (DI), Retrofit (API), Google Play Services (Auth/Location/Maps)
- **Backend API**: Laravel 12 (API), Sanctum (token auth), PHP ^8.2, database MySQL
- **Web Frontend**: TanStack Start (Framework) dengan Vite + React + TanStack Router/Query, Tailwind CSS

---

## 🤝 Kolaborasi & Pengelolaan

Sistem ini dapat dijalankan dan dikembangkan dengan kolaborasi multiperan:

- **Admin/Operasional**: kebijakan lokasi presensi, rekap & monitoring
- **HR/Manajemen**: kebutuhan laporan & aturan kerja
- **Tim IT**: pengembangan fitur, pemeliharaan server, dan integrasi aplikasi

---

## 🧑‍💻 Kontributor (Peran)


Kontribusi pengembangan terbagi menjadi:

- **Backend Developer (API & Database) & Sistem Analis** — Nama: Muhammad Fauzan Putra Trisuladana ([+62 857-1221-6860](https://wa.me/6285712216860))
- **Mobile Developer (Android)** — Nama: Tb. Muhammad Endra Zhafir Al Ghifari ([+62 889-5089-410](https://wa.me/628895089410))
- **Frontend Developer (Web Admin)** — Nama: Abdullah Afif Habiburrohman ([+62 851-5991-7205](https://wa.me/6285159917205))
- **UI/UX Designer** — Nama: Prihastomo Budi Satrio ([+62 821-3628-4039](https://wa.me/6282136284039))

---

## 📁 Struktur Project

- `An-KPRI-Bina-Sejahtera/` — Aplikasi Android
- `FE BE/Be-KPRI-Bina-Sejahtera/` — Backend API (Laravel)
- `FE BE/Fe-KPRI-Bina-Sejahtera/` — Web Frontend/Dashboard

---

## 📢 Kontak

Untuk kebutuhan akses, deployment, atau dukungan teknis, silakan hubungi **tim development KPRI Bina Sejahtera**.

---

## 🌱 Penutup

Sistem Presensi KPRI Bina Sejahtera dibuat untuk membantu operasional presensi menjadi lebih transparan, mudah dipantau, dan siap berkembang sesuai kebutuhan organisasi.

© 2026 KPRI Bina Sejahtera. Seluruh hak cipta dilindungi undang-undang.
