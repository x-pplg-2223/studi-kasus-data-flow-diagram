# studi-kasus-data-flow-diagram
# nimas

# DFD-level-0
[![dfd-level0-Page-1.png](https://i.postimg.cc/XqcNfsQt/dfd-level0-Page-1.png)](https://postimg.cc/hQvqg1F0)
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
# DFD-level-1
[![dfd-level1.png](https://i.postimg.cc/FR25ZJ1L/dfd-level1.png)](https://postimg.cc/S27vQR6S)

# DFD-level-2
[![dfd-level2.png](https://i.postimg.cc/1XcCqgFP/dfd-level2.png)](https://postimg.cc/m1kyxgV6)
# DFD-level-2-mengelola pustaka
[![dfd-level2-mengelola-pustaka.png](https://i.postimg.cc/TYK5h8vN/dfd-level2-mengelola-pustaka.png)](https://postimg.cc/3dHxbcR2)
# DFD-level-2-mengelola anggota
[![dfd-level2-mengelola-anggota.png](https://i.postimg.cc/SRCs74Qm/dfd-level2-mengelola-anggota.png)](https://postimg.cc/7JPwwpTR)
# DFD-level-2-mengelola peminjaman
[![dfd-level2-peminjaman.png](https://i.postimg.cc/Z57TNnPr/dfd-level2-peminjaman.png)](https://postimg.cc/gxhFFYTJ)
# DFD-level-2-mengelola petugas
[![dfd-level2-meneglola-petugas.png](https://i.postimg.cc/nLb30Y1Z/dfd-level2-meneglola-petugas.png)](https://postimg.cc/68cVQZS1)
1. Status  login memasukan data ke proses memasukan petugas 
2. data petugas mengalirkan data petugas ke proses memasukan petugas
3. proses memasukan petugas mengalirkan data petugas kepada petugas

1. status login memasukan data ke proses mengubah petugas
2. data petugas mengalirkan data petugas ke proses mengubah petugas
3. proses mengubah petugas mengalirkan data petugas ke petugas

1. status login memasukan data ke proses menghapus petugas
2. data petugas mengalirkan data petugas ke peroses menghapus petugas
3. proses menghapus data petugas mengalirkan data ke petugas

1. status login memasukan data ke proses ke melihat petugas
2. proses data mengalirkan data petugas ke petugas
3. petugas mengalirkan data petugas ke mnelihat petugas

1. status login memasukan data ke proses mencari petugas
2. petugas mengalirkan data pencarian petugas ke mencari petugas
3. proses mengalirkan data petugas ke  penyimpanan data petugas
4. petugas mengalirkan data petugas ke   proses mencari petugas
# KAMUS DATA
[![KAMUSDATA.png](https://i.postimg.cc/1zvv0gJr/KAMUSDATA.png)](https://postimg.cc/gw6ym09x)