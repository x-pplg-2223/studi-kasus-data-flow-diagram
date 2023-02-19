# studi-kasus-data-flow-diagram
# amel

# DFD-level-0
[![DFD-Level-0.jpg](https://i.postimg.cc/Dzs8HZVH/DFD-Level-0.jpg)](https://postimg.cc/v1YY6GZt)
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
17. Dan petugas memberikan data kepada anggota
# level 1
[![level1-early.jpg](https://i.postimg.cc/pdDb940P/level1-early.jpg)](https://postimg.cc/d7tSpHPf)

Anggota/pengunjung perpustakaan melakukan pencarian terhadap daftar pustaka
2. sistem mencari pustaka menerima data tersebut dan memberikan daftar pustaka kepada pengunjung/anggota
3. mencari pustaka menerima data pengunjung/anggota yang mencari pustaka, kemudian mengirimkan data pustaka kepada petugas 
4. petugas perpustakaan mendapatkan data pustaka, dan memberikan pencarian daftar pustaka kepada mencari pustaka 
5. mengelola pustaka memberikan pustaka tanpa pengarang kepada pustaka
6. pustaka memberikan data pustaka tanpa pengarang kepada mencari pustaka 
7. sistem informasi harus memeriksa terlebih dahulu memeriksa situs login dari mengelola pustaka, untuk dapat mengubah data dari mengelola pustaka
8. jika sudah login, pustaka dapat memberikan beberapa data pustaka tanpa pengarang kepada mengelola pustaka
9. mengelola pustaka memberi data tersebut kepada pengarang
10. pengarang memberika data pengarang pustaka kepada mengelola pustaka
11. mengelola pustaka memberikan data pustaka kepada petugas
12. petugas menerima data pustaka tersebut dan memproses kepada mencari pustaka lewat pencarian pustaka 
13. pengarang memasukkan pengarang pustaka kepada mencari pustaka
14. mencari pustaka memproses data keduanya untuk di berikan kepada anggota/pengunjung
15. petugas perpustakaan memberikan data pencarian peminjaman kepada mengelola peminjaman 
16. petugas perpustakaan memberikan data peminjaman yang di pinjam oleh anggota/pengunjung 
17. sistem informasi harus terlebih dahulu memeriksa status login untuk dapat menjangkau mengelola peminjaman untuk di lakukan peminjaman 
18. jika sudah status login, mengelola peminjaman menerima dan memberikan data kepada sistem peminjaman
19. sistem peminjaman menerima data dan memberikan kembali kepada mengelola peminjaman, tanda peminjaman di perbolehkan
20. kemudian memberikan data peminjaman kepada petugas untuk di berikan kepada mencari pustaka kemudian anggota/pengunjung
21. petugas melakukan pencarian terhadap data anggota
22. petugas kemudian memberikan data anggota yang di cari
23. sistem informasi mengecek status login terlebih dahulu untuk dapat menjangkau sistem mengelola petugas
24. jika sudah berstatus login, maka sistem mengelola anggota akan memberikan data anggota tanpa telepon kepada anggota
25. anggota menerima data dan memberikan data anggota tanpa telepon kepada sistem mengelola anggota
26. mengelola anggota memberikan data telpon anggota kepada telpon
27. telpon menerima data dan memberikan data telpon anggota ke mengelola anggota 
28. mengelola anggota menerima data telpon anggota dan memberikan data kepada petugas
29. petugas melalukan pencarian data petugas lainnya kepada mengelola tugas
30. petugas memberika data anggota yang di cari
31. sistem memeriksa status login dari petugas perpustakaan 
32. jika sudah berstatus login, mengelola petugas akan mencari data petugas kepada petugas
33. petugas memberikan data petugas yang di cari
34. kemudian mengelola petugas menerima data dan memberikannya kepada petugas perpustakaan 
35. petugas perpustakaan melakukan login 
36. sistem login menerima data login petugas perpustakaan
37. sistem petugas menerima login petugas perpustakaan
38. sistem login kemudian memberikan pesan login/logout kepada petugas perpustakaan
39. jika login terdapat, berarti petugas bisa menjalankan tugasnya
40. jika logout maka petugas harus login kembali.postimg.cc/VNyNq8SR/level1-early.jpg)](https://postimg.cc/cvmZWPBg)
 
# dfd level 2
[![Whats-App-Image-2023-02-14-at-10-37-12.jpg](https://i.postimg.cc/qMGnpvcL/Whats-App-Image-2023-02-14-at-10-37-12.jpg)](https://postimg.cc/crr6mZbg)

MENGELOLA PUSTAKA
1. pustaka tanpa pengarang mengalirkan data ke mengelola pustaka
2. mengelola pustaka mengalirkan data pengarang pustaka kepada penyimpanan data pengarang
3. pengarang pustaka mengalirkan data ke mengelola pustaka 
3. status login mengngalirkan data ke mengelola pustaka
4. menglolakan pustaka mengalirkan data pustaka tanpa pengarang kepada penyimpanan data pengarang
5. petugas mengalirkan data pustaka kepada mengelola pustaka
6. proses pemeriksaan status login mengalirkan data ststus login kepada mengelola pustaka

PROSES MENGELOLA PUSTAKA
Mengelola Pustaka mengenai tentang memasukan Pustaka,mengubah Pustaka ,menghapus Pustaka, dan melihat Pustaka
1. status login memasukkan data ke pustaka,selanjutnya mengalirkan data pustaka tanpa pengarang ke petugas
2. pustaka mengalirkan data ke proses memasukan pustaka, selanjutnya mengalirkan data pengarang pustaka ke petugas
3. status login mengalirkan data ke mengubah pustaka, selanjutnya mengalirkan data pustaka tanpa pengarang ke petugas
4. pustaka mengalirkan data ke proses mengubah pustaka, selanjutnya mengalirkan data pengarang pustaka ke petugas
5. status login mengalirkan data ke proses menghapus pustaka, selanjutnya mengalirkan data pustaka tanpa pengarang ke petugas
6. pustaka mengalirkan data ke proses menghapus pustaka, selanjutnya mengalirkan data pengarang pustaka ke petugas
7. status login mengalirkan data ke proses melihat pustaka,selanjutnya petugas mengalirkan data pustaka tanpa pengarangke proses melihat pustaka
8. proses melihat anggota mengalirkan data pustaka ke petugas, selanjutnya data penyimpananpetugas mengalirkan data pustaka pengarang ke proses melihat pustaka
# level 2 mengelola pustaka
[![level-2-mengelola-pustaka.jpg](https://i.postimg.cc/85QT6B0n/level-2-mengelola-pustaka.jpg)](https://postimg.cc/hJsFFxg9)
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
# level 2 mengelola anggota
[![level-2-mengelola-anggota.jpg](https://i.postimg.cc/VLLmnNK1/level-2-mengelola-anggota.jpg)](https://postimg.cc/YjV5wtcy)
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
# level 2 mengelola peminjaman
[![level-2-mengelola-peminjaman.jpg](https://i.postimg.cc/yx8tgDsb/level-2-mengelola-peminjaman.jpg)](https://postimg.cc/JDSPS4yN)
1. status login memasukan data ke proses memasukkan peminjaman
2. data peminjaman mengalirkan data peminjaman ke proses memasukkan peminjaman
3. proses memasukkan peminjaman mengalirkan data peminjaman kepada petugas
4. status login memasukkan data ke proses mengubah peminjaman
5. data peminjaman mengalirkan data peminjaman ke proses mengubah peminjaman
6. proses mengubah peminjaman mengalirkan data peminjaman kepada petugas
7. status login memasukkan data ke proses menghapus peminjaman
8. data peminjaman mengalirkan data peminjaman ke proses menghapus pemijaman
9. proses menghapus peminjaman mengalirkan data peminjaman kepada petugas
10. status login memasukkan data ke proses melihat peminjaman
11. proses mengalirkan data peminjaman ke penyimpanan data peminjaman
12. petugas mengalirkan data peminjaman ke proses melihat peminjaman
13. status login memasukkan data ke proses mencari peminjaman
14. peminjaman mengalirkan data pencarian peminjaman ke mencari peminjaman
15. proses mengalirkan data peminjaman ke penyimpanan data peminjaman
16. petugas mengalirkan data peminjaman ke proses mencari peminjaman
# level mengelola petugas
[![DFD-Level-2-5.jpg](https://i.postimg.cc/02MMDZW9/DFD-Level-2-5.jpg)](https://postimg.cc/zVNG1wYQ)

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
[![kamus-data.jpg](https://i.postimg.cc/3xjwFqgQ/kamus-data.jpg)](https://postimg.cc/hXjgSpy2)
Kamus data adalah suatu daftar elemen yang tergonarisir dengan definisi yang tetap dan sesuai dengan sistem dengan user dan analisis sistem yang mempunyai pengertian yang sama tentang input, output, dan komponen.

1. Nama aliran data login pustaka, peminjaman, anggota, petugas Dimana di gunakan proses login (input) Deskripsi data ini merupakan login id password/id "string"Lalu mengakses password 
2. Dimana proses memeriksa status login maka keluaran (output)

Lalu mengelola pustaka (masukan input/output) dan proses mengelola anggota, peminjaman, dan petugas masukan (input) Deskripsi bahwa status login telah sukses sehingga status login menjadi "BOOLEAN"