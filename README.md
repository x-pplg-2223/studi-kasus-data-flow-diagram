# studi-kasus-data-flow-diagram
# dfd level 0
![level0](img/Ripa.jpg)
Terdapat 2 Entitas luar/aktor yang terlibat, yaitu : [Anggota/Pengunjung perpustakaan]
Anggota/Pengunjung Perpustakaan adalah Seorang Anggota atau pengunjung yang ingin meminjam ke perpustakaan.
[Anggota/Pengunjung perpustakaan]<br>
pengunjung yang ingin meminjam ke perpustakaan<br>
(mengelola sistem informasi manajemen perpustakaan)<br>
sistem yang mengelola permintaan pengunjung dan memenuhi permintaan pengunjung yang di dapatkan dari petugas<br>
[Petugas Perpustakaan]<br>
petugas yang memenuhi permintaan dari pengunjung yang di dapat dari sistem pengelola<br>
aliran data >><br>
-pencarian pustaka- anggota/pengunjung melakukan pencarian pustaka di sistem informasi<br>
-login- petugas perpustakaan melakukan login pada sistem informasi<br>
-pesan login/logout- sistem informasi memberikan notif/pesan kepada petugas perpustakaan<br>
-pencarian pustaka- petugas perpustakaan mengirim pencarian pustaka ke sistem informasi<br>
-pustaka- sistem informas memberikan pustaka pada petugas perpustakaan<br>
-pustaka- petugas perpustakaan memberikan pustaka yang dicari pengunjung ke sistem informasi<br>
-pencarian anggota- petugas perpustakaan melakukan pencarian anggota di database sistem informasi<br>
-anggota- sistem informasi memberikan data anggota pada petugas perpustakaan<br>
-anggota- petugas perpustakaan memberikan akses anggota kepada sistem informasi<br>
-pencarian peminjaman- petugas perpustakaan melakukan pencarian peminjaman di sistem informasi<br>
-peminjaman- petugas perpustakaan melakukan peminjaman pada sistem informasi<br>
-peminjaman- sistem memberikan peminjaman ke petugas perpustakaan<br>
-pencarian petugas- petugas mencari data petugas<br>
-petugas- petugas memberikan akses untuk memberikan pustaka<br>
-petugas- sistem informasi memberikan konfirmasi pada petugas perpustakaan<br>
-pustaka- sistem memberikan pustaka pada anggota/pengunjung perpustakaan<br>

# dfd level 1
![level1](img/Rip.jpg)

# dfd level 2 no 1
![level2no1](img/ke-1-lvl-2.jpg)
<br>Proses Mengelola Pustaka:<br>
sistem yang mengelola proses memasukan pustaka, mengubah pustaka, menghapus pustaka, dan melihat pustaka<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan ke proses<br> mengelola pustaka<br>
-pengarang pustaka- proses memberikan data data pengarang pustaka yang ingin dimasukkan ke proses mengelola pustaka<br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan ke proses selanjutnya<br>
-pustaka- proses mengirim data pustaka yang ingin dimasukkan ke proses selanjutnya<br>
-pustaka- proses mengirim data pustaka yang ingin dimasukkan ke proses mengelola pustaka<br>
-pengarang pustaka- proses menunjukan data data pengarang pustaka yang diambil dari proses mengelola pustaka<br>

# dfd level 2 no 2
![level2no2](img/ke-2.jpeg)
<br>Proses Memasukkan pustaka:<br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka- proses mengambil data pustaka yang ingin dimasukkan<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin dimasukkan<br>
-pengarang pustaka- proses memeberikan data data pengarang pustaka yang ingin dimasukkan<br>
Proses Mengubah pustaka:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pustaka- proses mengambil data pustaka yang ingin diubah<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin diubah<br>
-pengarang pustaka- proses memberikan data data pengarang pustaka yang ingin diubah<br>
Proses Menghapus pustaka:<br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka- proses mengambil data pustaka yang ingin dihapus<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang yang ingin di hapus<br>
-pengarang pustaka- proses memberikan data data pengarang pustaka yang ingin di hapus<br>
Proses Melihat pustaka:<br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka- proses memberikan data pustaka yang ingin dilihat<br>
-pustaka tanpa pengarang- proses mengambil data pustaka tanpa pengarang yang ingom di lihat<br>
-pengarang pustaka- proses mengambil data pengarang pustaka yang ingin di lihat<br>

