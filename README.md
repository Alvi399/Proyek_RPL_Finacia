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