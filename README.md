# studi-kasus-data-flow-diagram

# NAMA : Akbar Maulana
# TUGAS DFD

# DFd Level O (Context Diagram)
![level0](img/level_0.jpeg)
Terdapat 2 Entitas luar/aktor yang terlibat, yaitu :
[Anggota/Pengunjung perpustakaan]<br>
Anggota/Pengunjung Perpustakaan adalah Seorang Anggota atau pengunjung yang ingin meminjam ke perpustakaan.<br>
[Petugas Perpustakaan]<br>
Petugas Perpustakaan adalah seorang petugas yang memenuhi permintaan/pinjaman dari pengunjung yang sudah di proses dan sudah mendapat izin dari sistem yang mengelola informasi manajemen perpustakaan.<br>
(mengelola sistem informasi manajemen perpustakaan)<br>
sistem yang mengelola permintaan anggota dan memenuhi permintaan anggota yang di dapatkan dari petugas.<br>
Penjelasan komponen-komponen DFD level 0:
-Petugas perpustakaan melakukan login;<br>
-dan sistem informasi akan memberikan notif/pesan kepada petugas perpustakaan;<br>
-petugas perpustakaan mengirim pencarian pustaka ke sistem informasi;<br>
-anggota/pengunjung mencari sebuah buku yang akan dipinjam, dan akan diterima sistem informasi;<br>
-sistem informasi memberikan data pustaka pada petugas perpustakaan;<br>
-petugas perpustakaan memberikan data buku yang dicari pengunjung ke sistem informasi;<br>
-petugas perpustakaan mencari data anggota/pengunjung yang ingin meminjam tersebut di database sistem informasi;<br>
-sistem informasi memberikan data anggota/pengunjung yang ingin meminjam buku pada petugas perpustakaan;<br>
-petugas perpustakaan memberikan akses untuk anggota/pengunjung;<br>
-petugas perpustakaan melakukan pencarian peminjaman di sistem informasi;<br>
-petugas perpustakaan memberikan formulir peminjaman pada sistem informasi untuk diisi tanggal,buku yg dipinjam,dll;<br>
-lalu sistem memberikan data peminjaman tersebut ke petugas perpustakaan;<br>
-selanjutnya tahap mencari data petugas yang akan melayani peminjaman tsb;<br>
-petugas memberikan akses untuk memberikan buku yang akan dipinjam;<br>
-sistem informasi memberikan konfirmasi pada petugas perpustakaan;<br>
-sistem memberikan data pustaka pada anggota/pengunjung perpustakaan;<br>


# DFd Level 1 
![level1](img/Level_1.jpeg)

# DFD Level 2
![level2](img/level2(part1).jpeg)
(Proses Mengelola Pustaka) : sistem yang mengelola proses memasukan pustaka, mengubah pustaka, menghapus pustaka, dan melihat pustaka. <br>
-pustaka tanpa pengarang : tahap memberikan data data pustaka tanpa pengarang yang ingin dimasukkan ke proses mengelola pustaka.<br>
-pengarang pustaka : tahap memberikan data data pengarang pustaka yang ingin dimasukkan ke proses mengelola pustaka.<br>
-status login : tahap mengambil dan mengecek data status login dari proses sebelumnya.<br>
-pustaka tanpa pengarang : tahap memberikan data data pustaka tanpa pengarang yang ingin dimasukkan ke proses selanjutnya.<br>
-pustaka : tahap mengirim data pustaka yang ingin dimasukkan ke proses selanjutnya.<br>
-pustaka : tahap mengirim data pustaka yang ingin dimasukkan ke proses mengelola pustaka.<br>
-pengarang pustaka : tahap menunjukan data data pengarang pustaka yang diambil dari proses mengelola pustaka.<br>
--Pada tahap ini ada previlege petugas yang dapat mengubah proses mengelola pustaka,seperti proses memasukkan pustaka, mengubah pustaka, menghapus pustaka, dengan melalui pengecekan status login agar dapat melakukan hal tersebut,selanjutnya data terakhir tersebut bisa  dikembalikan ke sistem lainnya.--<br>
--dan ada juga previlege yang dimiliki anggota yaitu proses melihat pustaka dengan melalui fase status login, pustaka tanpa pengarang, dan pengarang pustaka pada proses melihat pustaka.--<br>


