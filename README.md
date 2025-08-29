### **Deskripsi Proyek: Aplikasi Nomor Urut Karnaval**

Aplikasi web ini dirancang untuk mengelola pengambilan nomor urut peserta karnaval secara *real-time*, adil, dan otomatis. Dibangun menggunakan HTML, Tailwind CSS, dan JavaScript murni, aplikasi ini terintegrasi langsung dengan Google Sheets sebagai basis data, memungkinkan pembaruan data secara langsung tanpa memerlukan server yang kompleks.

**Fitur Utama:**

* **Login Berbasis Peran:** Sistem login terpisah untuk **Pengguna (Lembaga)** dan **Admin**, masing-masing dengan hak akses dan tampilan yang berbeda.
* **Pengambilan Nomor Acak & Aman:** Mencegah pendaftaran ganda dengan sistem validasi yang memeriksa status pendaftaran setiap lembaga.
* **Manajemen Admin:** Admin memiliki dasbor khusus untuk memantau, mendaftarkan, dan membatalkan pendaftaran peserta jika diperlukan.
* **Pendaftaran Berbasis Waktu:** Pendaftaran hanya dapat dilakukan dalam rentang waktu yang telah ditentukan, dengan hitung mundur yang ditampilkan kepada pengguna.
* **Cetak Bukti Pendaftaran:** Peserta yang berhasil mendaftar dapat mencetak bukti pendaftaran yang dirancang secara profesional, lengkap dengan logo dan detail lembaga.
* **Mode Uji Coba:** Fitur khusus untuk melakukan simulasi pengambilan nomor tanpa memengaruhi data pendaftaran yang sebenarnya.
* **Integrasi Google Sheets:** Semua data (daftar lembaga, peserta terdaftar) dikelola secara terpusat di Google Sheets dan diakses melalui Google Apps Script, membuatnya mudah dikelola oleh panitia.

Aplikasi ini adalah solusi yang efisien dan modern untuk mengotomatisasi proses pendaftaran acara, memastikan transparansi dan kemudahan bagi semua pihak yang terlibat.
