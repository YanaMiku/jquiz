# Master JLPT N5 - Glassmorphism Quiz App

Aplikasi web kuis interaktif yang dirancang untuk membantu pengguna mempelajari Hiragana, Katakana, dan Kanji sebagai persiapan ujian JLPT N5. Aplikasi ini menggunakan antarmuka modern dengan gaya desain **Glassmorphism** dan ditenagai oleh AI untuk pembuatan soal secara dinamis.

## 🔗 Live Preview

Anda dapat mencoba aplikasi ini secara langsung melalui tautan berikut:
**[https://yanamiku.github.io/jquiz/](https://yanamiku.github.io/jquiz/)**

## 🌟 Fitur Utama

* **Generasi Soal Berbasis AI**: Menggunakan integrasi API Gemini untuk menghasilkan soal kuis yang berbeda setiap kali sesi dimulai.
* **Desain Glassmorphism Modern**: Tampilan transparan yang elegan dengan dukungan otomatis untuk **Dark Mode** dan **Light Mode**.
* **Sistem Timer Interaktif**: Setiap soal dibatasi waktu 30 detik untuk melatih kecepatan berpikir.
* **Feedback Instan**: Efek suara (SFX) dan indikator visual untuk jawaban benar atau salah.
* **Statistik Akhir**: Menampilkan skor total, jumlah jawaban benar/salah, serta rata-rata waktu menjawab.
* **Konfigurasi Fleksibel**: Pengguna dapat memilih jumlah soal per sesi (15 hingga 90 soal).

## 🛠️ Teknologi yang Digunakan

* **Frontend**: HTML5, CSS3 (Custom Variables, Flexbox, Grid, Animations).
* **Icons & Fonts**: Google Fonts (Poppins & Noto Sans JP) dan Font Awesome 6.
* **API**: Gemini Flash 2.5 melalui endpoint NekoLabs untuk generasi teks JSON.
* **Audio**: Mixkit SFX untuk pengalaman pengguna yang imersif.

## 🚀 Cara Penggunaan

1.  **Halaman Utama**: Klik tombol "Mulai Belajar" untuk masuk ke menu konfigurasi.
2.  **Pilih Target**: Pilih jumlah soal yang ingin dikerjakan (misal: 15 atau 30 soal).
3.  **Generate Soal**: Klik "Generate Soal" dan tunggu AI menyiapkan materi kuis.
4.  **Mulai Kuis**: Pilih jawaban yang menurut Anda benar sebelum waktu habis.
5.  **Hasil**: Lihat statistik performa Anda di akhir sesi dan gunakan tombol "Main Lagi" untuk mencoba tantangan baru.

## 🎨 Detail Desain

Aplikasi ini menggunakan teknik CSS modern:
- `backdrop-filter: blur()` untuk efek kaca.
- Animasi `cubic-bezier` untuk transisi layar yang halus.
- Desain responsif yang menyesuaikan tampilan dengan perangkat mobile (Mobile First).

## 📄 Lisensi

Proyek ini dibuat untuk tujuan pembelajaran. Silakan modifikasi dan kembangkan lebih lanjut sesuai kebutuhan Anda.

---
*Dibuat dengan ❤️ untuk komunitas pembelajar Bahasa Jepang.*
