# PRAKTIKUM 3

- Dokumen terdapat di file di atas

# Daftar tugas yang di minta

- Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen. 
- Hapus satu record dat pada tabel dosen yang telah dirjuk pada tabel mahasiswa. 
- Ubah mode menjadi on update cascade on delete rescrict.
- Lakukan perubahan data pada tabel dosen (kd_ds).
- Lakukan penghapusan data pada tabel dosen. 
-  Ubah mode menjadi on update cascade on delete delete set null 
-  Lakukan penghapusan data pada tabel dosen.




# Berikut langkah langkah pembuatan yang di minta

- Langkah pertama adalah melakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen 

![gambar1](gambar/ini1.png)


- Ini merupakan gambaran secara keseluran

![gambar1](gambar/ini2.png)

- Langkah kedua yaitu menghapus satu record data pada tabel dosen yang telah di rujuk pada tabel mahasiswa

![gambar1](gambar/ini3.png)

- Langkah ketiga yaitu mengubah mode menjadi  on update cascade on delete rescrict
![gambar1](gambar/ini4.png)

- Langkah ke empat Lakukan perubahan data pada tabel dosen (kd_ds)

![gambar1](gambar/ini5.png)

- Langkah ke lima yaitu Lakukan penghapusan data pada tabel dosen

![gambar1](gambar/ini6.png)

- Langkah ke enam Ubah mode menjadi on update cascade on delete delete set null 

![gambar1](gambar/ini7.png)

- Langkah ke tujuh Lakukan penghapusan data pada tabel dosen

![gambar1](gambar/ini8.png)



# PERBEDAAN RESCRICT DAN CASCADE

RESCRICT adalah jika kita menghapus atau merubah baris data dalam tabel A maka tidak akan diperbolehkan jika pada tabel B masih ditemukan relasi datanya. InnoDB dapat menolak perintah perubahan atau penghapusan tersebut.

CASCADE adalah jika kita menghapus atau merubah baris data dalam tabel A secara otomatis akan menghapus atau merubah baris yang sesuai dalam tabel B.

# KESIMPULAN 

RESCRICT Merupakan perintah untuk menghapus dan juga merubah baris data di dalam tabel secara manual 

CASCADE merupakan perintah menghapus dan merubah baris data dengan menggunakan cara otomatis pada tabel yang ada
