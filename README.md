# Nama: Aan Fadillah Putra
# NIM: 312210327
# Kelas: TI.22.A3

## PERTEMUAN 12
## SOAL

![soal](https://user-images.githubusercontent.com/115542704/206460646-4c089e2d-9d9c-427b-a326-d43c633e78d6.png)

## Diagram class

![diagramClass](https://user-images.githubusercontent.com/115542704/206462308-ab57022f-da40-422a-9e52-1c59252d2123.png)

## Flowchart

![flowchart (3)](https://user-images.githubusercontent.com/115542704/206462353-41fd2d95-2329-4f92-9403-e679c5bc1784.png)

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

<img width="422" alt="r3" src="https://user-images.githubusercontent.com/115542704/206634080-2e46eb8d-81f9-4799-9c38-eb5d04703c08.png">

ini adalah output apabila memilih hapus (4)

<img width="201" alt="r4" src="https://user-images.githubusercontent.com/115542704/206633372-daefd529-009d-46e8-be7a-b5d06687388a.png">

berikut tampilan data yang telah terhapus

<img width="418" alt="r4 1" src="https://user-images.githubusercontent.com/115542704/206633747-6f3e7e1a-97ec-4768-9418-f9c78b2e64c7.png">

ini adalah output apabila memilih keluar (5)

<img width="233" alt="r5" src="https://user-images.githubusercontent.com/115542704/206634711-7843405a-c2a7-4a80-8428-b9cb22c58324.png">

# SEKIAN TERIMAKASIH
