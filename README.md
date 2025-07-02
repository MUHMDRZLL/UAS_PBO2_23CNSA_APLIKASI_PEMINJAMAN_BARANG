UAS_PBO2_23CNSA_APLIKASI_PEMINJAMAN_BARANNG

Aplikasi Peminjaman Barang

Latar Belakang
Kondisi saat ini di lingkungan Universitas Teknologi Bandung (UTB) masih menunjukkan bahwa proses peminjaman barang, baik untuk keperluan akademik maupun operasional, masih dilakukan secara manual. Proses manual ini seringkali menimbulkan berbagai permasalahan, seperti ketidakteraturan dalam pencatatan data, kesulitan dalam memantau status barang yang dipinjam, serta potensi terjadinya kehilangan atau keterlambatan pengembalian barang. Situasi ini tentu menghambat efisiensi kerja staf internal dan berdampak pada kinerja operasional kampus secara keseluruhan.
Untuk menjawab permasalahan tersebut, diperlukan sebuah sistem peminjaman barang berbasis aplikasi desktop yang dapat dioperasikan secara lokal tanpa memerlukan koneksi internet, sehingga tetap dapat digunakan secara optimal di lingkungan kampus dengan infrastruktur jaringan terbatas sekalipun. Aplikasi ini akan dibangun menggunakan JavaFX, sebuah framework modern untuk pengembangan antarmuka grafis yang interaktif dan user-friendly. Penggunaan JavaFX dianggap tepat karena mendukung pembuatan aplikasi desktop dengan tampilan yang menarik, mudah digunakan oleh staf internal, serta memiliki performa yang handal untuk mendukung kebutuhan administrasi peminjaman barang di UTB. Dengan adanya sistem ini, diharapkan proses peminjaman barang di UTB dapat berjalan lebih teratur, terkontrol, dan efisien.

Alur Sistem
1.	Alur Sistem (Mahasiswa)
a.	Login ke Aplikasi
b.	Lihat daftar barang tersedia
c.	Ajukan permintaan peminjaman
d.	Tunggu persetuan admin
e.	Ambil barang jika disetujui
f.	Kembalikan barang sesaui jadwal

2.	Alur Admin
a.	Login sebagai admin
b.	Melihat dan mengelola data barang
c.	Melihat permintaan peminjaman dan menyetujiui/menolak
d.	Memverifikasi pengembalian dan mencatat kondisi barang
e.	Mencetak laporan jika diperlukan
Aktor Pada Sistem
1.	Mahasiswa
2.	Dosen/Admin
Rencana Fitur
1.	Login
a.	Login (Mahasiswa/Admin)
2.	Data Barang
a.	Tambah, ubah, dan hapus barang
b.	Lihat status barang (tersedia, dipinjam, rusak)
3.	Peminjaman
a.	Form permintaan peminjaman
b.	Table daftar permintaan 
c.	Setujui/tolak
d.	Update status menjadi “dipinjam”
4.	Pengembalian
a.	Daftar barang yang harus dikembalikan
b.	Verifikasi pengembalian
c.	Cek kondisi barang
d.	Update status 
5.	Laporan
a.	Tabel riwayat peminjaman
b.	Print laporan (opsional)
Tahapan Implementasi
1.	Setup
•	Setup project di NetBeans
•	Integrasi javaFX + database
•	Desain tampilan awal 

2.	CRUD Barang dan User
•	Buat tampilan dan fungsi tambah/edit/hapus barang
•	CRUD untuk pemiinjaman
3.	Peminjaman dan pengembalian
•	Buat form peminjaman dan verifiikasi admin
•	Buat form pengembalian dan status
4.	Laporan
•	Buat fitur riwayat 
