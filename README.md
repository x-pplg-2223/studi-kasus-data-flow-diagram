# studi-kasus-data-flow-diagram
# TUGAS FAZA #


# DFD LEVEL 0 *
[![Tugas-dfd.jpg](https://i.postimg.cc/7LhSmdTv/Tugas-dfd.jpg)](https://postimg.cc/5HcHtP3p)

# LEVEL 0
Penjelasan berbagai Unsur pada DFD ini adalah sebagai berikut :
- Pada level ini terbagi menjadi 2 jalur :
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


# DFD LEVEL 1 *
[![dfd-l-1-1.png](https://i.postimg.cc/T10rk6Q6/dfd-l-1-1.png)](https://postimg.cc/n9sjzN6R)

# LEVEL 1
Penjelasan berbagai Unsur pada DFD ini adalah sebagai berikut :
1.anggota pengunjung mencari pustaka
pustaka ini dicari oleh petugas jika pengarang nya bertemu akan langsung diberi outputnya jika tidak pustaka tampa pengarang maka outputnya akan kembali ke inputan awal "mencari pustaka"
3. Data buku  yang dipinjam dimasukan ke file "Peminjaman"  lalu saat buku yang dipinjam akan dikembalikan petugas memeriksa file "Peminjaman" buku apa saja yang dia pinjam.
4. saat pencarian anggota, akan diproses dahulu apakah dia sudah terdaftar atau belum, jika anggota belum terdaftar dan ingin meminjam buku, nama dan nomor telepon peminjam yang belum akan dimasukan ke file nama "Anggota" dan "telepon". jika anggota tidak memiliki nomor telepon maka peminjam tidak bisa meminjam buku 
5. lalu petugas harus login untuk mengelola pustaka, peminjaman , anggota, dan petugas lainnya.
6. jika proses login diterima, petugas akan mendapat verifikasi "status login" dan notifikasi login. petugas bisa langsung mengelola pustaka, peminjaman , anggota dan petugas lainnya    
7. jika petugas ingin logout maka petugas akan diberi notifikasi  bahwa dia ingin logout "pesan login/logout"


# DFD LEVEL 2 
[![dfd-level-2.jpg](https://i.postimg.cc/cJ51B5fb/dfd-level-2.jpg)](https://postimg.cc/Ff3Q9pWy)

Penjelesan berbagai unsur pada DFD ini adalah sebagai berikut :
1. jika buku yang dicari tanpa pengarang maka output akan langsung diberikan "Pustaka" Jika buku yang dicari ditemukan nama pengarang nya maka outputnya akan langsung diberikan " Pengarang Pustaka"
2. Jika ingin Mengelola pustaka maka diperlukan "Status Login" untuk melakukan hal tersebut.

# DFD LEVEL 2 Mengelola Perpustakaan
[![soal2-mengelolaperpustakaan.png](https://i.postimg.cc/ZYLNrJC7/soal2-mengelolaperpustakaan.png)](https://postimg.cc/23V3YRdh)

Penjelasan berbagai unsur pada DFD ini adalah sebagai berikut :
-jika ingin memasukan, mengubah dan menghapus pustaka 
maka petugas harus login terlebih dahulu dan memasukan, mengubah dan menghapus pustaka 
maka outputnya akan menjadi dua :
1. Pustaka tanpa pengarang
2. Pengarang Pustaka
-jika ingin melihat pustaka, maka pengguna harus login, lalu diperiksa apakah dia terdaftar sebagai anggota atau petugas melalui " status login", maka output yang dikeluarkan adalah data pustaka yang ada.

# DFD LEVEL 2 Mengelola Anggota 
[![Mengelola-Anggota.png](https://i.postimg.cc/cJN198zQ/Mengelola-Anggota.png)](https://postimg.cc/3knHWWYR)

Penjelasan berbagai unsur pada DFD ini adalah sebagai berikut :
-jika ingin memasukan, mengubah dan menghapus Anggota
maka petugas harus login terlebih dahulu dan memasukan, mengubah dan menghapus Anggota
maka Inputnya akan menjadi dua :
1. Anggota tanpa telepon
2. telepon anggota

Jikq ingin melihat anggota maka petugas harus login, dan akan mengeluarkan output :
1. anggota tanpa telepon
2. telepon anggota

Jika petugas ingin mencari anggota maka petugas harus login , dan data akan diberikan pada petugas lalu data yang dikeluarkan atau output yang diberikan : 
1. anggota tanpa telepon
2. telepon anggota

# DFD LEVEL 2 Mengelola  Peminjaman
[![level2-mengelolapeminjaman.jpg](https://i.postimg.cc/BbNPnfbG/level2-mengelolapeminjaman.jpg)](https://postimg.cc/p5hLs7K0)

Penjelasan berbagai Unsur pada DFD ini adalah sebagai berikut :

-jika ingin memasukan, mengubah dan menghapus Peminjaman
maka petugas harus login terlebih dahulu dan memasukan, mengubah dan menghapus Peminjaman
maka Inputnya akan dimasukan ke file:
1. Peminjaman

Jikq ingin melihat data Peminjaman maka petugas harus login, dan akan mengeluarkan output :
1. Peminjaman

Jika petugas ingin mencari peminjaman maka petugas harus login , dan data akan diberikan pada petugas lalu data yang dikeluarkan atau output yang diberikan ada di di data "Peminjaman"

# DFD LEVEL 2 Mengelola Petugas
[![soal2-mengelolaperpustakaan.png](https://i.postimg.cc/ZYLNrJC7/soal2-mengelolaperpustakaan.png)](https://postimg.cc/23V3YRdh)

Penjelasan berbagai unsur pada DFD ini adalah sebagai berikut :
Jika ingin memasukan, mengubah dan menghapus Petugas
maka petugas harus login terlebih dahulu dan memasukan, mengubah dan menghapus Peminjaman
maka Inputnya akan dimasukan ke file:
1. Petugas

Jikq ingin melihat data Peminjaman maka petugas harus login, dan akan mengeluarkan output :
1. Petugas

Jika petugas ingin mencari peminjaman maka petugas harus login , dan data akan diberikan pada petugas lalu data yang dikeluarkan atau output yang diberikan ada di di data "Petugas"

# KAMUS DATA
[![KAMUS-DATA.jpg](https://i.postimg.cc/fbrs4t22/KAMUS-DATA.jpg)](https://postimg.cc/7C0d06y0)
	