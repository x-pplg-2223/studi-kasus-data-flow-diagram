# studi-kasus-data-flow-diagram

## Diagram milik Arif Achmad Fauzy coy🗿

<br>

## DFD level 0
### Ini contoh level 0 :

!['DFD.Diagram'](https://g.top4top.io/p_2600t208c1.png)
<br>

Penjelasan pada DFD diatas bisa seperti ini
<br> 
 
* Bisa di lihat di atas gambar berikut di dfd level 0 mempunyai sebuah sistem yaitu sistem mengelola informasi manajemen perpustakaan di gambar tersebut ada dua entitas/aktor yang terlibat yaitu ada anggota perpustakaan dan petugas perpustakaan.

* Pada tahap awal pengunjung akan mencari sebuah buku kemudian diterima sistem dan dikirim ke petugas perpustakaan,karena pengunjung tersebut belum login(login tersebut berguna untuk mendapatkan privillage anggota perpustakaan), maka petugas akan mengirim pesan login ke pengunjung tersebut, saat sudah login kemudian pesan login tersebut terkirim ke petugas perpustakaan. Dan pengunjung kembali ke halaman awal untuk mencari buku.anggota mencari buku ke sistem (buku progarming),kemudian pencarian tersebut diterima oleh petugas dan petugas mengirimkan list buku tentang (Programing/Coding) dan anggota memilih buku yang di inginkan kemudian petugas mencari anggota yang menginginkan buku (Programing) pilihannya tersebut, lalu petugas mengirimkan data buku ke sistem dan sistem mengirimkan datanya ke anggota.

## DFD level 1
### Ini contoh level 1 :

!['DFD.Diagram'](https://a.top4top.io/p_26009aun31.png)
<br>

DFD diatas merupakan DFD dari level 0 jika di perjelas lebih rinci lagi, penjelasannya bisa seperti ini :
<br>

* Pada tahapan ini anggota perpustakaan mencari data pustaka ke sistem dan sistem akan meminta data ke petugas perpustakaan apakah sudah login atau belum dan bilamana anggota mencari buku tanpa pengarang maka petugas perpustakaan mengirim data pustaka ke dalam mengelola pustaka dan di proses mengelola pustaka akan mengirimkan buku tanpa pengarang ke dalam storage pustakan dan dikirimkan datanya ke sistem utama dan jika anggota mencari buku dengan pengarang maka petugas akan mengirim ke mengelola pustaka dan di proses lalu dicek ke storage pengarang pustaka dan langsung dikirimkan ke sistem utama.

* Di tahap selanjutnya ada mengelola peminjaman anggota akan meminjam sebuah pustaka ke sistem dan sistem meminta petugas perpustakaan untuk mengirimkan data yang ingin dipinjam ke proses mengelola peminjaman ,di proses mengelola peminjaman akan di cek status loginnya jika sudah login maka akan terjadi proses pengecekan peminjaman di storage peminjaman dan dikembalikan data peminjaman ke petugas dan mengirimkannya ke mengelola pustaka jika anggota meminjam buku dengan pengarang makan akan dikirim ke sistem utama lalu ke anggota.

* Selanjutnya ada tahap mencari anggota , sama seperti proses sebelumnya anggota akan mencari/meminjam sebuah buku ke sistem dan dikirim ke petugas perpustakaan melalui proses pencarian buku dan ke proses peminjaman sebelum proses peminjaman selesai dicek terelbih dahulu status loginnya jika sudah maka akan di cari anggota yang ingin melakukan peminjaman di proses mengelola anggota petugas akan mengecek data anggota dari storage telepon anggota dan akan diambil dan dikirimkan ke sistem utama agar syarat peminjaman terpenuhi dan sistem akan mengirimkan datanya ke anggota.

* Pada proses yang selanjutnya adalah proses mengelola petugas , dan sama proses sebelumnya anggota mencari buku ke sistem melalui proses mengelola pustaka dan meminjam buku melalui proses peminjaman dan memenuhi persyaratan peminjaman melalui proses mengelola anggota dan dikirimkan ke petugas perpustakaan ,setelah data anggota terisi petugas perpustakaan mengirimkan list pencarian petugas ke sistem dan anggota akan memilih petugas yang melayani pencatatan tgl peminjaman buku dan pengembalian buku di tahapan mengelola petugas akan di cek data anggota di storage anggota appakah sudah sesuai/belum setelah sudah sesuai maka dicek status login/logoutnya dan jika sudah makan semua persyaratan peminjaman/pencarian buku sudah terpenuhi dan data pustaka akan di kirim ke petugas perpustakaan dan kemudian dikirim ke sistem utama dan terakhir ke anggota.

<br>

## DFD level 2

#### Ini contoh ( Mengelola Pustaka 2.1 ) :

!['DFD.Diagram'](https://l.top4top.io/p_2601g1wox1.png)
<br>

Penjelasan pada DFD diatas bisa seperti ini :
<br>

* Tahapan ini adalah tahapan untuk previlege petugas, di tahap ini data yang akan masuk seperti buku pustaka tanpa pengarang dan buku terdapat pengarang pusta pada mengelola pustaka akan bisa diubah dengan previlege yang khusus petugas, seperti Memasukan pustaka, Mengubah pustaka, Menghapus pustaka dan terlebih melewati dengan pengecekan status login agar dapat melakukan hal tersebut. lalu data terakhir tersebut bisa dikembalikan ke sistem lainnya.

* Tahap ini bisa diakses oleh privilege yang dimiliki anggota yaitu dengan melihat pustaka dengan melewati fase status login dan pustaka tanpa pengarang dan pengarang pustaka pada laman melihat pustaka.

#### Ini contoh ( Mengelola Pustaka 2.2 ) :

!['DFD.Diagram'](https://l.top4top.io/p_2601esh4o1.png)
<br>

Penjelasan DFD diatas bisa seperti ini :
<br>

* Pada tahapan ini terdapat 2 previlege yaitu anggota dan previlege khusus petugas.

* Tahapan yang ada pada previlege anggota adalah melihat pustaka, dan mencari pustaka. Dengan tahapan awal adalah sistem membaca dengan data pada status login yang ada yang lalu dengan mencari buku dengan tanpa pengarang atau dengan pengarang yang kemudian setelah data tersebut diambil data semua tersebut kembali ke sistem awal.

* Tahapan yang ada pada previlege petugas adalah memasukan pustaka, mengubah, menghapus, melihat, dan mencari pustaka.

#### Ini contoh ( Mengelola Anggota 2.3 ) :

!['DFD.Diagram'](https://k.top4top.io/p_2601w1cvk1.png)
<br>

Penjelasan DFD diatas bisa seperti ini :
<br>

* Tahapan mengelola anggota adalah tahapan yang dimana terdapat previlege tertentu yang akan bisa mengakses beberada informasi dan data, seperti memasukan anggota, mengubah anggota, menghapus anggota, melihat anggota, dan mencari anggota.

* Di tahap ini petugas bisa mencarikan data informasi anggota dengan melihat status anggota di sistem lalu petugas mencari pada laman anggota tanpa telepon jika data yang ingin dicari terdapat didalam pada sistem data anggota tanpa telepon.

#### Ini contoh ( Mengelola Peminjaman 2.4 ) :

!['DFD.Diagram'](https://k.top4top.io/p_26016zyvp1.png)
<br>

Penjelasan DFD diatas bisa seperti ini :
<br>

* Di tahap mengelola peminjaman ini ada beberapa proses yaitu memasukan,mengubah,menghapus,melihat,mencari peminjaman di tahap ini petuga bisa memasukkan peminjaman baru setelah login. Contohnya adalah petugas akan mencatat data peminjaman data yang baru dengan isi nama buku,jangka waktu peminjaman , nama anggota yang meminjam dan tanggal peminjaman.

* Lalu di tahap selanjutnya petugas bisa mencari data pinjaman yang sudah selesai pada jangka waktu yang ditentukan dan menghapus riwayat peminjaman tersebut.

#### Ini contoh ( Mengelola Petugas 2.5 ) :

!['DFD.Diagram'](https://d.top4top.io/p_260115jfz1.png)
<br>

Penjelasan DFD diatas bisa seperti ini :

* Pada tahap mengelola petugas yang bisa mengakses data data petugas yaitu admin/petugas perpustakaan setelah prosedur peminjaman admin mengirimkan daftar nama petugas untuk melayani peminjaman, penginputan tanggal dll.

* Dan admin juga bisa menghapus petugas, mengubah petugas dan juga mencari petugas tentunya hal diatas bisa dilakukan setelah melalui proses pengecekan status login.
 
## Kamus data

!['DFD.Diagram'](https://f.top4top.io/p_2601b1vtl1.png)
