# studi-kasus-data-flow-diagram

<b><u>
Nama  : Nazam Ahmad Fahreyza
<br>
Kelas : X PPLG 1
<br>
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

### Penjelasan DFD level 1
- pada dfd level 0 kemudian diperjelas prosesnya di dfd level 1 ini, berikut penjelasannya

- pada tahapan ini anggota perpustakaan mencari data pustaka ke sistem dan sistem akan meminta data ke petugas perpustakaan apakah sudah login atau belum dan bilamana anggota mencari buku tanpa pengarang maka petugas perpustakaan mengirim data pustaka ke dalam mengelola pustaka dan di proses mengelola pustaka akan mengirimkan buku tanpa pengarang ke dalam storage pustakan dan dikirimkan datanya ke sistem utama dan jika anggota mencari buku dengan pengarang maka petugas akan mengirim ke mengelola pustaka dan di proses lalu dicek ke storage pengarang pustaka dan langsung dikirimkan ke sistem utama.

- di tahap selanjutnya ada mengelola peminjaman anggota akan meminjam sebuah pustaka ke sistem dan sistem meminta petugas perpustakaan untuk mengirimkan data yang ingin dipinjam ke proses mengelola peminjaman ,di proses mengelola peminjaman akan di cek status loginnya jika sudah login maka akan terjadi proses pengecekan peminjaman di storage peminjaman dan dikembalikan data peminjaman ke petugas dan mengirimkannya ke mengelola pustaka jika anggota meminjam buku dengan pengarang makan akan dikirim ke sistem utama lalu ke anggota.

- selanjutnya ada tahap mencari anggota , sama seperti proses sebelumnya anggota akan mencari/meminjam sebuah buku ke sistem dan dikirim ke petugas perpustakaan melalui proses pencarian buku dan ke proses peminjaman sebelum proses peminjaman selesai dicek terelbih dahulu status loginnya jika sudah maka akan di cari anggota yang ingin melakukan peminjaman di proses mengelola anggota petugas akan mengecek data anggota dari storage telepon anggota dan akan diambil dan dikirimkan ke sistem utama agar syarat peminjaman terpenuhi dan sistem akan mengirimkan datanya ke anggota.

- pada proses yang selanjutnya adalah proses mengelola petugas , dan sama proses sebelumnya anggota mencari buku ke sistem melalui proses mengelola pustaka dan meminjam buku melalui proses peminjaman dan memenuhi persyaratan peminjaman melalui proses mengelola anggota dan dikirimkan ke petugas perpustakaan ,setelah data anggota terisi petugas perpustakaan mengirimkan list pencarian petugas ke sistem dan anggota akan memilih petugas yang melayani pencatatan tgl peminjaman buku dan pengembalian buku di tahapan mengelola petugas akan di cek data anggota di storage anggota appakah sudah sesuai/belum setelah sudah sesuai maka dicek status login/logoutnya dan jika sudah makan semua persyaratan peminjaman/pencarian buku sudah terpenuhi dan data pustaka akan di kirim ke petugas perpustakaan dan kemudian dikirim ke sistem utama dan terakhir ke anggota.

