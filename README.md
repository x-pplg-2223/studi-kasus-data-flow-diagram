# studi-kasus-data-flow-diagram
## Dyandra
### kelompok-12

# DFD level 0
![level0](img/studi-kasus-DFD0.jpg) <br>
Anggota/Pengunjung perpustakaan<br>
Anggota atau pengunjung perpustakaan dapat mencari buku pada aplikasi yang dibangun, oleh sebab itu entitas ini mengirim masukan (input) berupa data pencarian untuk proses pencarian data buku dan menerima keluaran (output) berupa data buku yang dicari.
<br>
<br>
Petugas Perpustakaan<br>
Petugas perpustakaan merupakan entitas yang cukup banyak berinteraksi dengan sistem. Kegiatan yang bisa dilakukan diantaranya melakukan login, mencari buku, mengelola data buku, mencari peminjaman, mengelola data peminjaman, mencari anggota, mengelola data anggota, mencari petugas dan data mengelola petugas.
<br>
<br>
Aliran data dikirim dari entitas petugas yang masuk ke dalam sistem  Informasi Manajemen Perpustakaan adalah:<br>
-data login untuk proses login ke sistem<br>
-data pencarian buku untuk proses pencarian dan pengelolaan buku<br>
-data peminjaman untuk proses pencarian dan pengelolaan data peminjaman<br>
-data anggota untuk proses pencarian dan pengelolaan data anggota<br>
-data petugas untuk proses pencarian dan pengelolaan data petugas.
<br>
<br>
Dari masukan yang diterima oleh sistem, selanjutnya aliran data yang keluar dari sistem Informasi Manajemen Perpustakaan ke petugas adalah:<br>
-Pesan login/logout dari proses login/logout<br>
-data buku dari proses pencarian dan pengelolaan buku<br>
-data peminjaman dari proses pencarian dan pengelolaan data peminjaman<br>
-data anggota dari proses pencarian dan pengelolaan data anggota<br>
-data petugas dari proses pencarian dan pengelolaan data petugas.

# DFD level 1
![level1](img/studi-kasus-DFD1.jpg) <br>
DFD level 1 menggambarkan proses sebuah sistem untuk kedua Entitas tersebut (petugas dan anggota), proses ini meliputi mengelola pustaka, mengelola peminjaman, melakukan mengelola anggota, petugas dan data, dan data login dan logout, melakukan pemeriksaaan status login
<br>
<br>
-Proses Mengelola Pustaka<br>
Pada proses ini, perpustakaan akan melakukan manajemen terhadap buku-buku yang ada di perpustakaan. Data yang akan diolah di sini antara lain informasi buku seperti judul buku, pengarang, nomor ISBN, dan status ketersediaan buku. Jika ada buku yang sudah rusak atau tidak layak untuk dipinjam, maka buku tersebut akan dihapus dari daftar buku.
<br>
-Proses Mengelola Peminjaman<br>
Pada proses ini, perpustakaan akan melakukan manajemen terhadap peminjaman buku oleh anggota perpustakaan. Proses ini mencakup pencatatan data peminjaman, pengembalian buku, perpanjangan waktu peminjaman, serta pembayaran denda jika terdapat keterlambatan dalam pengembalian buku.
<br>
-Proses Pengelolaan Anggota<br>
Pada proses ini, perpustakaan akan melakukan manajemen terhadap data anggota perpustakaan, antara lain menginput data anggota baru, mengubah data anggota, atau bahkan menghapus data anggota jika anggota tersebut sudah tidak aktif lagi. Data yang diolah meliputi nama anggota, nomor identitas, alamat, dan nomor telepon.
<br>
-Proses Pengelolaan Petugas dan Data<br>
Pada proses ini, perpustakaan akan melakukan manajemen terhadap data petugas perpustakaan, antara lain menginput data petugas baru, mengubah data petugas, atau bahkan menghapus data petugas jika petugas tersebut sudah tidak aktif lagi. Data yang diolah meliputi nama petugas, nomor identitas, alamat, dan nomor telepon.
<br>
-Proses Data Login dan Logout<br>
Pada proses ini, sistem akan memproses data login dan logout untuk setiap pengguna yang mengakses sistem. Data yang diolah meliputi username dan password.
<br>
-Proses Pemeriksaan Status Login<br>
Pada proses ini, sistem akan memverifikasi apakah pengguna yang melakukan login memiliki hak akses untuk mengakses fitur-fitur tertentu dalam sistem. Jika pengguna memiliki hak akses, maka sistem akan memberikan akses tersebut. Namun jika pengguna tidak memiliki hak akses, maka sistem akan menolak pengguna tersebut.