# dfd level 2 no 3
![level2no3](img/ke-3.jpeg)
<br>Proses Memasukkan anggota:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-anggota- proses mengambil data anggota yang ingin dimasukkan<br>
-anggota tanpa telepon- proses mengirim data data anggota tanpa telepon yang ingin di masukkan<br>
-telepon anggota- proses mengirim data data telepon anggota yang ingin di masukkan<br>
Proses Mengubah anggota:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-anggota- proses mengambil data anggota yang ingin di ubah
-anggota tanpa telepon- proses mengirim data anggota tanpa telepon yang ingin di ubah<br>
-telepon anggota- proses mengirim data telepon anggota yang ingin di ubah<br>
Proses Menghapus anggota:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-anggota- proses mengambil data anggota yang ingin di hapus<br>
-anggota tanpa telepon- proses mengirim data tanpa telepon yang ingin di hapus<br>
-telepon anggota- proses mengirim data telepon anggota yang ingin dihapus<br>
Proses Melihat anggota:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-anggota- proses mengirim data pustaka yang ingin dilihat<br>
-anggota tanpa telepon- proses mengambil data anggota tanpa telepon yang ingin dilihat<br>
-telepon anggota- proses mengambil data anggota tanpa telepon yang ingin dilihat<br>
Proses Mencari anggota:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pencarian anggota- proses mengambil dan mengecek data anggota yang ingin dicari<br>
-anggota- proses mengirim data anggota yang dicari<br>
-anggota tanpa telepon- proses mengambil data anggota tanpa telepon yangg dicari<br>
-telepon anggota- proses mengambil data telepon anggota yang dicari<br>


# dfd level 2 no 4
![level2no4](img/baru.jpeg)
<br>Proses Memasukkan peminjaman:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-peminjaman- proses mengambil dan mengirim data peminjaman yang ingin dimasukkan<br>
Proses Mengubah peminjaman:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-peminjaman- proses mengambil dan mengirim data peminjaman yang ingin diubah<br>
Proses Menghapus peminjaman:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-peminjaman- proses mengambil dan mengirim data peminjaman yang ingin dihapus<br>
Proses Melihat peminjaman:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pemijaman- proses mengambil dan mengirim data peminjaman yang ingin dilihat<br>
Proses Mencari peminjaman:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pencarian peminjaman- proses mengambil data peminjaman yang di cari<br>
-pemijaman- proses mengambil dan mengirim data peminjaman yang di cari<br>

# dfd level 2 no 5
![level2no5](img/petugas.jpeg)
<br>Proses Memasukkan Petugas:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-petugas- proses mengambil dan mengirim data petugas yang ingin dimasukkan<br>
Proses Mengubah Petugas:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-petugas- proses mengambil dan mengirim data petugas yang ingin diubah<br>
Proses Menghapus Petugas:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-petugas- proses mengambil dan mengirim data petugas yang ingin dihapus<br>
Proses Melihat Petugas:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-petugas- proses mengambil dan mengirim data petugas yang ingin dilihat<br>
Proses Mencari Petugas:<br>
-status login- proses mengambil dan mengecek data status login dari data sebelumnya<br>
-mencari petugas- proses mengambil data petugas yang dicari<br>
-petugas- proses mengambil dan mengirim data petugas yang dicari<br>

# kamusdata
![kamusdata](img/kamusdataasli.jpeg) 