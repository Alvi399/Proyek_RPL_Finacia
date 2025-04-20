## 📌 Overview Proyek

Proyek ini dikembangkan sebagai bagian dari tugas Ujian Tengah Semester (UTS) mata kuliah **Rekayasa Perangkat Lunak (RPL)**. Aplikasi yang dibangun adalah sistem pencatatan keuangan pribadi, yang memungkinkan pengguna untuk mencatat transaksi berdasarkan **kategori** dan **brand (merek)**.

Dalam aplikasi ini, pengguna dapat:
- Menginput brand sesuai dengan kategori yang disediakan.
- Menyesuaikan nama brand, contohnya: *IKEA* untuk kategori *Pengeluaran*.
- Mengelola transaksi keuangan dalam empat kategori utama:
  - **Pemasukan**
  - **Pengeluaran**
  - **Tabungan**
  - **Investasi**

### 🧭 Fitur Utama
Aplikasi ini memiliki empat menu utama:
1. **Dashboard** – Ringkasan data dan grafik transaksi.
2. **Brands** – Manajemen brand/merek.
3. **Kategori** – Pengaturan kategori transaksi.
4. **Transaksi** – Pencatatan dan pengelolaan transaksi keuangan.

### 👨‍💻 Tim Pengembang
Proyek ini dikerjakan secara berkelompok oleh mahasiswa berikut:

1. **Pebri Andika Putra** – 23051204334  
2. **Muhammad Alvi Kirana Zulfan Nazal** – 23051204339  
3. **Dwi Lestari Amelia** – 23051204341  
4. **Najwa Vaida Isnani** – 23051204355


# Panduan Penginstalan Proyek
Ikuti langkah-langkah berikut untuk menginstal proyek ini di komputer Anda:

1. **Clone Repository**
    ```bash
    git clone https://github.com/username/Finacia.git
    cd Finacia
    ```

2. **Instal Dependensi**
    Pastikan Anda memiliki Node.js dan npm terinstal. Kemudian jalankan:
    ```bash
    npm install
    ```

3. **Konfigurasi Lingkungan**
    Salin file `.env.example` menjadi `.env` dan sesuaikan konfigurasi sesuai kebutuhan Anda.

4. **Jalankan Proyek**
    Untuk menjalankan proyek secara lokal:
    ```bash
    npm start
    ```

5. **Akses Aplikasi**
    Buka browser dan akses [http://localhost:3000](http://localhost:3000).

6. **Build untuk Produksi**
    Jika ingin membuat build untuk produksi:
    ```bash
    npm run build
    ```

7. **Import Database**
    Gunakan file `backup.sql` untuk mengatur database. Pastikan Anda memiliki MySQL terinstal, lalu jalankan perintah berikut:
    ```bash
    mysql -u root -p -e "CREATE DATABASE hisabi;"
    mysql -u root -p hisabi < backup.sql
    ```
    Gunakan password `hisabi` saat diminta.

Pastikan semua langkah di atas dilakukan dengan benar untuk menghindari masalah saat menjalankan proyek.