# DFD Level 2(Mengelola Pustaka)
![level2](img/level2(part2).jpeg)
<br>Terdapat 4 proses di Tahap mengelola pustaka ini<br>
<br>(Proses Memasukkan pustaka)<br>
-status login : tahap mengambil dan mengecek data status login dari proses sebelumnya;<br>
-pustaka : tahap mengambil data pustaka yang ingin dimasukkan;<br>
-pustaka tanpa pengarang : tahap memberikan data data pustaka tanpa pengarang yang ingin dimasukkan;<br>
-pengarang pustaka : tahap memberikan data data pengarang pustaka yang ingin dimasukkan.<br>
(Proses Mengubah pustaka)<br>
-status login : tahap mengambil dan mengecek data status login dari data sebelumnya;<br>
-pustaka : tahap mengambil data pustaka yang ingin diubah;<br>
-pustaka tanpa pengarang : tahap memberikan data data pustaka tanpa pengarang yang ingin diubah;<br>
-pengarang pustaka : tahap memberikan data data pengarang pustaka yang ingin diubah.<br>
(Proses Menghapus pustaka)<br>
-status login : tahap mengambil dan mengecek data status login dari proses sebelumnya;<br>
-pustaka : tahap mengambil data pustaka yang ingin dihapus;<br>
-pustaka tanpa pengarang : tahap memberikan data data pustaka tanpa pengarang yang ingin di hapus;<br>
-pengarang pustaka : tahap memberikan data-data pengarang pustaka yang ingin di hapus.<br>
(Proses Melihat pustaka)<br>
-status login : tahap mengambil dan mengecek data status login dari proses sebelumnya;<br>
-pustaka : tahap memberikan data pustaka yang ingin dilihat;<br>
-pustaka tanpa pengarang : tahap mengambil data pustaka tanpa pengarang yang ingin di lihat;<br>
-pengarang pustaka : tahap mengambil data pengarang pustaka yang ingin di lihat.<br>


# DFD Level 2(Mengelola Anggota)
![level2](img/level2(part3).jpeg)
<br>Terdapat 5 proses pada tahap Mengelola Anggota.<br>
<br>(Proses Memasukkan anggota)<br>
-status login : pertama yaitu tahap pengecekan data status login dari proses sebelumnya<br>
-anggota : tahap mengambil data anggota yang ingin dimasukkan<br>
-anggota tanpa telepon : tahap mengirim data data anggota tanpa telepon yang ingin di masukkan<br>
-telepon anggota : tahap mengirim data data telepon anggota yang ingin di masukkan<br>
(Proses Mengubah anggota)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-anggota : tahap mengambil data anggota yang ingin di ubah<br>
-anggota tanpa telepon : tahap mengirim data anggota tanpa telepon yang ingin di ubah<br>
-telepon anggota : tahap mengirim data telepon anggota yang ingin di ubah<br>
(Proses Menghapus anggota)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-anggota : tahap mengambil data anggota yang ingin di hapus<br>
-anggota tanpa telepon : tahap mengirim data tanpa telepon yang ingin di hapus<br>
-telepon anggota : tahap mengirim data telepon anggota yang ingin dihapus<br>
(Proses Melihat anggota)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-anggota : proses mengirim data anggota yang ingin dilihat<br>
-anggota tanpa telepon : tahap mengambil data anggota tanpa telepon yang ingin dilihat<br>
-telepon anggota : tahap mengambil data anggota tanpa telepon yang ingin dilihat<br>
(Proses Mencari anggota)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-pencarian anggota : tahap mengambil dan mengecek data anggota yang ingin dicari<br>
-anggota : tahap mengirim data anggota yang dicari<br>
-anggota tanpa telepon : tahap mengambil data anggota tanpa telepon yangg dicari<br>
-telepon anggota : tahap mengambil data telepon anggota yang dicari<br>


# DFD Level 2(Mengelola Peminjaman)
![level2](img/level2(part4).jpeg)
<br>Terdapat 5 proses pada tahap Mengelola Peminjaman<br>
<br>(Proses Memasukkan peminjaman)<br>
-status login : tahap mengambil pengecekan data status login dari proses sebelumnya<br>
-peminjaman : tahap mengambil dan mengirim data peminjaman yang ingin dimasukkan<br>
(Proses Mengubah peminjaman)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-peminjaman : tahap mengambil dan mengirim data peminjaman yang ingin diubah<br>
(Proses Menghapus peminjaman)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-peminjaman : tahap mengambil dan mengirim data peminjaman yang ingin dihapus<br>
(Proses Melihat peminjaman)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-pemijaman : tahap mengambil dan mengirim data peminjaman yang ingin dilihat<br>
Proses Mencari peminjaman:<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-pencarian peminjaman : tahap mengambil data peminjaman yang di cari<br>
-peminjaman : tahap mengambil dan mengirim data peminjaman yang di cari<br>


# DFD Level 2(Mengelola Petugas)
![level2](img/level2(part5).jpeg)
<br>Terdapat 5 proses pada tahap Mengelola Petugas<br>
<br>(Proses Memasukkan Petugas)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-petugas : tahap mengambil dan mengirim data petugas yang ingin dimasukkan<br>
(Proses Mengubah Petugas)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-petugas : tahap mengambil dan mengirim data petugas yang ingin diubah<br>
(Proses Menghapus Petugas)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-petugas : tahap mengambil dan mengirim data petugas yang ingin dihapus<br>
(Proses Melihat Petugas)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-petugas : tahap mengambil dan mengirim data petugas yang ingin dilihat<br>
(Proses Mencari Petugas)<br>
-status login : tahap pengecekan data status login dari proses sebelumnya<br>
-mencari petugas : tahap mengambil data petugas yang dicari<br>
-petugas : tahap mengambil dan mengirim data petugas yang dicari<br>

# DFD Kamus Data 

![kamusdata](img/kamus_data.jpeg)



