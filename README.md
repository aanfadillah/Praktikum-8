# Nama: Aan Fadillah Putra
# NIM: 312210327
# Kelas: TI.22.A3

## PERTEMUAN 12
## SOAL

![soal](https://user-images.githubusercontent.com/115542704/206460646-4c089e2d-9d9c-427b-a326-d43c633e78d6.png)

## Diagram class

![diagramClass](https://user-images.githubusercontent.com/115542704/206462308-ab57022f-da40-422a-9e52-1c59252d2123.png)



## Program

pertama buatlah dictionary terlebih dahulu untuk menampung data
```python
mahasiswa = {}
```

kemudian buatlah sebuah class daftar nilai
```python
class daftarNilai()
```

Lalu lanjutkan dengan membuat method method fungsinya sebagai berikut
```
def tambah(self)
def ubah(self)
def lihat(self)
def hapus(self)
def keluar(self)
```

lalu isi setiap method dengan elemen-elemennya
```python
nama= input("masukan nama: ")
nim= input("masukan nim :")                                         
nilaiTugas= int(input("Masukkan Nilai Tugas: "))
nilaiUts= int(input("Masukkan Nilai UTS\t: "))            
nilaiUas= int(input("Masukkan Nilai UAS\t: "))             
nilaiAkhir= (30/100 * nilaiTugas) + (35/100 * nilaiUts) + (35/100 * nilaiUas)
mahasiswa[nama]=nim,nilaiTugas,nilaiUts,nilaiUas,nilaiAkhir
```

lalu saya membuat sebuah looping
```python
while True:
    data = daftarNilai()
    print('\ntambah\t(1)\nubah\t(2)\nlihat\t(3)\nhapus\t(4)\nkeluar\t(5)')
    c = input("\nsilahkan masukan pilihan : ")
    print()
```

Kemudian membuat fungsi if else untuk menjalankan method
```python
if (c == "1"):
    data.tambah()
elif (c == "2"):
    data.ubah()
elif (c == "3"):
    data.lihat()
elif (c == "4"):
    data.hapus()
elif (c == "5"):
    data.keluar()
    break    
```

Dan terakhir saya juga menggunakan else di akhir program yang digunakan apabila salah memasukkan pilihan inputan
Berikut programnya:
```python
else:
    print()
    print("Kode yang anda masukkan salah!")
```

# output program

ini adalah output apabila memilih tambah (1)

![IMG-20221209-WA0015](https://user-images.githubusercontent.com/115763475/206890436-535ba9dd-14ef-4e4f-93d6-dcfa506ed108.jpg)


ini adalah output apabila memilih untuk tambah lagi

![IMG-20221209-WA0014](https://user-images.githubusercontent.com/115763475/206890528-1cc05cbf-5dce-432f-9934-de36dd6746f7.jpg)


ini adalah output apabila memilih ubah (2)

![IMG-20221209-WA0013](https://user-images.githubusercontent.com/115763475/206898032-04e713c0-c007-4ba1-9762-0f46c8156ee0.jpg)

berikut data yang sudah diubah

![IMG-20221209-WA0012](https://user-images.githubusercontent.com/115763475/206898115-b922645f-3c38-4f6d-a88d-7647737eda2d.jpg)

ini adalah output apabila memilih lihat (3)

![IMG-20221209-WA0012](https://user-images.githubusercontent.com/115763475/206898600-1a0599f7-16c9-40dd-8a14-65debbaa598b.jpg)

ini adalah output apabila memilih hapus (4)

![IMG-20221209-WA0009](https://user-images.githubusercontent.com/115763475/206898686-9f3d773b-8e86-44f9-8296-4766f34ed8f8.jpg)


berikut tampilan data yang telah terhapus

![IMG-20221209-WA0011](https://user-images.githubusercontent.com/115763475/206898731-39d40408-cccc-4aaa-8af3-bc06764b9948.jpg)


ini adalah output apabila memilih keluar (5)

![IMG-20221209-WA0010](https://user-images.githubusercontent.com/115763475/206898792-9167d4c9-ef50-48eb-808a-d5979b83a256.jpg)

## Flowchart

![flowchart (3)](https://user-images.githubusercontent.com/115542704/206462353-41fd2d95-2329-4f92-9403-e679c5bc1784.png)


# SEKIAN TERIMAKASIH
