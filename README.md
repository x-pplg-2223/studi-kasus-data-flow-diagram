# studi-kasus-data-flow-diagram

# DFD Level 0
 ![level0.jpg](img/level0.jpeg)

 <B>[Anggota/Pengunjung perpustakaan]</b> 
 <br>
    pengunjung yang ingin meminjam ke perpustakaan
 <br>
 <b>(mengelola sistem informasi manajemen perpustakaan)</b> 
 <br>
    sistem yang mengelola permintaan pengunjung dan memenuhi permintaan pengunjung yang di dapatkan dari petugas 
 <br>
 <b>[Petugas Perpustakaan]</b>
 <br>
    petugas yang memenuhi permintaan dari pengunjung yang di dapat dari sistem pengelola
 <br>
 <center>aliran data >></center>
 <br>
  -pencarian pustaka- anggota/pengunjung melakukan pencarian pustaka di sistem informasi 
 <br>
  -login- petugas perpustakaan melakukan login pada sistem informasi
 <br>
  -pesan login/logout- sistem informasi memberikan notif/pesan kepada petugas perpustakaan
  <br>
  -pencarian pustaka- petugas perpustakaan mengirim pencarian pustaka ke sistem informasi
  <br>
  -pustaka- sistem informas memberikan pustaka pada petugas perpustakaan
  <br>
  -pustaka- petugas perpustakaan memberikan pustaka yang dicari pengunjung ke sistem informasi
  <br>
  -pencarian anggota- petugas perpustakaan melakukan pencarian anggota di database sistem informasi 
  <br>
  -anggota- sistem informasi memberikan data anggota pada petugas perpustakaan 
  <br>
  -anggota- petugas perpustakaan memberikan akses anggota kepada sistem informasi 
  <br>
  -pencarian peminjaman- petugas perpustakaan melakukan pencarian peminjaman di sistem informasi
  <br>
  -peminjaman- petugas perpustakaan melakukan peminjaman pada sistem informasi 
   <br>
  -peminjaman- sistem memberikan peminjaman ke petugas perpustakaan 
  <br>
  -pencarian petugas- petugas mencari data petugas 
  <br>
  -petugas- petugas memberikan akses untuk memberikan pustaka
  <br>
  -petugas- sistem informasi memberikan konfirmasi pada petugas perpustakaan 
  <br>
  -pustaka- sistem memberikan pustaka pada anggota/pengunjung perpustakaan 


# DFD Level 1
 ![dfd-l-1.svg](img/dfd%20l-1.svg)



# DFD Level 2
 ![dfd l-2.jpg](img/dfd%20level%202.jpg)

Setelah dfd level 1 ada proses yang dipecah lagi dan jadi dfd level 2 <br>
<b>Proses Mengelola Pustaka:</b>
sistem yang mengelola proses memasukan pustaka, mengubah pustaka, menghapus pustaka, dan melihat pustaka <br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan ke proses
mengelola pustaka<br>
-pengarang pustaka- proses memberikan data data pengarang pustaka yang ingin dimasukkan ke proses mengelola pustaka<br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan ke proses selanjutnya<br>
-pustaka- proses mengirim data pustaka yang ingin dimasukkan ke proses selanjutnya<br>
-pustaka- proses mengirim data pustaka yang ingin dimasukkan ke proses mengelola pustaka<br>
-pengarang pustaka- proses menunjukan data data pengarang pustaka yang diambil dari proses mengelola pustaka<br>

# DFD Level 2 - pustaka
 ![dfd lv2 pustaka.jpeg](img/dfd%20lv2%20pustaka.jpeg)

Pada dfd level 2 bagian pustaka ada proses begini
   <b>Proses memasukkan pustaka :</b><br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya <br>
-pustaka- proses mengambil data pustaka yang ingin dimasukkan<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan<br>
-pengarang pustaka- proses memeberikan data data pengarang pustaka yang ingin dimasukkan<br>
   <b>Proses Mengubah pustaka :</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pustaka- proses mengambil data pustaka yang ingin diubah<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin diubah<br>
-pengarang pustaka- proses memberikan data data pengarang pustaka yang ingin diubah<br>
   <b>Proses Menghapus pustaka :</b><br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka- proses mengambil data pustaka yang ingin dihapus<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin di hapus<br>
