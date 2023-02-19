# studi-kasus-data-flow-diagram
# nadia rizky alifah

# DFD-Level-0
[![Ripa-2.jpg](https://i.postimg.cc/GpS62ZTP/Ripa-2.jpg)](https://postimg.cc/R3KgppRq)
1. Mengelola sistem informasi manajemen perpustakaan mengalirkan data anggota/pengunjung perpustakaan (ketika ada yg meminjam buku)
2. lalu anggota melakukan pencarian pustaka kepada mengelola sistem
3. terus petugas pustaka itu melakukan login ke mengelola sisitem pustaka
4. setalah itu anggota  mendapatkan pesan login/logut dari pustaka
5. Petugas pustaka melakukan pencarian pustaka kepada mengelola sistem
6. Mengelola sistem mengirim data kembali kepada petugas 
7. Petugas juga langsung mengirim kembali kepada mengelola sistem untuk di periksa
8. Mengelola sistem mencari anggota yg meminjam buku
9. Mengelola sistem itu mengirimkan data anggota kepada si petugas untuk di periksa,setelah di periksa
10. petugas juga langsung mengirimkan data anggota lagi untuk di menerima data tersebut     (setelah di terima data)
11. Lalu melakukan peminjaman kepada mengelola sistem
12. Petugas melakukan pencarian peminjam kepada mengelola sistem
13. Petugas melakukan peminjaman
14. Mengelola sistem mengirimkan data peminjama kpd petugas 
15. prtugas mengirimkan data kepada mengelola sistem
16. Mengelola sistem mengirimkan data HASIL PENCARIAN kepada petugas
17. Dan petukan memberikan data kepada anggota

# DFD-Level-1
[![Whats-App-Image-2023-02-13-at-20-26-48.jpg](https://i.postimg.cc/ZqW9nxL8/Whats-App-Image-2023-02-13-at-20-26-48.jpg)](https://postimg.cc/WDPpfrCz)
-anggota/pengunjung perpustakaan melakukan pencarian terhadap daftar pustaka
-sistem mencari pustaka menerima data tersebut dan memberikan daftar pustaka kepada pengunjung/anggota
-mencari pustaka menerima data pengunjung/anggota yang mencari pustaka, kemudian mengirimkan data pustaka kepada petugas 
-petugas perpustakaan mendapatkan data pustaka, dan memberikan pencarian daftar pustaka kepada mencari pustaka 
-mengelola pustaka memberikan pustaka tanpa pengarang kepada pustaka
- pustaka memberikan data pustaka tanpa pengarang kepada mencari pustaka 
- sistem informasi harus memeriksa terlebih dahulu memeriksa situs login dari mengelola pustaka, untuk dapat mengubah data dari mengelola pustaka
- jika sudah login, pustaka dapat memberikan beberapa data pustaka tanpa pengarang kepada mengelola pustaka
- mengelola pustaka memberi data tersebut kepada pengarang
- pengarang memberika data pengarang pustaka kepada mengelola pustaka
- mengelola pustaka memberikan data pustaka kepada petugas
- petugas menerima data pustaka tersebut dan memproses kepada mencari pustaka lewat pencarian pustaka 
- pengarang memasukkan pengarang pustaka kepada mencari pustaka
- mencari pustaka memproses data keduanya untuk di berikan kepada anggota/pengunjung
- petugas perpustakaan memberikan data pencarian peminjaman kepada mengelola peminjaman 
- petugas perpustakaan memberikan data peminjaman yang di pinjam oleh anggota/pengunjung 
- sistem informasi harus terlebih dahulu memeriksa status login untuk dapat menjangkau mengelola peminjaman untuk di lakukan peminjaman 
- jika sudah status login, mengelola peminjaman menerima dan memberikan data kepada sistem peminjaman
- sistem peminjaman menerima data dan memberikan kembali kepada mengelola peminjaman, tanda peminjaman di perbolehkan
- kemudian memberikan data peminjaman kepada petugas untuk di berikan kepada mencari pustaka kemudian anggota/pengunjung
- petugas melakukan pencarian terhadap data anggota
- petugas kemudian memberikan data anggota yang di cari
- sistem informasi mengecek status login terlebih dahulu untuk dapat menjangkau sistem mengelola petugas
- jika sudah berstatus login, maka sistem mengelola anggota akan memberikan data anggota tanpa telepon kepada anggota
- anggota menerima data dan memberikan data anggota tanpa telepon kepada sistem mengelola anggota
- sistem kemudian memberikan data anggota kepada petugas
# DFD-Level-2
[![Untitled-2.jpg](https://i.postimg.cc/Gthmt9Hy/Untitled-2.jpg)](https://postimg.cc/sQqr0jPj)
1. Status login memasukan data ke proses memasukan pustaka
2. Petugas mengalirkan data pustaka kepada proses memasukan  pustaka 
3. Proses memasukan pustaka mengalirkan data  pustaka tanpa pengarang kepada petugas
4. Proses memasukan pustaka mengalirkan data pengarang pustaka kepada petugas
5. Status login memasukan data ke proses mengubah pustaka
6. Petugas mengalirkan data pustaka kepada proses mengubah pustaka
7. Proses memasukan pustaka mengalirkan data  pustaka tanpa pengarang kepada petugas
8. Proses memasukan pustaka mengalirkan data pengarang pustaka kepada petugas
9. Status login mengalirkan data ke menghapus pustaka
10. Petugas mengalirkan data pustaka kepada proses menghapus pustaka
11. Proses memasukan pustaka  mengalirkan data tanpa pengarang kepada petugas
12. Proses memasukan pustaka mengalirkan data pengarang pustaka kepada petugas
13. Status login mengalirkan data ke proses melihat pustaka
14. Proses mengalirkan pustaka mengalirkan data   pustaka 
15. Petugas mengalirkan data petugas tanpa pengarang ke proses melihat pustaka
16. Petugas mengalirkan data pengarang pustaka kepada proses  melihat pustaka
# DFD-Level-2-Mengelola-Pustaka
[![Whats-App-Image-2023-02-13-at-21-25-22.jpg](https://i.postimg.cc/kMTsD8LT/Whats-App-Image-2023-02-13-at-21-25-22.jpg)](https://postimg.cc/9zqZn4m9)
*MENGELOLA PUSTAKA*
1. pustaka tanpa pengarang mengalirkan data ke mengelola pustaka
2. mengelola pustaka mengalirkan data pengarang pustaka kepada penyimpanan data pengarang
3. pengarang pustaka mengalirkan data ke mengelola pustaka 
3. status login mengngalirkan data ke mengelola pustaka
4. menglolakan pustaka mengalirkan data pustaka tanpa pengarang kepada penyimpanan data pengarang
5. petugas mengalirkan data pustaka kepada mengelola pustaka
6. proses pemeriksaan status login mengalirkan data ststus login kepada mengelola pustaka
*PROSES MENGELOLA PUSTAKA*
1. status login memasukkan data ke pustaka,selanjutnya mengalirkan data pustaka tanpa pengarang ke petugas
2. pustaka mengalirkan data ke proses memasukan pustaka, selanjutnya mengalirkan data pengarang pustaka ke petugas
3. status login mengalirkan data ke mengubah pustaka, selanjutnya mengalirkan data pustaka tanpa pengarang ke petugas
4. pustaka mengalirkan data ke proses mengubah pustaka, selanjutnya mengalirkan data pengarang pustaka ke petugas
5. status login mengalirkan data ke proses menghapus pustaka, selanjutnya mengalirkan data pustaka tanpa pengarang ke petugas
6. pustaka mengalirkan data ke proses menghapus pustaka, selanjutnya mengalirkan data pengarang pustaka ke petugas
7. status login mengalirkan data ke proses melihat pustaka,selanjutnya petugas mengalirkan data pustaka tanpa pengarangke proses melihat pustaka
8. proses melihat anggota mengalirkan data pustaka ke petugas, selanjutnya data penyimpananpetugas mengalirkan data pustaka pengarang ke proses melihat pustaka
# DFD-Level-2-Mengelola-Anggota
[![Whats-App-Image-2023-02-13-at-22-35-27-2.jpg](https://i.postimg.cc/wByYhqp4/Whats-App-Image-2023-02-13-at-22-35-27-2.jpg)](https://postimg.cc/2qDtYf3n)
1. status login memasukkan data ke proses anggota,selanjutnya mengalirkan data anggota tanpa telepon ke petugas

2. anggota mengalirkan data ke proses memasukkan anggota,selanjutnya mengalirkan data telepon anggota kepetugas 

3. status login mengalirkan data ke proses mengubah anggota,selanjutnya mengalirkan data anggota tanpa telepon kepetugas

4. anggota mengalirkan data ke proses mengubah anggota,selanjutnya mengalirkan data telepon anggota ke petugas

5. status login mengalirkan data ke proses menghapus anggota,selanjutnya mengalirkan data anggota  tanpa telepon ke prtugas 

6. anggota mengalirkan data ke proses menghapus anggota,selanjutnya mengalirkan data telepon anggota ke petugas

7. status login mengalirkan  data ke proses melihat anggota,selanjutnya petugas mengalirkan data anggota tanpa telepon ke proses melihat anggota

8. proses melihat anggota mengalirkan data anggota ke petugas,selanjutnya data penyimpanan petugas mengalirkan data telepon anggota ke proses anggota

9. status login mengalirkan data ke proses mencari anggota,selanjutnya petugas mengalirkan data anggota tanpa telepon ke proses mencari anggota

10. pencarian anggota mengalirkan data ke proses mencari anggota

11. proses mencari anggota mengalirkan data anggota ke petugas,selanjutnya data penyimpan petugas mengalirkan data telepon anggota ke proses mencari anggota
# DFD-Level-2-Mengelola-Petugas
[![Whats-App-Image-2023-02-14-at-10-07-28.jpg](https://i.postimg.cc/tRc8pQG9/Whats-App-Image-2023-02-14-at-10-07-28.jpg)](https://postimg.cc/6TdMfPQP)
1. Status  login memasukan data ke proses memasukan petugas 
2. data petugas mengalirkan data petugas ke proses memasukan petugas
3. proses memasukan petugas mengalirkan data petugas kepada petugas
4. status login memasukan data ke proses mengubah petugas
5. data petugas mengalirkan data petugas ke proses mengubah petugas
6. proses mengubah petugas mengalirkan data petugas ke petugas
7. status login memasukan data ke proses menghapus petugas
8. data petugas mengalirkan data petugas ke peroses menghapus petugas
9. proses menghapus data petugas mengalirkan data ke petugas	
10. status login memasukan data ke proses ke melihat petugas
11. proses data mengalirkan data petugas ke petugas
12. petugas mengalirkan data petugas ke mnelihat petugas
13. status login memasukan data ke proses mencari petugas
14. petugas mengalirkan data pencarian petugas ke mencari petugas
15. proses mengalirkan data petugas ke  penyimpanan data petugas
16. petugas mengalirkan data petugas ke   proses mencari petugas
# DFD-Level-2-Mengelola-Peminjaman
[![Whats-App-Image-2023-02-14-at-10-11-43.jpg](https://i.postimg.cc/PfFnJvYs/Whats-App-Image-2023-02-14-at-10-11-43.jpg)](https://postimg.cc/3WpcbRtn)
# DFD-Kamus-Data
[![Whats-App-Image-2023-02-14-at-10-02-42.jpg](https://i.postimg.cc/Gph19F7R/Whats-App-Image-2023-02-14-at-10-02-42.jpg)](https://postimg.cc/0z34Bw1X)
*Kamus data adalah suatu daftar elemen yang tergonarisir dengan definisi yang tetap dan sesuai dengan sistem dengan user dan analisis sistem yang mempunyai pengertian yang sama tentang input, output, dan komponen.*

1. Nama aliran data login pustaka, peminjaman, anggota, petugas Dimana di gunakan proses login (input) Deskripsi data ini merupakan login id password/id "string"Lalu mengakses password 
2. Dimana proses memeriksa status login maka keluaran (output) Lalu mengelola pustaka (masukan input/output) dan proses mengelola anggota, peminjaman, dan petugas masukan (input) Deskripsi bahwa status login telah sukses sehingga status login menjadi "BOOLEAN"
