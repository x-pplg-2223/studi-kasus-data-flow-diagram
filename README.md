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
![level2(2)](img/dfd%20level%202%20(2).jpg)<br>
DFD level 2.2 berfokus pada proses pengelolaan pustaka perpustakaan melalui status login dan pustaka. Proses ini terdiri dari beberapa aktivitas, antara lain:
<br>
<br>
-Menambahkan Pustaka:<br> 
Pada aktivitas ini, petugas perpustakaan dapat menambahkan pustaka baru ke dalam sistem. Informasi yang dimasukkan meliputi judul, pengarang (jika ada), kategori, dan jumlah eksemplar.
<br>
-Mengubah Data Pustaka:<br> 
Petugas perpustakaan dapat mengubah informasi tentang pustaka yang sudah terdaftar dalam sistem. Hal ini bisa dilakukan ketika terjadi kesalahan dalam informasi pustaka atau adanya perubahan informasi terkait pustaka tersebut.
<br>
-Menghapus Pustaka:<br> 
Pada aktivitas ini, petugas perpustakaan dapat menghapus informasi tentang pustaka yang sudah tidak diperlukan dalam sistem.
<br>
-Melihat Data Pustaka:<br> 
Pada aktivitas ini, petugas perpustakaan dapat melihat informasi tentang pustaka yang sudah terdaftar dalam sistem. Informasi yang dapat dilihat meliputi judul, pengarang, kategori.
<br>
Proses pengelolaan pustaka di DFD level 2.2 dibagi menjadi dua jenis, yaitu pustaka tanpa pengarang dan pustaka dengan pengarang. Hal ini dilakukan untuk memudahkan proses pengelolaan dan pengecekan informasi pustaka pada sistem. Pustaka tanpa pengarang, seperti majalah atau kamus, hanya memerlukan informasi judul dan kategori saja. Sedangkan untuk pustaka dengan pengarang, seperti novel atau buku teks, memerlukan informasi tambahan berupa pengarang dari pustaka tersebut.


# DFD level 2 (3)
![level2(3)](img/dfd%20level%202%20(3).jpg)<br>
DFD level 2.3 ini terfokus pada proses pengelolaan anggota melalui status login dan terdaftar sebagai anggota. Proses ini terdiri dari beberapa aktivitas, antara lain:
<br>
<br>
-Menambahkan Anggota:<br> 
Pada aktivitas ini, petugas perpustakaan dapat menambahkan informasi anggota baru ke dalam sistem. Informasi anggota yang dimasukkan meliputi nama lengkap, alamat, nomor telepon, dan jenis kelamin.
<br>
-Mengubah Data Anggota:<br> 
Petugas perpustakaan dapat mengubah informasi anggota yang sudah terdaftar di dalam sistem. Hal ini bisa dilakukan ketika terjadi kesalahan dalam informasi anggota atau adanya perubahan informasi terkait anggota tersebut.
<br>
-Menghapus Anggota:<br> 
Pada aktivitas ini, petugas perpustakaan dapat menghapus informasi anggota yang sudah tidak diperlukan dalam sistem.
<br>
-Melihat Data Anggota:<br> 
Pada aktivitas ini, petugas perpustakaan dapat melihat informasi anggota yang sudah terdaftar di dalam sistem. Informasi anggota yang dapat dilihat meliputi nama lengkap, alamat, nomor telepon, jenis kelamin, serta informasi lain terkait anggota tersebut.
<br>
Seluruh aktivitas di atas dilakukan melalui status login, di mana hanya petugas perpustakaan yang terdaftar dan masuk ke dalam sistem yang dapat melakukan pengelolaan anggota tersebut. Proses pengelolaan anggota ini dibagi menjadi dua kategori, yaitu anggota tanpa nomor telepon dan anggota dengan nomor telepon.

