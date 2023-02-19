# studi-kasus-data-flow-diagram
# dfd level 0
![level0](img/Ripa.jpg)
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

# dfd level 2 no 2
![level2no2](img/ke-2.jpeg)
Proses Memasukkan pustaka:<br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka- proses mengambil data pustaka yang ingin dimasukkan<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang ke proses selanjutnya<br>
-pengarang pustaka- proses memeberikan data data pengarang pustaka untuk proses selanjutnya<br>
Proses Mengubah pustaka:<br>
-status login: proses mengambil dan mengecek data status login dari data sebelumnya<br>
-pustaka- proses mengambil data pustaka yang ingin diubah<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang ke proses selanjutnya<br>
-pengarang pustaka- proses memberikan data data pengarang pustaka untuk proses selanjutnya<br>
Proses Menghapus pustaka:<br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka- proses mengambil data pustaka yang ingin dihapus<br>
-pustaka tanpa pengarang- proses memberikan data data pustaka tanpa pengarang ke proses selanjutnya<br>
-pengarang pustaka- proses memberikan data data pengarang pustaka untuk proses selanjutnya<br>
Proses Melihat pustaka:<br>
-status login- proses mengambil dan mengecek data status login dari proses sebelumnya<br>
-pustaka- proses memberikan data pustaka yang ingin dilihat<br>
-pustaka tanpa pengarang- proses mengambil data pustaka tanpa pengarang dari proses sebelumnya<br>
-pengarang pustaka- proses mengambil data pengarang psutaka dari proses sebelumnya<br>
# dfd level 2 no 3
![level2no3](img/ke-3.jpeg)

# dfd level 2 no 4
![level2no4](img/baru.jpeg)

# dfd level 2 no 5a
![level2no5](img/petugas.jpeg)

# kamusdata
![kamusdata](img/kamusdataasli.jpeg) 