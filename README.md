# SITTA UT - Sistem Informasi Tata Kelola Bahan Ajar

SITTA UT adalah aplikasi berbasis web yang dirancang untuk mengelola, memonitor, dan melacak (tracking) distribusi Bahan Ajar Terprogram (BMP) atau buku materi pokok di lingkungan Universitas Terbuka. Projek ini dibuat sebagai tugas praktik mata kuliah Pemrograman Berbasis Web, Analisis Data, serta Algoritma dan Pemrograman (Semester 4 - Sistem Informasi Universitas Terbuka).

## 🚀 Fitur Utama
* **Sistem Autentikasi (Login):** Pembatasan hak akses multi-user (UPBJJ, Puslaba, Fakultas, Administrator) dengan session yang tersimpan di LocalStorage.
* **Manajemen Stok Bahan Ajar (Vue.js 3):** Fitur penambahan, pembaruan, dan penghapusan data buku secara dinamis, lengkap dengan filter berdasarkan UPBJJ/Kategori serta pengurutan data.
* **Logika Safety Stock:** Sistem otomatis mendeteksi dan memberikan status visual (*warning* / *danger*) jika stok buku di gudang menipis atau kosong.
* **Tracking Pengiriman (Delivery Order):** Fitur melacak status perjalanan logistik bahan ajar ke mahasiswa menggunakan nomor DO, dilengkapi fungsi *Auto-Generate* nomor dokumen baru.

## 🛠️ Teknologi yang Digunakan
* **Frontend:** HTML5, CSS3 (Custom Responsive Layout & Fonts)
* **Framework & Library:** Vue.js 3 (Reactive State Management), SweetAlert2 (Pop-up & Notifikasi Dinamis)
* **Scripting:** Vanilla JavaScript (ES6+) untuk manajemen data lokal, pencarian data, dan logika bisnis.

## 👤 Akun Demo untuk Pengujian
Untuk mencoba sistem tata kelola ini, dapat menggunakan kredensial berikut:
* **Email:** `rabilaarianni@ut.ac.id`
* **Password:** `Rabila123`
