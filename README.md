# Kondisional & Perulangan

# Lab 2 : Struktur Kondisi

*Latihan 1
1. Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.
*Latihan 2
1. Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.


# Lab 3 : Perulangan

*Latihan 1
1. Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:

*Latihan 2
1. Tampilkan n bilangan acak yang lebih kecil dari 0.5.
2. nilai n diisi pada saat runtime
3. anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

# Codingan
```
print('==== Bilangan Acak yang lebih kecil dari 0.5 ====')
print(' ')
import random
N = int(input("Masukan nilai N : "))
a = 0
for x in range(N):
    a += 1
    b = random.uniform(.0,.5)
    print('Data ke:',a,'==>',b)
print('Selesai')
print(' ')
jawab = 'lanjutkan'
hitung = 0
while jawab == "lanjutkan":
    hitung += 1
    jawab = input('Ingin Mengulang ? (Y/N) : ')
    if jawab == "Lanjutkan":
        break
print('Total perulangan : ' + str (hitung))
```

# Tugas Latihan 
1. Simpan project Praktikum hari ini ke repository server.
2. Buat penjelasan setiap Lab/latihannya pada file README.md

# ==============================

# NAMA  : Ahmad Fadhiil Muttaqin
# NIM   : 312010615
# Kelas : TI.20.A1
