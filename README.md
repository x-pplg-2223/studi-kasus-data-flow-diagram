

# Fajril Yusin Supriadi

# Level 0
[![level0](img/level0.png)

<i>Terdapat 2 Aktor yang terlibat yaitu;
 [Anggota/Pengunjung perpustakaan]<br>
 Anggota/Pengunjung Perpustakaan adalah Seorang Anggota atau pengunjung yang ingin meminjam ke perpustakaan.<br> 
 [Petugas Perpustakaan]<br>
 Petugas Perpustakaan adalah seorang petugas yang memenuhi permintaan/pinjaman dari pengunjung yang sudah di proses dan sudah mendapat izin dari sistem yang mengelola informasi manajemen perpustakaan.<br> 
 (Mengelola sistem informasi manajemen perpustakaan)<br> 
 Sistem yang mengelola permintaan anggota dan memenuhi permintaan anggota yang di dapatkan dari petugas.<br> 
 Penjelasan komponen-komponen DFD level 0: 
 •Petugas perpustakaan melakukan login;<br> 
 •Dan sistem informasi akan memberikan notif/pesan kepada petugas perpustakaan;<br> 
 •Petugas perpustakaan mengirim pencarian pustaka ke sistem informasi;<br> 
 •Anggota/pengunjung mencari sebuah buku yang akan dipinjam, dan akan diterima sistem informasi;<br> 
 •Sistem informasi memberikan data pustaka pada petugas perpustakaan;<br> 
 •Petugas perpustakaan memberikan data buku yang dicari pengunjung ke sistem informasi;<br> 
 •Petugas perpustakaan mencari data anggota/pengunjung yang ingin meminjam tersebut di database sistem informasi;<br> 
 •Sistem informasi memberikan data anggota/pengunjung yang ingin meminjam buku pada petugas perpustakaan;<br> 
 •Petugas perpustakaan memberikan akses untuk anggota/pengunjung;<br> 
 •Petugas perpustakaan melakukan pencarian peminjaman di sistem informasi;<br> 
 •Petugas perpustakaan memberikan formulir peminjaman pada sistem informasi untuk diisi tanggal,buku yg dipinjam,dll;<br> 
 •Lalu sistem memberikan data peminjaman tersebut ke petugas perpustakaan;<br> 
 •Selanjutnya tahap mencari data petugas yang akan melayani peminjaman tersebut;<br> 
 •Petugas memberikan akses untuk memberikan buku yang akan dipinjam;<br> 
 •Sistem informasi memberikan konfirmasi pada petugas perpustakaan;<br> 
 •Sistem memberikan data pustaka pada anggota/pengunjung perpustakaan;<br></i>
# level 1
[![level1](img/level1.png)

<i>•Anggota mencari pustaka ke sistem dan petugas perpustakaan mencari pustaka di sistem dan mengirimnya ke petugas perpustakaan

<br> •Lalu Petugas perpustakaan login dan sistem memberikan pesan login<br>

•Sistem memeriksa sistem login 

<br> •Petugas perpustakaan mencari data pustaka di sistem dan sistem mencari data pustaka di storage pustaka 

<br> •Dan Petugas perpustakaan mencari data peminjaman di sistem dan sistem mencari data peminjaman di storage peminjaman 

<br> •Petugas perpustakaan mencari data anggpta di sistem dan sistem mencari data anggota tanpa telepon di storage anggota dan mencari data telepon anggota di storage telepon 

<br> •Terakhir Petugas perpustakaan mencari data petugas di sistem dan sistem mencari data di storage petugas<i/>

# level 2
[![Level2.](img/Level2.png)

<i>•Sistem yang mengelola proses memasukan pustaka, mengubah pustaka, menghapus pustaka, dan melihat pustaka<br> 

 •Pustaka tanpa pengarang- Proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan ke proses<br> mengelola pustaka<br> 

 •Pengarang pustaka- Proses memberikan data data pengarang pustaka yang ingin dimasukkan ke proses mengelola pustaka<br> 

 •Status login- Proses mengambil dan mengecek data status login dari proses sebelumnya<br> 

 •Pustaka tanpa pengarang- Proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan ke proses selanjutnya<br> 

 •Pustaka- Proses mengirim data pustaka yang ingin dimasukkan ke proses selanjutnya<br> 

 •Pustaka- Proses mengirim data pustaka yang ingin dimasukkan ke proses mengelola pustaka<br> 

 •Pengarang pustaka- Proses menunjukan data data pengarang pustaka yang diambil dari proses mengelola pustaka<br></i>

# Level 2 Mengelola Pustaka
[![pustaka](img/pustaka.png)

<i>•Status login- Proses mengambil dan mengecek data status login dari proses sebelumnya<br> 

 -Pustaka- Proses mengambil data pustaka yang ingin dimasukkan<br> 

 •Pustaka tanpa pengarang- Proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan<br> 

 •Pengarang pustaka- Proses memeberikan data data pengarang pustaka yang ingin dimasukkan<br> 

 Proses Mengubah pustaka:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Pustaka- Proses mengambil data pustaka yang ingin diubah<br> 

 •Pustaka tanpa pengarang- Proses memberikan data data pustaka tanpa pengarang yang ingin diubah<br> 

 •Pengarang pustaka- Proses memberikan data data pengarang pustaka yang ingin diubah<br> 

 Proses Menghapus pustaka:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari proses sebelumnya<br> 

 •Pustaka- Proses mengambil data pustaka yang ingin dihapus<br> 

 •Pustaka tanpa pengarang- Proses memberikan data data pustaka tanpa pengarang yang ingin di hapus<br> 

 •Pengarang pustaka- Proses memberikan data data pengarang pustaka yang ingin di hapus<br> 

 Proses Melihat pustaka:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari proses sebelumnya<br> 

 •Pustaka- Proses memberikan data pustaka yang ingin dilihat<br> 

 •Pustaka tanpa pengarang- Proses mengambil data pustaka tanpa pengarang yang ingom di lihat<br> 

 •Pengarang pustaka- Proses mengambil data pengarang pustaka yang ingin di lihat<br></i>

# Level 2 Mengelola Anggota
[![level2-anggota](img/level2-anggota.png)

<i>•Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Anggota- Proses mengambil data anggota yang ingin dimasukkan<br> 

 •Anggota tanpa telepon- Proses mengirim data data anggota tanpa telepon yang ingin di masukkan<br> 

 •Telepon anggota- Proses mengirim data data telepon anggota yang ingin di masukkan<br> 

 Proses Mengubah anggota:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Anggota- Proses mengambil data anggota yang ingin di ubah 

 •Anggota tanpa telepon- Proses mengirim data anggota tanpa telepon yang ingin di ubah<br> 

 •Telepon anggota- Proses mengirim data telepon anggota yang ingin di ubah<br> 

 Proses Menghapus anggota:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Anggota- Proses mengambil data anggota yang ingin di hapus<br> 

 •Anggota tanpa telepon- Proses mengirim data tanpa telepon yang ingin di hapus<br> 

 •Telepon anggota- Proses mengirim data telepon anggota yang ingin dihapus<br> 

 Proses Melihat anggota:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Anggota- Proses mengirim data pustaka yang ingin dilihat<br> 

 •Anggota tanpa telepon- Proses mengambil data anggota tanpa telepon yang ingin dilihat<br> 

 •Telepon anggota- Proses mengambil data anggota tanpa telepon yang ingin dilihat<br> 

 Proses Mencari anggota:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Pencarian anggota- Proses mengambil dan mengecek data anggota yang ingin dicari<br> 

 •Anggota- Proses mengirim data anggota yang dicari<br> 

 •Anggota tanpa telepon- Proses mengambil data anggota tanpa telepon yangg dicari<br> 

 •Telepon anggota- Proses mengambil data telepon anggota yang dicari<br></i>

# Level 2 Mengelola Peminjaman
[![level2-mengelolapeminjaman](img/level2-mengelolapeminjaman.png)

<i>•Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Peminjaman- Proses mengambil dan mengirim data peminjaman yang ingin dimasukkan<br> 

 Proses Mengubah peminjaman:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Peminjaman- Proses mengambil dan mengirim data peminjaman yang ingin diubah<br> 

 Proses Menghapus peminjaman:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Peminjaman- Proses mengambil dan mengirim data peminjaman yang ingin dihapus<br> 

 Proses Melihat peminjaman:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Peminjaman- Proses mengambil dan mengirim data peminjaman yang ingin dilihat<br> 

 Proses Mencari peminjaman:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Pencarian peminjaman- Proses mengambil data peminjaman yang di cari<br> 

 •Peminjaman- Proses mengambil dan mengirim data peminjaman yang di cari<br></i>

# Level 2 Mengelola Petugas
[![level2-mengelolapetugas-1](img/level2-mengelolapetugas(1).png)

<i>•Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Petugas- Proses mengambil dan mengirim data petugas yang ingin dimasukkan<br> 

 Proses Mengubah Petugas:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Petugas- Proses mengambil dan mengirim data petugas yang ingin diubah<br> 

 Proses Menghapus Petugas:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Petugas- Proses mengambil dan mengirim data petugas yang ingin dihapus<br> 

 Proses Melihat Petugas:<br> 

 •Status Login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Petugas- Proses mengambil dan mengirim data petugas yang ingin dilihat<br> 

 Proses Mencari Petugas:<br> 

 •Status login- Proses mengambil dan mengecek data status login dari data sebelumnya<br> 

 •Mencari petugas- Proses mengambil data petugas yang dicari<br> 

 •Petugas- Proses mengambil dan mengirim data petugas yang dicari<br></i>

# Kamus Data
[![Kamus-Data-Jril](img/KamusDataJril.png)
