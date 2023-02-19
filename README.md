# studi-kasus-data-flow-diagram
# Hashbi abdillah
# DFD-level-0
[![dfd-level0-Page-1.png](https://i.postimg.cc/XqcNfsQt/dfd-level0-Page-1.png)](https://postimg.cc/hQvqg1F0)
Pada level ini terbagi menjadi 2 jalur :

 1.Anggota/Pengunjung Perpustakaan

 2.Petugas Perpustakaan

1.Anggota/Pengunjung Perpustakaan 

Anggota atau pengunjung perpustakaan dapat mencari Pustaka pada sistem informasi manajemen perpustakaan 

lalu mengirim masukan (input) berupa data pencarian untuk proses pencarian Pustaka dan menerima keluaran (output) berupa Pustaka yang dicari.

2.Petugas Perpustakaan

Petugas perpustakaan melakukan banyak berinteraksi dengan sistem. dapat diuraikan sebagai berikut : Melakukan login, mencari buku, 

mengelola data buku, mencari peminjaman, mengelola data peminjaman, mencari anggota, mengelola data anggota, mencari petugas dan data mengelola petugas.

Aliran data dikirim dari  petugas yang masuk ke dalam sistem adalah

data login untuk proses login ke sistem

data pencarian pustaka untuk proses pencarian dan pengelolaan pustaka

data peminjaman untuk proses pencarian dan pengelolaan data peminjaman

data anggota untuk proses pencarian dan pengelolaan data anggota

data petugas untuk proses pencarian dan pengelolaan data petugas.

Dari masukan yang diterima oleh sistem, selanjutnya aliran data yang keluar dari sistem ke petugas adalah

Pesan login/logout dari proses login/logout

data buku dari proses pencarian dan pengelolaan pustaka

data peminjaman dari proses pencarian dan pengelolaan data peminjaman

data anggota dari proses pencarian dan pengelolaan data anggota

data petugas dari proses pencarian dan pengelolaan data petugas.
# DFD-level-1
[![dfd-level1.png](https://i.postimg.cc/FR25ZJ1L/dfd-level1.png)](https://postimg.cc/S27vQR6S)
1.anggota pengunjung mencari pustaka
pustaka ini dicari oleh petugas jika pengarang nya bertemu akan langsung diberi outputnya jika tidak pustaka tampa pengarang maka outputnya akan disuru balik ke awal "mencari pustaka"
3. Data buku  yang dipinjam dimasukan ke file "Peminjaman"  lalu saat buku yang dipinjam akan dikembalikan petugas memeriksa file "Peminjaman" buku apa saja yang dia pinjam
4. saat pencarian anggota, akan diproses dahulu apakah dia sudah terdaftar atau belum, jika anggota belum terdaftar dan ingin meminjam buku, nama dan nomor telepon peminjam yang belum akan dimasukan ke file nama "Anggota" dan "telepon". jika anggota tidak memiliki nomor telepon maka peminjam tidak bisa meminjam buku 
5. lalu petugas harus login untuk mengelola pustaka, peminjaman , anggota, dan petugas lainnya
6. jika proses login diterima, petugas akan mendapat verifikasi "status login" dan notifikasi login. petugas bisa langsung mengelola pustaka, peminjaman , anggota dan petugas lainnya    
7. jika petugas sudah logout maka petugas akan diberi notifikasi lagi bahwa dia sudah logout "pesan login/logout"
# DFD-level-2
[![dfd-level2.png](https://i.postimg.cc/1XcCqgFP/dfd-level2.png)](https://postimg.cc/m1kyxgV6)
2. jika buku yang dicari tanpa pengarang maka output akan langsung diberikan "Pustaka" Jika buku yang dicari ditemukan nama pengarang nya maka outputnya akan langsung diberikan "Pustaka Dengan Pengarang"

3. Jika ingin Mengedit dan melihat pustaka maka diperlukan "Status Login" untuk Mengedit dan melihat pustaka
# DFD-level-2-mengelola pustaka
[![dfd-level2-mengelola-pustaka.png](https://i.postimg.cc/TYK5h8vN/dfd-level2-mengelola-pustaka.png)](https://postimg.cc/3dHxbcR2)-jika ingin memasukan, mengubah dan menghapus pustaka 
maka petugas harus login terlebih dahulu dan memasukan, mengubah dan menghapus pustaka 
maka inputnya akan menjadi dua :
1. Pustaka tanpa pengarang
2. Pengarang Pustaka
-jika ingin melihat pustaka, maka pengguna harus login, lalu diperiksa apakah dia terdaftar sebagai anggota atau petugas melalui " status login", maka output yang dikeluarkan adalah data pustaka yang ada
# DFD-level-2-mengelola anggota
[![dfd-level2-mengelola-anggota.png](https://i.postimg.cc/SRCs74Qm/dfd-level2-mengelola-anggota.png)](https://postimg.cc/7JPwwpTR)
-jika ingin memasukan, mengubah dan menghapus Anggota

maka petugas harus login terlebih dahulu dan memasukan, mengubah dan menghapus Anggota

maka Inputnya akan menjadi dua :

1. Anggota tanpa telepon

2. telepon anggota

Jikq ingin melihqt anggota maka petugas harus login, dan akan mengeluarkan output :

1. anggota tanpa telepon

2. telepon anggota

Jika petugas ingin mencari anggota maka petugas harus login , dan data akan diberikan pada petugas lalu data yang dikeluarkan atau output yang diberikan : 

1. anggota tanpa telepon

2. telepon anggota
# DFD-level-2-mengelola peminjaman
[![dfd-level2-peminjaman.png](https://i.postimg.cc/Z57TNnPr/dfd-level2-peminjaman.png)](https://postimg.cc/gxhFFYTJ)-jika ingin memasukan, mengubah dan menghapus Peminjaman

maka petugas harus login terlebih dahulu dan memasukan, mengubah dan menghapus Peminjaman

maka Inputnya akan dimasukan ke file:

1. Peminjaman

Jikq ingin melihat data Peminjaman maka petugas harus login, dan akan mengeluarkan output :

1. Peminjaman

Jika petugas ingin mencari peminjaman maka petugas harus login , dan data akan diberikan pada petugas lalu data yang dikeluarkan atau output yang diberikan ada di di data "Peminjaman"
# DFD-level-2-mengelola petugas
[![dfd-level2-meneglola-petugas.png](https://i.postimg.cc/nLb30Y1Z/dfd-level2-meneglola-petugas.png)](https://postimg.cc/68cVQZS1)-jika ingin memasukan, mengubah dan menghapus Petugas

maka petugas harus login terlebih dahulu dan memasukan, mengubah dan menghapus Peminjaman

maka Inputnya akan dimasukan ke file:

1. Petugas

Jikq ingin melihat data Peminjaman maka petugas harus login, dan akan mengeluarkan output :

1. Petugas

Jika petugas ingin mencari peminjaman maka petugas harus login , dan data akan diberikan pada petugas lalu data yang dikeluarkan atau output yang diberikan ada di di data "Petugas"
# KAMUS DATA
[![KAMUSDATA.png](https://i.postimg.cc/1zvv0gJr/KAMUSDATA.png)](https://postimg.cc/gw6ym09x)
