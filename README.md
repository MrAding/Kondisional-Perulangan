```
NAMA  : Ahmad Fadhiil Muttaqin
NIM   : 312010615
Kelas : TI.20.A1
```
# ==============================

# Kondisional & Perulangan

# Lab 2 : Struktur Kondisi

*Latihan 1
1. Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

# Codingan
```
#include <iostream>
using namespace std;
int main() {
	
	cout<<"PROGRAM C++ BILANGAN TERKECIL DAN TERBESAR"<<endl;
	int terkecil, terbesar, bil1, bil2, bil3;
	cout<<"\nMasukan Bilangan ke-1 : ";
	cin>>bil1;
	cout<<"Masukan Bilangan ke-2 : ";
	cin>>bil2;
	cout<<"Masukan Bilangan ke-3 : ";
	cin>>bil3;
	
	//Menentukan nilai terkecil
	terkecil=bil1;
	
	if (bil2 < terkecil){
		terkecil=bil2;
	}
	if (bil3 < terkecil){
		terkecil=bil3;
	}
	
	//Menentukan nilai terbesar
	terbesar=bil1;
	
	if (bil2 > terbesar){
		terbesar=bil2;
	}
	if (bil3 > terbesar){
		terbesar=bil3;
	}
	
	cout<<"\nNilai Terkecil adalah "<<terkecil<<endl;
	cout<<"Nilai Terbesar adalah "<<terbesar<<endl;

	return 0;	
}
```

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
# Hasil Codingan (Program)
![hasil codingan](https://user-images.githubusercontent.com/46749500/53287636-a9dbbc80-37b1-11e9-8043-13169152b9dd.png)

# Tugas Latihan 
1. Simpan project Praktikum hari ini ke repository server.
2. Buat penjelasan setiap Lab/latihannya pada file README.md

# Sekian & Terimakasih
