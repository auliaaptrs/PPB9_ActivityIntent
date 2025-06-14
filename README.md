# Dessert Clicker app

Dessert Clicker adalah aplikasi Android sederhana yang dibangun sebagai bagian dari materi pembelajaran Android modern oleh Google. Aplikasi ini adalah clicker game di mana pengguna mengetuk gambar dessert untuk mendapatkan poin dan membuka dessert baru. Proyek ini merupakan contoh implementasi yang sangat baik untuk konsep-konsep inti Jetpack Compose.

## 🍰 Fitur
Gameplay Interaktif: Klik pada dessert untuk meningkatkan pendapatan dan jumlah dessert yang terjual.
Progresivitas Otomatis: Aplikasi secara otomatis menampilkan dessert baru yang lebih mahal setelah mencapai jumlah penjualan tertentu.
State yang Persisten: Skor dan progres game tidak akan hilang saat layar diputar (perubahan konfigurasi), berkat manajemen state yang tepat.
Fungsi Berbagi: Pengguna dapat membagikan skor mereka ke aplikasi lain menggunakan Android Sharesheet.

## 🛠️ Teknologi yang Digunakan
- Bahasa: Kotlin
- UI Toolkit: Jetpack Compose - Toolkit UI modern dan deklaratif dari Google.
- Desain: Material 3 - Mengikuti panduan desain terbaru dari Google.
- Arsitektur: Mengikuti prinsip arsitektur Android modern dengan pemisahan antara UI, data, dan logika.

## ✨ Konsep Utama yang Dipelajari
Proyek ini adalah studi kasus yang sangat baik untuk memahami beberapa konsep fundamental dalam pengembangan Android modern:

- UI Deklaratif: Membangun UI dengan mendeskripsikan seperti apa tampilannya untuk state tertentu, bukan bagaimana cara mengubahnya.
- Manajemen State (State Management): Menggunakan mutableStateOf untuk membuat data yang dapat diobservasi oleh UI.
- Menggunakan rememberSaveable untuk menjaga (mengingat) state agar selamat dari perubahan konfigurasi (seperti rotasi layar) dan bahkan saat proses aplikasi dimatikan oleh sistem.
- Siklus Hidup Activity (Lifecycle Awareness): Memahami bagaimana state dan UI bereaksi terhadap siklus hidup Android, dan bagaimana Compose menyederhanakan penanganannya.
- Arsitektur Bersih (Clean Architecture): Mempraktikkan pemisahan tugas dengan menempatkan data, model, dan logika UI di dalam file dan paket yang terpisah.
- Integrasi Intent: Menggunakan Intent.ACTION_SEND untuk berinteraksi dengan komponen Android lain dan memicu fungsionalitas berbagi.
- State Hoisting: Menerapkan pola di mana state diangkat ke komponen induk untuk membuat komponen UI menjadi stateless dan lebih mudah digunakan kembali.
