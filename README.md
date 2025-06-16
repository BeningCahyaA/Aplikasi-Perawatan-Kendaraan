# Aplikasi Perawatan Kendaraan

**Latar Belakang**

Banyak pemilik kendaraan lupa jadwal servis rutin seperti ganti oli, pengecekan ban, dan pergantian aki.
Hal ini bisa memperpendek umur kendaraan dan meningkatkan risiko kerusakan.
Oleh karena itu, dibutuhkan sebuah aplikasi yang mampu mengelola informasi perawatan kendaraan secara otomatis, aman, dan dapat digunakan oleh siapa saja.

**Tujuan**
1. Membantu pengguna mengatur jadwal perawatan kendaraan.
2. Memberikan notifikasi saat waktu servis mendekat.
3. Menyimpan data servis secara aman dan rapi.

**Target Pengguna**
- Pemilik kendaraan pribadi (motor/mobil)
- Pemilik usaha rental kendaraan

**Fitur Utama**
1. Manajemen Kendaraan (Generic: motor, mobil)
2. Riwayat Servis & Jadwal Perawatan
3. Pengingat Otomatis (Threading)
4. Backup & Restore Data (Serialisasi)
5. UI Multibahasa (Internasionalisasi)
6. Keamanan Data (Kriptografi)
7. Penyimpanan Fleksibel (SQL & NoSQL)

**Skenario**
1. Pengguna menambahkan kendaraan baru
2. Pengguna mencatat servis terakhir
3. Sistem menghitung perkiraan jadwal servis berikutnya
4. Thread background memantau jadwal
5. Jika sudah dekat, notifikasi muncul

**Stakeholder**
1. Pemilik Kendaraan (End User)
2. Developer / Programmer (Mahasiswa)
