# studi-kasus-data-flow-diagram

diagram wiwi
 
 # DFD Level 0 - Contect Diagram
 [![dfd-level0context-diagram.jpg](https://i.postimg.cc/k5sZ5JZL/dfd-level0context-diagram.jpg)](https://postimg.cc/d77nHYJ9)
ALIRAN DATA DIKIRIM DARI ENTITAS PETUGAS YANG MASUK KE DALAM SISTEM ADALAH
1. data login untuk proses login ke sistem
2. data pencarian buku untuk proses pencarian dan pengelolaan buku 
3. data peminjaman untuk proses pencarian dan pengelolaan data peminjaman
4. data anggota untuk proses pencarian dan pengelolaan data anggota
5. data petugas untuk proses pencarian dan pengelolaan data petugas.
DARI MASUKAN YANG DITERIMA OLEH SISTEM, SELANJUTNYA ALIRAN 
DATA YANG KELUAR DARI SISTEM KE PETUGAS ADALAH* 
1. Pesan login/logout dari proses login/logout                             
2. data buku dari proses pencarian dan pengelolaan buku
3. data peminjaman dari proses pencarian dan pengelolaan data peminjaman
4. data anggota dari proses pencarian dan pengelolaan data anggota
5. data petugas dari proses pencarian dan pengelolaan data petugas.
 # Gambar 1 (DFD Level 1)
 [![dfd-gambar-level-1.jpg](https://i.postimg.cc/D0rpt7qC/dfd-gambar-level-1.jpg)](https://postimg.cc/Wq47ZLYr)
 DFD LEVEL 2 ADALAH PENGGAMBARAN PROSES YANG DI LAKUKAN OLEH SISTEM UNTUK PETUGAS DAN ANGGOTA
1. mengelola pustaka
2.mengelola peminjaman
3.mengelola anggota
4.mengelola petugas
TAHAPAN ANGGOTA MENCARI ANGGOTA/PENGUNJUNG PERPUSTAKAAN
1. sistem mencari pustaka akan meminta data pustaka kepada petugas perpustakaan
2. petugas perpustakaan akan mengirimkan beberapa data kepada mengelola pustaka
3. anggota mencari pustaka tanpa pengarang maka data tersebut akan dikirim kedalam data pustaka
4. pustaka tanpa pengarang akan kembali langsung kembali kesistem utama
6. maka data tersebut akan dikirim kedalam storage pustaka
7. pustaka tanpa pengarang langsung kembali kesistem utama
8. jika anggota mencari pustaka berupa pengarang
9. maka sistem akan dikirimkan kepada storage pengarang dan pencarian baru akan dikirimkan kesistem utama
10. petugas perpustakaan sistem mengirimkan data berupa login petugas yang kemudian memasukkan data data petugas
11. memeriksa status login
12. sistem memeriksa status login pada mengelola anggota yang akan meminjam buku pada perpustakaan dengan mengambil data anggota
13. lalu dikirimkan kembali ke mengelola petugas
14. kemudian dikirimkan kepada sistem utama
15. lalu terakhir kepada anggota
 # DFD Level 2
[![dfd-level2.jpg](https://i.postimg.cc/900zkf52/dfd-level2.jpg)](https://postimg.cc/4HCJ7sx2)
DFD LEVEL 2  ADALAH
1. tahapan ini terdapat 2 previlege yaitu anggota dan previlege khusus petugas
2. melihat pustaka
3. mencari pustaka
4. tahapan awal adalah sistem membaca dengan data pada status login yang ada
5. mencari buku dengan tanpa pengarang atau dengan pengarang
6. setelah data tersebut diambil data semua tersebut kembali ke sistem awal.
TAHAPAN YANG ADA PADA PRAVILEGE PETUGAS ADALAH
1. memasukan pustaka
2. menghapus pustaka
3. melihat pustaka
4. mencari pustaka

# DFD Level 2 - Mengelola Pustaka
[![dfd-mengelola-pustaka2.jpg](https://i.postimg.cc/WbBpj8Lx/dfd-mengelola-pustaka2.jpg)](https://postimg.cc/GHjnxkpj)
DFD LEVEL 2 MENGELOLA PUSTAKA ADALAH
1. tahapan untuk previlege petugas 
2. tahap ini data yang akan masuk seperti buku pustaka tanpa pengarang
3.  buku terdapat pengarang pustaka pada mengelola pustaka akan di ubah dengan previlege yang khusus petugas
4. Memasukan pustaka
5. Mengubah pustaka
6. menghapus pustaka 
7. pengecekan status login agar dapat melakukan hal tersebut
8.  data terakhir bisa dikembalikan ke sistem lainnya
9.  bisa diakses oleh privilege yang dimiliki anggota
10. melihat pustaka dengan melewati fase status login
11. pustaka tanpa pengarang dan pengarang pustaka pada laman melihat pustaka
 # DFD Level 2 - Mengelola Anggota 
[![dfd-level-contectdiagram-Page-3.jpg](https://i.postimg.cc/zGxzsr7X/dfd-level-contectdiagram-Page-3.jpg)](https://postimg.cc/0zJ1ShhL)
DFD LEVEL 2 MENGELOLA ANGGOTA ADALAH 
1.  tahapan yang dimana terdapat previlege tertentu yang akan bisa mengakses beberada informasi data
2. memasukan anggota
3. mengubah anggota
4. menghapus anggota
5. melihat anggota
6.  menghapus anggota 
7. melihat anggota
8. mencari anggota
9. petugas bisa mencarikan data informasi anggota dengan melihat status anggota di sistem 
10.  petugas mencari pada laman anggota tanpa telepon jika data yang ingin dicari terdapat didalam pada sistem data anggota tanpa telepon.
# DFD Level 2 - Mengelola Peminjaman
[![dfd-level-contectdiagram-Page-5.jpg](https://i.postimg.cc/SK46vcZp/dfd-level-contectdiagram-Page-5.jpg)](https://postimg.cc/zydHLHZd)
DFD LEVEL 2 MENGELOLA PEMINJAMAN 
1. petugas mengecek informasi untuk peminjaman yang ada pada anggota
2.  sistem awal akan memeriksa status login terlebih dahulu agar dapat melihat atau mengakses informasi peminjaman lebih lanjut
3.  petugas bisa menghapus peminjaman setelah memperoleh data anggota peminjaman dan tahap ini petugas bisa menghapus 
4.  menghapus peminjaman berupa menghapus buku peminjaman
# DFD Level 2 - Mengelola Petugas
[![dfd-mengelola-pustaka.jpg](https://i.postimg.cc/2SR8QG6r/dfd-mengelola-pustaka.jpg)](https://postimg.cc/nC2JZvBP)
1. Status  login memasukan data ke proses memasukan petugas 
    2. data petugas mengalirkan data petugas ke proses memasukan petugas
	3 proses memasukan petugas mengalirkan data petugas kepada petugas
	
	1 status login memasukan data ke proses mengubah petugas
	2 data petugas mengalirkan data petugas ke proses mengubah petugas
	3 proses mengubah petugas mengalirkan data petugas ke petugas
	
	1 status login memasukan data ke proses menghapus petugas
	2 data petugas mengalirkan data petugas ke peroses menghapus petugas
	3 proses menghapus data petugas mengalirkan data ke petugas
	
	1 status login memasukan data ke proses ke melihat petugas
	2 proses data mengalirkan data petugas ke petugas
	3 petugas mengalirkan data petugas ke mnelihat petugas
	
	1 status login memasukan data ke proses mencari petugas
	2 petugas mengalirkan data pencarian petugas ke mencari petugas
	3 proses mengalirkan data petugas ke  penyimpanan data petugas
	4 petugas mengalirkan data petugas ke   proses mencari petugas
# kamus data
[![kamus-data.jpg](https://i.postimg.cc/N00znhCt/kamus-data.jpg)](https://postimg.cc/RWjd3Yzp)
Kamus data adalah suatu daftar elemen yang tergonarisir dengan definisi yang tetap dan sesuai dengan sistem dengan user dan analisis sistem yang mempunyai pengertian yang sama tentang input, output, dan komponen.

1. Nama aliran data login pustaka, peminjaman, anggota, petugas Dimana di gunakan proses login (input) Deskripsi data ini merupakan login id password/id "string"Lalu mengakses password 
2. Dimana proses memeriksa status login maka keluaran (output)

Lalu mengelola pustaka (masukan input/output) dan proses mengelola anggota, peminjaman, dan petugas masukan (input) Deskripsi bahwa status login telah sukses sehingga status login menjadi "BOOLEAN"