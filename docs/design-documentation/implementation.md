---
sidebar_position: 4
---

# Implementation details

Aplikasi latihan rumahan akan menggunakan database MySQL untuk menyimpan latihan dan data aplikasi lainnya. Basis data akan terdiri dari satu tabel latihan, dengan kolom untuk judul latihan, deskripsi, tanggal jadwal latihan, dan status penyelesaian. Server backend akan menggunakan library Flask-SQLAlchemy untuk berinteraksi dengan database dan melakukan operasi CRUD (buat, baca, perbarui, hapus) pada latihan.

# Testing

Aplikasi latihan rumahan akan diuji menggunakan teknik pengujian manual. Pengujian manual akan dilakukan oleh tim penguji yang akan menguji aplikasi secara manual pada perangkat untuk memastikannya berfungsi seperti yang diharapkan.

# Deployment

- Menggunakan platform cloud seperti AWS, Azure, atau Google Cloud. Platform ini menyediakan infrastruktur dan alat yang dibutuhkan untuk menjalankan aplikasi, seperti server, storage, dll.
- Menggunakan layanan hosting web seperti Heroku, DigitalOcean, atau Bluehost. Layanan ini menyediakan server yang sudah diatur sehingga aplikasi dapat dengan mudah di-deploy.
- Menggunakan Containerization seperti Docker atau Kubernetes. Ini memungkinkan aplikasi dikemas dalam container yang dapat di-deploy ke berbagai platform.
- Deploying secara lokal, dengan menginstall software yang dibutuhkan di komputer pengguna.

Pilihan deployment yang tepat akan tergantung pada kompleksitas aplikasi, anggaran, dan jumlah pengguna yang diharapkan. Jika aplikasi memiliki jumlah pengguna yang besar dan harus tersedia 24/7, maka menggunakan platform cloud atau layanan hosting web yang dapat diandalkan adalah pilihan yang baik. Namun, jika aplikasi hanya digunakan oleh jumlah pengguna yang terbatas atau tidak memerlukan ketersediaan yang tinggi, maka deploying secara lokal atau menggunakan containerization mungkin lebih cocok.

Aplikasi daftar tugas akan diterapkan ke mesin virtual berbasis cloud yang menjalankan Ubuntu Linux. Aplikasi akan di-container menggunakan Docker dan di-deploy menggunakan continuous integration and delivery (CI/CD) pipeline. Pipeline akan dikonfigurasi untuk menerapkan versi baru aplikasi secara otomatis setiap kali perubahan kode dibuat dan didorong ke repositori.

# Maintenance

Aplikasi latihan rumahan akan dikelola oleh tim pengembang yang akan bertanggung jawab untuk memperbaiki bug, menambahkan fitur baru, dan memastikan bahwa aplikasi tetap up-to-date. Tim akan menggunakan proses pengembangan yang gesit, dengan pembaruan dan rilis reguler untuk menjaga agar aplikasi tetap segar dan bermanfaat bagi pengguna.