# Overview Proyek 
Proyek ini dibuat untuk memenuhi tugas UTS matakuliah RPL. Proyek ini adalah aplikasi pencatatan keungan dimana dalam proyek ini user bisa menginputkan sebuah brand (merek) sesui dengan kategori yang disediakan, ada 4 kategori yaitu, pemasukan , pengeluaran, tabungan, dan investasi untuk brand-nya sendiri bisa dikustom contoh IKEA (Pengeluaran) dan juga Proyek ini terdapat 4 menu utam yaitu Dashboard, Brands, Kategori dan Transaksi.
Proyek ini dikembangkan secara tim dengan daftar anggota sebagai berikut:
23051204334 - Pebri Andika Putra 
23051204339 – Muhammad Alvi Kirana Zulfan Nazal 
23051204341 – Dwi Lestari Amelia 
23051204355 – Najwa Vaida Isnani 

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
