# studi-kasus-data-flow-diagram

<b><u>
Nama  : Nazam Ahmad Fahreyza
Kelas : X PPLG 1
Kelompok 2
</b></u>

# DFD-Level-0 :
[![Diagram-lv0-new.png](https://i.postimg.cc/j2bTgWsw/Diagram-lv0-new.png)](https://postimg.cc/KkJC483x)

### Penjelasan DFD level 0
- Bisa di lihat di atas gambar berikut di dfd level 0 mempunyai sebuah sistem yaitu sistem mengelola informasi manajemen perpustakaan
di gambar tersebut ada dua entitas/aktor yang terlibat yaitu ada anggota perpustakaan dan petugas perpustakaan.

- pada tahap awal pengunjung akan mencari sebuah buku kemudian diterima sistem dan dikirim ke petugas perpustakaan,karena pengunjung tersebut belum login(login tersebut berguna untuk mendapatkan privillage anggota perpustakaan),  maka petugas akan mengirim pesan login ke pengunjung tersebut, saat sudah login kemudian pesan login tersebut terkirim ke petugas perpustakaan. dan pengunjung kembali ke halaman awal untuk mencari buku.anggota mencari buku ke sistem(buku mtk),kemudian pencarian tersebut diterima oleh petugas dan petugas mengirimkan list buku(mtk) dan anggota memilih buku yang di inginkan kemudian petugas mencari anggota yang menginginkan buku(mtk) tersebut, lalu petugas mengirimkan data buku ke sistem dan sistem mengirimkan datanya ke anggota. 

- kebetulan anggota tersebut ingin meminjam buku yang berbeda, kemudian anggota melakukan pencariann buku ke sistem dan sistem mengirimkan pencarian tsb ke petugas perpustakaan.kemudian petugas memverivikasi bahwa dia adalah anggota dan mengirimkan list buku yang diinginkan, anggota tersebut memilih buku dan sistem mengirimkan data buku ke petugas kemudian petugas mencari data petugas yang akan melayani peminjaman ke sisitem dan anggota memilih petugas untuk mencatat tgl peminjaman buku ,nama anggota dll,anggota melakukan peminjaman dan data peminjaman di kirim kesistem,setelah semua syarat peminjaman sudah terpenuhi maka petugas mengirimkan data pustaka yang ingin di pinjam ke sistem dan sistem mengirimkan data pustakanya ke anggota.

#  DFD-Level-1 :
[![Diagram-lv-1-new-1.png](https://i.postimg.cc/tRfRfMrx/Diagram-lv-1-new-1.png)](https://postimg.cc/grVPLNbz)
# DFD-Level-2 :
[![Diagram-lv2-new.png](https://i.postimg.cc/kM0fBks5/Diagram-lv2-new.png)](https://postimg.cc/RqTcYpjr)
# DFD-Level-2-Pustaka :
[![Diagram-lv-2-Mengelola-Pustaka-new.png](https://i.postimg.cc/L8mzY5zR/Diagram-lv-2-Mengelola-Pustaka-new.png)](https://postimg.cc/Ln0qGHC0)
# DFD-Level-2-Mengelola-Anggota :
[![Diagram-lv2-Mengelola-Anggota-new.png](https://i.postimg.cc/bJ2V58gK/Diagram-lv2-Mengelola-Anggota-new.png)](https://postimg.cc/wygktCSV)
# DFD-Level-2-Mengelola-Peminjaman :
[![Diagram-Mengelola-Peminjaman-new.png](https://i.postimg.cc/4yx7d400/Diagram-Mengelola-Peminjaman-new.png)](https://postimg.cc/R62Vpm41)
# DFD-Level-2-Mengelola-petugas :
[![Diagram-Mengelola-Petugas-new.png](https://i.postimg.cc/GtR0JHRM/Diagram-Mengelola-Petugas-new.png)](https://postimg.cc/YGdyt2hg)
# DFD-Kamus-Data :
[![Diagram-Kamus-Data-new.png](https://i.postimg.cc/nLpvJ200/Diagram-Kamus-Data-new.png)](https://postimg.cc/ZWs9P8kd)