# DFD level 2 (4)
![level2(4)](img/dfd%20level%202%20(4).jpg)<br>
DFD Level 2.4 pada sistem peminjaman buku di perpustakaan menggambarkan bagaimana proses pengelolaan peminjaman buku dijalankan. Terdapat beberapa kegiatan yang dilakukan dalam pengelolaan peminjaman buku, yaitu memasukkan peminjaman, mengubah peminjaman, menghapus peminjaman, melihat peminjaman, dan mencari peminjaman.
<br>
<br>
Proses dimulai ketika pengguna yang telah login ke sistem memasukkan data peminjaman buku. Data ini akan dicek terlebih dahulu oleh sistem untuk memastikan bahwa buku yang akan dipinjam tersedia. Jika buku tersedia, maka sistem akan mencatat data peminjaman tersebut dan mengirim notifikasi ke anggota perpustakaan.
<br>
<br>
Selanjutnya, pengguna dapat melakukan pengubahan, penghapusan, atau pencarian data peminjaman yang telah tercatat di dalam sistem. Sistem akan mengecek terlebih dahulu apakah pengguna yang melakukan akses ke data tersebut adalah pengguna yang memiliki hak akses sesuai dengan aturan yang telah ditetapkan. Jika pengguna memiliki hak akses, maka pengguna dapat melakukan aktivitas yang diinginkan.
<br>
<br>
Setelah pengguna selesai melakukan aktivitas, sistem akan melakukan penyimpanan data terbaru dan melakukan notifikasi ke pengguna mengenai status peminjaman buku yang telah diubah, dihapus, atau ditemukan. Kemudian petugas bisa mencari data pinjaman yang sudah selesai pada jangka waktu yang sudah ditentukan sesuai tenggat peminjaman buku dan menghapus riwayat peminjaman.

# DFD level 2 (5)
![level2(5)](img/dfd%20level%202%20(5).jpg)<br>
Pada tahap ini adalah penjelasan tentang cara kerja DFD level 2.5 yang mencakup memasukkan petugas, mengubah petugas, menghapus petugas, melihat petugas, dan mencari petugas:
<br>
<br>
Status Login dan Petugas
Petugas perpustakaan harus login ke dalam sistem untuk mendapatkan akses ke fungsi pengelolaan petugas. Setelah login, sistem akan mengecek apakah petugas tersebut memiliki hak akses untuk mengelola petugas atau tidak. Jika petugas memiliki hak akses, maka sistem akan menampilkan menu pengelolaan petugas.
<br>
<br>
-Memasukkan Petugas<br>
Petugas perpustakaan dapat memasukkan data petugas baru ke dalam sistem dengan memasukkan informasi seperti nama, alamat, nomor telepon, dan email. Setelah data petugas dimasukkan, sistem akan memvalidasi data dan menyimpan data tersebut ke dalam database.
<br>
-Mengubah Petugas<br>
Petugas perpustakaan dapat mengubah data petugas yang sudah ada dalam sistem, seperti nama, alamat, nomor telepon, dan email. Setelah data diubah, sistem akan memvalidasi perubahan dan memperbarui data petugas dalam database.
<br>
-Menghapus Petugas<br>
Petugas perpustakaan yang lain dapat menghapus data petugas yang sudah ada dalam sistem jika petugas tersebut tidak lagi bekerja di perpustakaan. Setelah data dihapus, sistem akan memvalidasi penghapusan dan menghapus data petugas dari database.
<br>
-Melihat Petugas<br>
Petugas perpustakaan dapat melihat data petugas yang sudah ada dalam sistem. Data petugas yang dapat dilihat meliputi nama, alamat, nomor telepon, dan email.
<br>
-Mencari Petugas<br>
Petugas perpustakaan dapat mencari data petugas yang sudah ada dalam sistem dengan menggunakan fitur pencarian. Fitur ini memungkinkan petugas untuk mencari data petugas berdasarkan kriteria tertentu, seperti nama atau nomor telepon.
<br>
DFD level 2.5 ini memberikan gambaran tentang bagaimana sistem peminjaman buku di perpustakaan bekerja dengan lebih rinci, terutama pada tahap mengelola petugas.

# DFD Kamus Data
![kamusdata](img/kamus%20dataa.drawio.png)