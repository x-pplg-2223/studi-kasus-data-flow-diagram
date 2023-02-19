# studi-kasus-data-flow-diagram
# Shezil
# level-0 
[![level-0.jpg](https://i.postimg.cc/MGXnDDt6/level-0.jpg)](https://postimg.cc/zLZDDT96)
Penjelasan DFD Level 0 :
Ada dua entitas luar yang terlibat di dalam sistem yaitu:
1.Anggota/Pengunjung Perpustakaan
2.Petugas Perpustakaan
~ Anggota/Pengunjung Perpustakaan melakukan pencarian pustaka dan Sistem mengelola informasi manajemen perpustakaan melalui Petugas Perpustakaan, dari Petugas login ke Sistem, Sistem memberikan pesan login/logout ke Petugas, kemudian Petugas melakukan pencarian pustaka ke Sistem, Sistem dan Petugas mendapatkan hasil pustaka, kemudian Petugas melakukan pencarian anggota, Sistem dan Petugas mendapatkan hasil anggota, lalu Petugas melakukan pencarian peminjaman ke Sistem, Sistem dan Petugas mendapatkan hasil peminjaman, kemudian Petugas Perpustakaan melakukan pencarian petugas, Sistem dan Petugas mendapatkan hasil petugas, setelah itu Sistem memberikan hasil pustaka kepada Anggota/Pengunjung Perpustakaan.
-DFD level 0 / Diagram konteks
Diagram konteks adalah tingkat tertinggi dalam DFD dimana diagram ini hanya memiliki satu proses inti yang menggambarkan keseluruhan sistem.

# level-1
[![levell-1.jpg](https://i.postimg.cc/Pr2fRDCP/levell-1.jpg)](https://postimg.cc/GHT1BHJC)
Penjelasan DFD Level 1 :
~ Anggota/Pengunjung Perpustakaan melakukan pencarian pustaka dan Sistem mengelola pustaka melalui Petugas Perpustakaan, setelah itu hasil pustaka dari Sistem di berikan kepada Petugas, lalu di berikan kepada Anggota.
~ Anggota/Pengunjung Perpustakaan melakukan peminjaman dan Sistem mengelola peminjaman melalui Petugas Perpustakaan, Petugas melakukan pencarian peminjaman kepada Sistem, Sistem memeriksa status login, Sistem status login memberikan hasil kepada Sistem.
~ Petugas melakukan pencarian anggota kepada Sistem, Sistem memeriksa status login, status login memberikan hasil kepada Sistem, setelah itu hasil dari Sistem di berikan kepada Petugas.
~ Petugas melakukan pencarian petugas kepada Sistem, Sistem memeriksa status login, status login memberikan hasil kepada Sistem, setelah itu hasil dari Sistem di berikan kepada Petugas.
~ Sistem status memberikan hasil login/logout kepada Petugas.
-DFD level 1 bertujuan untuk menggambarkan keseluruhan sistem dengan lebih detail. 
Pada DFD level 1 proses dipecah menjadi beberapa proses.

# dfd level 2 
[![dfd-level-2.jpg](https://i.postimg.cc/0y4k8qdv/dfd-level-2.jpg)](https://postimg.cc/JsbVqv2Y)
Penjelasan DFD Level 2 :
-Pada DFD level 2 kita melakukan dekomposisi pada setiap proses yg ada di level 1.
DFD level 2 dari proses mengelola pustaka pada DFD level 1.

# level-2 Mengelola Pustaka
[![level-2-mengelola-pustaka.jpg](https://i.postimg.cc/85QT6B0n/level-2-mengelola-pustaka.jpg)](https://postimg.cc/hJsFFxg9)
Penjelasan DFD Level-2 Mengelola Pustaka :
~ Mengelola Pustaka meliputi ; Memasukkan, Mengubah, Menghapus, dan Melihat Pustaka.
-DFD level 2 dari proses mengelola pustaka pada DFD level 1.

# level-2 Mengelola Anggota
[![level-2-mengelola-anggota.jpg](https://i.postimg.cc/VLLmnNK1/level-2-mengelola-anggota.jpg)](https://postimg.cc/YjV5wtcy)
Penjelasan DFD Level-2 Mengelola Anggota :
~ Mengelola Anggota meliputi ; Memasukkan, Mengubah, Menghapus, Melihat dan Mencari Anggota.
-DFD level 2 dari proses mengelola anggota pada DFD level 1.

# level-2 Mengelola Peminjaman
[![level-2-mengelola-peminjaman.jpg](https://i.postimg.cc/yx8tgDsb/level-2-mengelola-peminjaman.jpg)](https://postimg.cc/JDSPS4yN)
Penjelasan DFD Level-2 Mengelola Peminjaman :
~ Mengelola Peminjaman meliputi ; Memasukkan, Mengubah, Menghapus, Melihat dan Mencari Peminjaman.
-DFD level 2 dari proses mengelola peminjaman pada DFD level 1.

# level-2 Mengelola Petugas
[![level-2-mengelola-petugas.jpg](https://i.postimg.cc/y8cQNm0N/level-2-mengelola-petugas.jpg)](https://postimg.cc/9DXt8q83)
Penjelasan DFD Level-2 Mengelola Petugas :
~ Mengelola Petugas meliputi ; Memasukkan, Mengubah, Menghapus, Melihat dan Mencari Petugas.
-DFD level 2 dari proses mengelola petugas pada DFD level 1.

# Kamus Data
[![kamus-data.jpg](https://i.postimg.cc/br4gyrJb/kamus-data.jpg)](https://postimg.cc/vxLfXQ5H)