-pengarang pustaka- proses memberikan data data pengarang pustaka yang ingin di hapus<br>
   <b>Proses Melihat pustaka :</b><br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka- proses memberikan data pustaka yang ingin dilihat<br>
-pustaka tanpa pengarang- proses mengambil data pustaka tanpa pengarang yang ingom di lihat<br>
-pengarang pustaka- proses mengambil data pengarang pustaka yang ingin di lihat<br>

 # DFD Level 2 - anggota
 ![MengelolaAnggota (1).jpg](img/MengelolaAnggota%20(1).jpg)
   
   Pada dfd level 2 bagian anggota ada proses begini<br>
<b>Proses Memasukkan anggota:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-anggota- proses mengambil data anggota yang ingin dimasukkan<br>
-anggota tanpa telepon- proses mengirim data data anggota tanpa telepon yang ingin di masukkan<br>
-telepon anggota- proses mengirim data data telepon anggota yang ingin di masukkan<br>
<b>Proses Mengubah anggota:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-anggota- proses mengambil data anggota yang ingin di ubah <br>
-anggota tanpa telepon- proses mengirim data anggota tanpa telepon yang ingin di ubah<br>
-telepon anggota- proses mengirim data telepon anggota yang ingin di ubah<br>
<b>Proses Menghapus anggota:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-anggota- proses mengambil data anggota yang ingin di hapus<br>
-anggota tanpa telepon- proses mengirim data tanpa telepon yang ingin di hapus<br>
-telepon anggota- proses mengirim data telepon anggota yang ingin dihapus<br>
<b>Proses Melihat anggota:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-anggota- proses mengirim data pustaka yang ingin dilihat<br>
-anggota tanpa telepon- proses mengambil data anggota tanpa telepon yang ingin dilihat<br>
-telepon anggota- proses mengambil data anggota tanpa telepon yang ingin dilihat<br>
<b>Proses Mencari anggota:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pencarian anggota- proses mengambil dan mengecek data anggota yang ingin dicari<br>
-anggota- proses mengirim data anggota yang dicari<br>
-anggota tanpa telepon- proses mengambil data anggota tanpa telepon yangg dicari<br>
-telepon anggota- proses mengambil data telepon anggota yang dicari<br>




 # DFD Level 2 - peminjaman
 ![dfd l-2 peminjaman.jpg](img/dfd%20l-2%20peminjaman.jpg)

   Pada dfd level 2 bagian peminjaman ada proses begini<br>
<b>Proses Memasukkan peminjaman:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-peminjaman- proses mengambil dan mengirim data peminjaman yang ingin dimasukkan<br>
<b>Proses Mengubah peminjaman:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-peminjaman- proses mengambil dan mengirim data peminjaman yang ingin diubah<br>
<b>Proses Menghapus peminjaman:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-peminjaman- proses mengambil dan mengirim data peminjaman yang ingin dihapus<br>
<b>Proses Melihat peminjaman:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pemijaman- proses mengambil dan mengirim data peminjaman yang ingin dilihat<br>
<b>Proses Mencari peminjaman:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pencarian peminjaman- proses mengambil data peminjaman yang di cari<br>
-pemijaman- proses mengambil dan mengirim data peminjaman yang di cari<br>

 # DFD Level 2 - petugas
 ![level2-mengelolapetugas (1).jpg](img/level2-mengelolapetugas%20(1).jpg)

pada dfd level 2 bagian petugas ada proses begini 
<b>Proses Memasukkan Petugas:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-petugas- proses mengambil dan mengirim data petugas yang ingin dimasukkan<br>
<b>Proses Mengubah Petugas:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-petugas- proses mengambil dan mengirim data petugas yang ingin diubah<br>
<b>Proses Menghapus Petugas:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-petugas- proses mengambil dan mengirim data petugas yang ingin dihapus<br>
<b>Proses Melihat Petugas:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-petugas- proses mengambil dan mengirim data petugas yang ingin dilihat<br>
<b>Proses Mencari Petugas:</b><br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-mencari petugas- proses mengambil data petugas yang dicari<br>
-petugas- proses mengambil dan mengirim data petugas yang dicari<br>

 # KAMUS DATA
 ![KAMUS DATA.jpg](img/KAMUS%20DATA.jpg)