# DFD-Level-2 :
[![Diagram-lv2-new.png](https://i.postimg.cc/kM0fBks5/Diagram-lv2-new.png)](https://postimg.cc/RqTcYpjr)

### Penjelasan DFD level 2
- pada tahap ini merupakan tahapan dimana ada sebuah proses besar (mengelola pustaka) dimana didalamnya terdapat proses yang lebih kecil yaitu proses memasukan pustaka,mengubah pustaka , menghapus pustaka dan melihat pustaka di proses mengelola pustaka terdapat inputan pustaka tanpa pengarang, pengarang pustaka dan pustaka kemudian juga ada output pustaka tanpa pangarang ,pengarang pustaka dan pustaka. di dalam proses mengelola pustaka juga ada pengeceka status login. 

- di proses memasukan pustaka,mengubah pustaka dan menghapus pustaka yang mendapat akses hanyalah admin/petugas
perpustakaan sebelum mengubah,menghapus,memasukan,petugas perlu mengecek status login terlebih dahulu setelah di ubah atau di hapus data tersebut bisa dikembalikan ke sistem utama atau sistem lainnya

- di proses melihat pustaka itu bisa diakses oleh petugas maupun anggota dengan melewati pengecekan status login baru bisa melihat data pustaka ytanpa pengarang dan data pengarang pustaka.

# DFD-Level-2-Pustaka :
[![Diagram-lv-2-Mengelola-Pustaka-new.png](https://i.postimg.cc/L8mzY5zR/Diagram-lv-2-Mengelola-Pustaka-new.png)](https://postimg.cc/Ln0qGHC0)

### Penjelasan DFD level 2 Mengelola Pustaka
- pada tahapan ini terdapat 2 entitas yang dapat mengakses kedalam proses tsb yaitu petugas perpustakaan dan anggota

- pada tahapan memasukan,mengubah,menghapus pustaka hanya petugas yang memiliki akses tersebut tentunya setelah melewati pengecekan status login.
dan untuk melihat dan mencari pustaka kedua entitas tsb dapat mengaksesnya tentunya setelah melewati proses login dan verivikasi.


# DFD-Level-2-Mengelola-Anggota :
[![Diagram-lv2-Mengelola-Anggota-new.png](https://i.postimg.cc/bJ2V58gK/Diagram-lv2-Mengelola-Anggota-new.png)](https://postimg.cc/wygktCSV)

### Penjelasan DFD level 2 Mengelola Anggota 
- tahapan mengelola anggota seperti memasukan,mengubah,menghapus dan mencari anggota hanya petugas yang diberikan akses di tahap ini kita bisa mendapatkan beberapa informasi dari database anggota

- di tahap ini petugas bisa mencarikan data informasi anggota dengan melihat status anggota di sistem lalu petugas mencari pada laman anggota tanpa telepon jika data yang ingin dicari terdapat didalam pada sistem data anggota tanpa telepon.

# DFD-Level-2-Mengelola-Peminjaman :
[![Diagram-Mengelola-Peminjaman-new.png](https://i.postimg.cc/4yx7d400/Diagram-Mengelola-Peminjaman-new.png)](https://postimg.cc/R62Vpm41)

### Penjelasan DFD level 2 Mengelola Peminjaman
- di tahap mengelola peminjaman ini ada beberapa proses yaitu memasukan,mengubah,menghapus,melihat,mencari peminjaman di tahap ini petuga bisa memasukkan peminjaman baru setelah login. contohnya adalah petugas akan mencatat data peminjaman data yang baru dengan isi nama buku,jangka waktu peminjaman , nama anggota yang meminjam dan tanggal peminjaman.

- lalu di tahap selanjutnya petugas bisa mencari data pinjaman yang sudah selesai pada jangka waktu yang ditentukan dan menghapus riwayat peminjaman tersebut.

# DFD-Level-2-Mengelola-petugas :
[![Diagram-Mengelola-Petugas-new.png](https://i.postimg.cc/GtR0JHRM/Diagram-Mengelola-Petugas-new.png)](https://postimg.cc/YGdyt2hg)

### Penjelasan DFD level 2 Mengelola Petugas
- pada tahap mengelola petugas yang bisa mengakses data data petugas yaitu admin/petugas perpustakaan setelah prosedur peminjaman admin mengirimkan daftar nama petugas untuk melayani peminjaman, penginputan tgl dll 

- dan admin juga bisa menghapus petugas ,mengubah petugas dan juga mencari petugas tentunya hal diatas bisa dilakukan setelah melalui proses pengecekan status login.

# DFD-Kamus-Data :
[![Diagram-Kamus-Data-new.png](https://i.postimg.cc/nLpvJ200/Diagram-Kamus-Data-new.png)](https://postimg.cc/ZWs9P8kd)