# Sistem Informasi Manajemen Servis Gadget

Aplikasi desktop berbasis Java untuk latihan membangun sistem administrasi servis gadget menggunakan antarmuka Java Swing dan database MySQL. Repository ini berasal dari proyek kelompok.

## Fitur yang Tersedia

- Login dan registrasi pengguna.
- Pengelolaan pelanggan dan teknisi.
- Pengelolaan layanan servis, spare part, dan aksesori.
- Pencatatan transaksi pembayaran.
- Riwayat dan laporan menggunakan JasperReports.

## Teknologi

- Java dan Java Swing
- MySQL / MariaDB
- JDBC / MySQL Connector
- NetBeans dan Apache Ant
- JasperReports

## Struktur Utama

- `src/form/`: form utama untuk pengelolaan data.
- `src/form_popup/`: jendela pemilihan data.
- `src/form_report/`: halaman laporan.
- `src/koneksi/`: koneksi database.
- `src/database/service_gadget.sql`: skema dan data awal database.
- `src/report/`: template laporan.

## Menjalankan Secara Lokal

1. Siapkan JDK, NetBeans, serta MySQL atau MariaDB.
2. Buat database `service_gadget`, lalu impor `src/database/service_gadget.sql`.
3. Periksa konfigurasi database pada `src/koneksi/koneksi.java`; sesuaikan dengan environment lokal.
4. Buka proyek di NetBeans sebagai proyek Java with Ant dan pastikan library pada `src/Libs/` tersedia.
5. Jalankan form login atau kelas awal yang terkonfigurasi dalam proyek.

## Catatan Pembelajaran

Sebelum aplikasi digunakan di lingkungan nyata, autentikasi, pengelolaan password, validasi input, dan keamanan query perlu ditinjau ulang. Kredensial pada kode harus dianggap sebagai konfigurasi lokal, bukan kredensial produksi.
