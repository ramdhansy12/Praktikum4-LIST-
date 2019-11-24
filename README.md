### Latihan LIST
• Buat sebuah list sebanyak 5 elemen dengan nilai bebas

• Akses list:
- tampilkan elemen ke 3
- ambil nilai elemen ke 2 sampai elemen ke 4
- ambil elemen terakhir

• Ubah elemen list:
 
- ubah elemen ke 4 dengan nilai lainnya
- ubah elemen ke 4 sampai dengan elemen terakhir

• Tambah elemen list:

- ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
-  tambah list B dengan nilai string
- tambah list B dengan 3 nilai
- gabungkan list B dengan list A

#### Programnya
![gambar](https://user-images.githubusercontent.com/56957725/69396349-86c84400-0d14-11ea-9be0-ee1d90f15dab.png)


#### Hasil Programnya
![gambar](https://user-images.githubusercontent.com/56957725/69396413-bd9e5a00-0d14-11ea-94c0-c29386885301.png)

--------------------------------------------------------------------------------------------------------------------------------
####  Tugas Praktikum

Buat program sederhana untuk menambahkan data kedalam sebuah
list dengan rincian sebagai berikut:

- Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)

- Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban t (Tidak), maka program akan   menampilkan daftar datanya.

- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)

- Buat flowchart dan penjelasan programnya pada README.md.

- Commit dan push repository ke github.


#### Programnya
![gambar](https://user-images.githubusercontent.com/56957725/69493246-07d33700-0edf-11ea-805f-8552021025cc.png)


#### Hasil Programnya
![gambar](https://user-images.githubusercontent.com/56957725/69493278-92b43180-0edf-11ea-8757-b079b8f96079.png)


#### Flowchart
![gambar](https://user-images.githubusercontent.com/56957725/69493009-0fdda780-0edc-11ea-96fa-87b5f98db9ac.png)


#### Penjelasan program
1. Buatlah list berupa Nama, Nim, Nilai tugas, Nilai UTS, Nilai UAS
2. Lalu inputlah Nama, Nim, Nilai tugas, Nilai UTS, Nilai UAS
3. Jika ingin menambah list data ketik "ya" dan jikalau tidak ingin menambahkan list data ketik "tidak". Dengan perintah while jawab =="ya" dan if  jawab =="tidak". Jawab input(("Tambah data y/t")).
4,Gunakan perintah append pada Nama, Nim, Nilai tugas, Nilai UTS, Nilai UAS untuk menambahkan 1 item ke elemen terakhir.
5. Lalu mencari nilai akhir dengan perhitungan nilai tugas 30%, nilai uts 35% dan uas 35% , dengan perintah float
6. Gunakanlah perulangan for, dengan perintah for i in range(len(Nama)):. Fungsi "len" ialah untuk mengembalikan panjang (jumlah anggota) dari suatu objek.
7. Lalu cetak  dengan perintah print(i+1,Nama[i],Nim[i],TGS[i],UTS[i],UAS[i],Nilaiakhir[i] )\
8. Selesai

