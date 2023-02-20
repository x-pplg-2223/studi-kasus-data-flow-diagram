# studi-kasus-data-flow-diagram
# Aretha

# DFD-Level-0
[![Ripa-2.jpg](https://i.postimg.cc/GpS62ZTP/Ripa-2.jpg)](https://postimg.cc/R3KgppRq)
penjelasan dfd level 0 : 
- Dalam kasus ini ada dua entitas luar yang terlibat di dalam sistem yaitu:
1.Anggota/Pengunjung perpustakaan
2.Petugas perpustakaan
- Anggota/pengunjung perpustakaan dapat mencari pustaka pada sistem yg ada, karna itu dapat mengirim masukan (input) berupa data pencarian untuk proses pencarian data pustaka dan menerima keluaran (output) berupa data pustaka yang dicari.
- Petugas perpustakaan cukup banyak berinteraksi dengan sistem. Kegiatan yang bisa dilakukan oleh petugas perpustakaan  diantaranya melakukan login, mencari pustaka, mengelola data pustaka, mencari peminjaman, mengelola data peminjaman, mencari anggota, mengelola data anggota, mencari petugas dan data mengelola petugas.
- anggota/pengunjung perpustakaan mencari pustaka, pesan login/logout ke petugas perpustakaan. petugas login ke sistem informasi perpustakaan, sistem mencari keanggotaan ke petugas perpustakaan. petugas mencari anggota ke sistem informasi perpustakaan jika sudah terdaftar menjadi anggota, sistem kembali ke petugas perpustakaan. kemudian petugas mencari petugas ke sistem informasi perpustakaan, sistem informasi perpustakaan kembali mencari peminjaman ke petugas perpustakaan. petugas perpustakaan mencari peminjaman ke sistem, sistem informasi perpustakaan ke pustaka lalu ke petugas perpustakaan. kemudian petugas perpustakaan balik mencari pustaka yg dicari anggota ke sistem informasi perpustakaan, kemudian jika pustaka yg dicari sudah ditemukan oleh sistem, pustaka yg dicari diberikan ke anggota/pengunjung perpustakaan.

# DFD-Level-1
[![Whats-App-Image-2023-02-13-at-22-42-37-1.jpg](https://i.postimg.cc/CLSQbV47/Whats-App-Image-2023-02-13-at-22-42-37-1.jpg)](https://postimg.cc/bdVgjWWS)
penjelasan dfd level 1 :  
- dfd level 1 ini bertujuan untuk menggambarkan keseluruhan sistem dengan lebih detail. tetapi pada dfd level 1 ini proses nya dipecah menjadi beberapa bagian.

# DFD-Level-2
[![Whats-App-Image-2023-02-13-at-22-42-53.jpg](https://i.postimg.cc/V6PR1jGg/Whats-App-Image-2023-02-13-at-22-42-53.jpg)](https://postimg.cc/Z9j3xyhv)
penjelasan dfd level 2 : 
- dalam tahapan ini dfd 2 dibagi menjadi 4 bagian, yaitu : mengelola pustaka, mengelola anggota, mengelola peminjaman, dan mengelola petugas. penjelasannya dibawah ini.

# DFD-Level-2-Mengelola-Pustaka
[![Whats-App-Image-2023-02-13-at-22-43-19.jpg](https://i.postimg.cc/ZKsx0ksC/Whats-App-Image-2023-02-13-at-22-43-19.jpg)](https://postimg.cc/xcHzFZ22)
penjelasan dfd level 2 - mengelola pustaka :
- didalam tahap ini kita bisa memasukan pustaka, mengubah pustaka, menghapus pustaka, dan melihat pustaka.

# DFD-Level-2-Mengelola-Anggota
[![Whats-App-Image-2023-02-13-at-22-44-54.jpg](https://i.postimg.cc/J02H7878/Whats-App-Image-2023-02-13-at-22-44-54.jpg)](https://postimg.cc/Mf1pthj3)
penjelasan dfd 2 - mengelola anggota : 
- ditahapan ini petugas bisa memasukan anggota, mengubah anggota, menghapus anggota, melihat anggota, mencari anggota.
- ditahap ini juga petugas dapat mencari informasi anggota dengan melihat statusnya di sistem.

# DFD-Level-2-Mengelola-Peminjaman
[![Whats-App-Image-2023-02-14-at-10-12-39-1.jpg](https://i.postimg.cc/vZzgD5ZX/Whats-App-Image-2023-02-14-at-10-12-39-1.jpg)](https://postimg.cc/877P0JWr)
penjelasan dfd level 2 - mengelola peminjaman : 
- ditahap ini terdapat 5 bagian yaitu : memasukan peminjaman, mengubah peminjaman, menghapus peminjaman, melihat peminjaman, mencari peminjaman.
- ditahap ini petugas juga bisa mencari siapa saja yg meminjam.

# DFD-Level-2-Mengelola-Petugas
[![Whats-App-Image-2023-02-14-at-10-08-40.jpg](https://i.postimg.cc/9M6shKrx/Whats-App-Image-2023-02-14-at-10-08-40.jpg)](https://postimg.cc/0MCVGtGm)
penjelasan dfd level 2 - mengelola petugas : 
- tahapan mengelola petugas ada 5, yaitu : memasukan petugas, mengubah petugas, menghapus petugas, melihat petugas, mencari petugas.
- di tahap ini anggota bisa mencari petugas dengan melihat di sistem.

# DFD-Kamus-Data
[![Whats-App-Image-2023-02-14-at-10-11-31.jpg](https://i.postimg.cc/ncZwGv7Q/Whats-App-Image-2023-02-14-at-10-11-31.jpg)](https://postimg.cc/pyGZ25s2)