# DFD level 2 (1)
![level2(1)](img/dfd%20level%202%20(1).jpg)
-Status Login<br>
Proses ini memeriksa status login pengguna. Jika pengguna belum login, maka proses akan meminta pengguna untuk melakukan login terlebih dahulu.
<br>
<br>
-Mengelola Pustaka<br>
Pada tahap ini ada keunggulan seorang petugas yang dapat mengubah proses mengelola pustaka,seperti proses memasukkan pustaka, mengubah pustaka, menghapus pustaka, dengan melalui pengecekan status login agar dapat melakukan hal tersebut,selanjutnya data terakhir tersebut bisa  dikembalikan ke sistem lainnya. Dan ada pula keuntungan yang dimiliki anggota yaitu proses melihat pustaka dengan melalui fase status login, pustaka tanpa pengarang, dan pengarang pustaka pada proses melihat pustaka. Proses ini terdiri dari beberapa subproses, yaitu:<br>
Memasukkan Pustaka: proses ini memungkinkan petugas perpustakaan untuk memasukkan data buku ke dalam sistem. Data buku yang dimasukkan antara lain judul buku, nomor ISBN, jumlah buku, kategori buku, dan lain-lain.<br>
Mengubah Pustaka: proses ini memungkinkan petugas perpustakaan untuk mengubah data buku yang sudah ada di dalam sistem, misalnya mengubah judul buku, nomor ISBN, atau kategori buku.<br>
Menghapus Pustaka: proses ini memungkinkan petugas perpustakaan untuk menghapus data buku yang sudah ada di dalam sistem.<br>
Melihat Pustaka: proses ini memungkinkan petugas perpustakaan untuk melihat daftar buku yang sudah ada di dalam sistem.
<br>
<br>
-Pustaka Tanpa Pengarang<br>
Proses ini memperlihatkan bagaimana data pustaka tanpa pengarang diolah. Data pustaka tanpa pengarang akan masuk ke dalam proses ini setelah proses "Mengelola Pustaka" selesai dilakukan. Proses ini terdiri dari dua subproses, yaitu:<br>
Mendaftarkan Pustaka Tanpa Pengarang: proses ini memungkinkan petugas perpustakaan untuk mendaftarkan buku tanpa pengarang ke dalam daftar buku yang ada di sistem.<br>
Melakukan Pencarian Pustaka Tanpa Pengarang: proses ini memungkinkan petugas perpustakaan untuk melakukan pencarian data buku tanpa pengarang di dalam sistem.
<br>
-Pustaka dengan Pengarang<br>
Proses ini memperlihatkan bagaimana data pustaka dengan pengarang diolah. Data pustaka dengan pengarang akan masuk ke dalam proses ini setelah proses "Mengelola Pustaka" selesai dilakukan. Proses ini terdiri dari beberapa subproses, yaitu:<br>
Mendaftarkan Pustaka dengan Pengarang: proses ini memungkinkan petugas perpustakaan untuk mendaftarkan buku dengan pengarang ke dalam daftar buku yang ada di sistem. Data yang dimasukkan antara lain judul buku, nama pengarang, nomor ISBN, jumlah buku, kategori buku, dan lain-lain.<br>
Melakukan Pencarian Pustaka dengan Pengarang: proses ini memungkinkan petugas perpustakaan untuk melakukan pencarian data buku dengan pengarang di dalam sistem.

# DFD level 2 (2)
![level2(2)](img/dfd%20level%202%20(2).jpg)





# DFD level 2 (3)
![level2(3)](img/dfd%20level%202%20(3).jpg)
# DFD level 2 (4)
![level2(4)](img/dfd%20level%202%20(4).jpg)
# DFD level 2 (5)
![level2(5)](img/dfd%20level%202%20(5).jpg)

# DFD Kamus Data
![kamusdata](img/kamus%20dataa.drawio.png)