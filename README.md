# Aplikasi Penjualan Galon

Aplikasi website ini dirancang untuk memudahkan proses penjualan galon air minum secara online. Pengguna dapat membeli galon air, memilih layanan pengantaran, serta melakukan transaksi pembayaran melalui platform ini.

## Deskripsi

Aplikasi ini dibuat sebagai tugas untuk memenuhi mata kuliah **E-commerce** yang diampu oleh **Bapak Agus**. Pengguna dapat dengan mudah memilih berbagai jenis galon, melakukan pembelian, serta melacak status pesanan mereka. Aplikasi ini juga menyediakan sistem manajemen untuk penjual, agar dapat memantau stok dan transaksi dengan lebih efisien.

## Fitur

- **Daftar Galon**: Pengguna dapat melihat daftar galon yang tersedia beserta harga dan detail produk.
- **Pencarian Produk**: Memudahkan pengguna untuk mencari galon berdasarkan kategori atau harga.
- **Keranjang Belanja**: Pengguna dapat menambah galon ke keranjang dan mengedit pesanan sebelum checkout.
- **Checkout dan Pembayaran**: Pengguna dapat memilih metode pembayaran yang tersedia (transfer bank, e-wallet, dll.).
- **Layanan Pengantaran**: Pengguna dapat memilih lokasi pengantaran dan menentukan waktu pengiriman.
- **Notifikasi**: Pengguna akan mendapatkan notifikasi mengenai status pesanan mereka.

## Teknologi yang Digunakan

- **Frontend**: HTML, CSS, JavaScript (ReactJS)
- **Backend**: Node.js dengan Express
- **Database**: MongoDB
- **Payment Gateway**: Midtrans API (atau lainnya)
- **Hosting**: Heroku / Vercel

## Cara Menjalankan Aplikasi

### Prasyarat

- Node.js terinstal di komputer Anda.
- MongoDB terinstal atau akses ke MongoDB Atlas.
- IDE (misalnya, Visual Studio Code).

### Langkah-langkah:

1. **Clone repositori**:
    ```bash
    git clone https://github.com/username/repo-penjualan-galon.git
    ```
2. **Install dependensi**:
    Masuk ke direktori aplikasi dan jalankan:
    ```bash
    cd repo-penjualan-galon
    npm install
    ```
3. **Konfigurasi .env**:
    Buat file `.env` di root proyek dan masukkan konfigurasi yang diperlukan (seperti database URI, API keys, dll.).
   
4. **Jalankan aplikasi**:
    ```bash
    npm start
    ```
    Aplikasi akan berjalan di [http://localhost:3000](http://localhost:3000).

## Pembuat

- **Nama**: Talitha Shafa Thiffasha
- **Mata Kuliah**: E-commerce
- **Dosen**: Bapak Agus

## Lisensi

MIT License. Lihat file `LICENSE` untuk informasi lebih lanjut.
