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

Penjelasan dari DFD diatas bisa seperti ini :
<br>

* DFD di atas adalah penggambaran proses yang dilakukan oleh sistem untuk petugas dan anggota, proses didalamnya meliputi mengelola pustaka, mengelola peminjaman, melakukan mengelola anggota, petugas dan data, dan data login dan logout, melakukan pemeriksaaan status login

* Disini adalah tahapan anggota mencari pustaka dan peminjaman buku, ditahap pertama ini sistem mencari pustaka akan meminta data pustaka kepada petugas perpustakaan, dan ditahap ini petugas perpustakaan akan mengirimkan beberada data kepada mengelola pustaka, jika anggota mencari pustaka tanpa pengarang maka akan data tersebut akan dikirim kedalam storage pustaka, dan pustaka tanpa pengarang langsung kembali kesistem utama. dan jika anggota mencari pustaka berupa pengarang, makan sistem akan mengirimkan kepada storage pengarang dan pencarian baru akan dikirimkan ke sistem utama. tahap selanjutnya adalah petugas perpustakaan sistem mengirimkan data berupa login petugas yang kemudian memasukan data data petugas dan memeriksa status loginnya lalu tahap kemudian sistem memeriksa status login pada mengelola anggota yang akan meminjam buku pada perpustakaan dengan mengambil data anggota telepon di storage telepon dan lalu dikirimkan kembali ke mengelola petugas dan kemudian dikirimkan kepada sistem utama dan lalu terakhir kepada anggota.

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

#### Ini contoh ( Mengelola Petugas 2.5 ) :

!['DFD.Diagram'](https://d.top4top.io/p_260115jfz1.png)
 
## Kamus data

!['DFD.Diagram'](https://f.top4top.io/p_2601b1vtl1.png)
