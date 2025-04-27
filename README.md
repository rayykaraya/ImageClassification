# ImageClassification

Instruksi Penggunaan
Disarankan untuk menjalankan kode ini di Google Colab untuk menghindari masalah dengan versi TensorFlow dan dependensi lainnya. Google Colab sudah menyediakan versi TensorFlow yang kompatibel dan memungkinkan Anda untuk menggunakan GPU secara gratis, yang dapat mempercepat pelatihan model. Selain itu, Google Colab juga menyediakan lingkungan Python yang siap pakai, sehingga Anda tidak perlu khawatir tentang pengaturan instalasi atau dependensi.

## Mengunduh Dataset dari Kaggle Menggunakan API

Untuk mengunduh dataset langsung dari Kaggle menggunakan API, ikuti langkah-langkah di bawah ini.

### 1. Membuat Akun dan Mendapatkan API Key

- **Daftar atau masuk ke akun Kaggle**: Kunjungi [Kaggle](https://www.kaggle.com/) dan buat akun jika belum memiliki.
- **Akses API Key**: 
  - Setelah masuk, buka halaman [Akun Kaggle](https://www.kaggle.com/account).
  - Di bagian **API**, klik **Create New API Token** untuk mengunduh file `kaggle.json`, yang berisi kredensial API kamu.

### 2. Menyimpan API Key

Setelah mendapatkan file `kaggle.json`, simpan file ini di direktori tertentu, agar dapat digunakan oleh API Kaggle.
