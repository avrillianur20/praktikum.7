# praktikum.7
## Nama : Avrillia Nur Hidayah
## NIM : 312210309
## Kelas : TI.22.A3

## Soal!!
## Latihan
![WhatsApp Image 2022-12-02 at 11 54 09](https://user-images.githubusercontent.com/115686359/205217811-96b2de7b-4ea3-4c5c-b883-794f99e35489.jpeg)

```
import math
def a(x):
  return x**2
a = lambda x : x**2
print(a(2))
def b(x, y):
  return math.sqrt(x*2 + y*2)
b = lambda x, y : x * 2 + y * 2
print(b(2, 2))
def c(*args):
  return sum(args)/len(args)
c = lambda *args : sum(args)/len(args)
print(c(1,2,3,4,5))
def d(s):
  return "".join(set(s))
d = lambda s: "".join(set(s))
print(d("buku"))
```

### Outputnya adalah
![Screenshot (644)](https://user-images.githubusercontent.com/115686359/205218558-8413844d-8ca3-4e32-9088-cd3207d68be9.png)


## Praktikum
![WhatsApp Image 2022-12-02 at 09 09 47](https://user-images.githubusercontent.com/115686359/205219066-f4794d78-595f-4f8c-b132-2decc63eb3a7.jpeg)

### 1. (T)ambah data
```
def tambah():
    print("Tambah Data")
    nama = input("Masukkan Nama Mahasiswa   : ")
    nim = input("Masukkan NIM              : ")
    tugas = int(input("Masukkan Nilai Tugas      : "))
    uts = int(input("Masukkan Nilai UTS        : "))
    uas = int(input("Masukkan Nilai UAS        : "))
    akhir = tugas * 30/100 + uts * 35/100 + uas * 35/100
    mahasiswa[nama] = nim , tugas, uts , uas , akhir
def tampilkan():
```

### Outputnya adalah

![Screenshot (645)](https://user-images.githubusercontent.com/115686359/205284123-697c6d02-5225-439f-94ce-215c7d5fcbb8.png)

Kemudian (L)ihat data

![Screenshot (646)](https://user-images.githubusercontent.com/115686359/205284314-bbcf4383-60f0-472a-9d57-352265246c9c.png)

### 2. (U)bah data
```
def ubah():
    print ( "Ubah Data" )
    nama = input("Masukkan Nama Mahasiswa   : ")
    if nama in  mahasiswa . keys ():
        nim = input("Masukkan NIM              : ")
        tugas = int(input("Masukkan Nilai Tugas      : "))
        uts = int(input("Masukkan Nilai UTS        : "))
        uas = int(input("Masukkan Nilai UAS        : "))
        akhir = tugas * 30/100 + uts * 35/100 + uas * 35/100
        mahasiswa[nama] = nim , tugas, uts , uas , akhir
    else :
        print ( "Nama{0} Tidak Ditemukan" . format(nama ))
```
### Outputnya adalah

![Screenshot (647)](https://user-images.githubusercontent.com/115686359/205284806-af3f02fd-0643-4c38-b0ae-05a3d119b649.png)

Kemudian untuk melihat data yang terubah ketik ```U```

![Screenshot (648)](https://user-images.githubusercontent.com/115686359/205285145-14896489-57fd-4017-bd24-65224a864043.png)

Data kemudian berubah

### 3. (H)apus data
```
def hapus():
    print ( "Hapus Data" )
    nama = input("Masukkan Nama Mahasiswa   : ")
    if  nama in  mahasiswa . keys ():
        del  mahasiswa [ nama ]
    else :
        print ( "Nama {0} Tidak Ditemukan" . format ( nama ))
```

### Outputnya adalah

![Screenshot (649)](https://user-images.githubusercontent.com/115686359/205285555-147d0797-4e85-4630-a403-d890f0fc7ee3.png)

### 4. (K)eluar

![Screenshot (650)](https://user-images.githubusercontent.com/115686359/205285859-92c3efb8-fb72-483c-9e0e-4fdb1bd18ada.png)


