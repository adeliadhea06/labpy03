Hallo perkenalkan saya Deea Dwi Adelia NIM 312210116 kelas TI.22.A1.
#Kondisional dan Perulangan
##Lab 2: Struktur Kondisi
###Latihan 1
-Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if!
Buat syntax sebagai berikut:
``` python
x = int(input("Masukkan bilangan ke 1: "))
y = int(input("Masukkan bilangan ke 2: "))
if x > y:
    print("Bilangan ke 1 adalah yang terbesar : %s "%x)
else:
    print("Bilangan ke 2 adalah yang terbesar : %s "%y)
```
![Screenshot (86)](https://user-images.githubusercontent.com/115794875/200199830-c1679848-5482-436b-8136-45fb2f3ecf19.png)

Berikut hasil setelah di run
![Screenshot (87)](https://user-images.githubusercontent.com/115794875/200199847-d952cf53-af2e-419e-b5e7-ba25599d773c.png)

###Latihan 2
-Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.
Data yang sebelumnya bersifat acak, namun kemudian diurutkan dari nilai terkecil ke terbesar.
Fungsi tersebut adalah fungsi sort().
``` short() ```
Buat syntax sebagai berikut:
``` python
angka = []
for i in range(1) :
    a = int(input("Bilangan ke- :"))
    angka.append(a)
    b = int(input("Bilangan ke- :"))
    angka.append(b)
    c = int(input("Bilangan ke- :"))
    angka.append(c)
list.sort(angka)
print("Urutan bilangan :", angka)
```
![Screenshot (88)](https://user-images.githubusercontent.com/115794875/200200029-8bcaae5f-5ec1-4d1a-ad46-b545381f072f.png)

Berikut hasil run
![Screenshot (89)](https://user-images.githubusercontent.com/115794875/200200194-0199a5f9-b839-4b4d-be05-9842252e3b98.png)

##Lab 3: Perulangan
###Latihan 1
-Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:
![image](https://user-images.githubusercontent.com/115794875/200200369-c3870dd3-66b4-4b4f-ac53-1517530ef6b8.png)

Berikut adalah syntax nya:
``` python
for i in range(0,10):
    print()
    print(i, end="\t")
    for j in range(1,10):
        print(i+j,end="\t")
```
![Screenshot (90)](https://user-images.githubusercontent.com/115794875/200200430-cdc465ce-5d7f-43ed-ad9e-008445f2841c.png)

Dan ini hasil run
![Screenshot (91)](https://user-images.githubusercontent.com/115794875/200200456-18cf8d9f-504c-44ab-b603-9ea2908081e8.png)

###Latihan 2
• Tampilkan n bilangan acak yang lebih kecil dari 0.5.
• nilai n diisi pada saat runtime
• anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

Berikut adalah syntax nya
``` python
from random import random

n = int(input("Masukkan jumlah n 5 : "))
while n==n:
    break
for i in range(n):
    bil = random()%0.5
    print("Perulangan ke : ", bil)
```
![Screenshot (93)](https://user-images.githubusercontent.com/115794875/200200627-e029e4ab-c7e4-4979-83f7-536602651764.png)

Berikut hasil run
![Screenshot (94)](https://user-images.githubusercontent.com/115794875/200200685-608297f6-36b9-419f-899b-51dd8a6b48f4.png)


#Modul Praktikum 2 dan Praktikum 3
###Labspy02
Buat program sederhana dengan input 3 buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya. Gunakan statement if. Sertakan flowchart dan algoritmanya.
- Berikut adalah flowchartnya
![image](https://user-images.githubusercontent.com/115794875/200201257-577ec925-c85d-42d6-b058-86d3e1e67ded.png)

Berikut ini adalah logika untuk mencari angka terbesar
![Screenshot (105)](https://user-images.githubusercontent.com/115794875/200201377-b3ca7545-2309-47a8-937e-e42bedc9f9d4.png)

Berikut hasil run
![Screenshot (106)](https://user-images.githubusercontent.com/115794875/200201406-19f6a1ec-79f5-4b0b-9c3a-f19777efef00.png)


##Labspy03
###Latihan1
1. Tampilkan n bilangan acak yang lebih kecil dari 0.5.
2. nilai n diisi pada saat runtime.
3. anda biasa menggunakan kombinasi while dan for untuk menyelesaikannya.
4. gunakan fungsi random() yang dapat diimport terlebih dahulu

Berikut syntax nya
![Screenshot (97)](https://user-images.githubusercontent.com/115794875/200201711-410c5bbd-7515-49ab-9d4c-f5963178934a.png)

Dan ini hasil run
![Screenshot (98)](https://user-images.githubusercontent.com/115794875/200201728-edd8ed5f-e539-4e0f-937c-799189bf2549.png)

###Latihan 2
Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan. Masukkan angka 0 untuk beerhenti.

Berikut syntax nya
![Screenshot (99)](https://user-images.githubusercontent.com/115794875/200201809-dcbaf7ad-eff7-4c26-8173-478e084b06e1.png)

Dan ini hasil run
![Screenshot (100)](https://user-images.githubusercontent.com/115794875/200201823-660b4ec0-742c-4411-8676-49ff0085353b.png)

###Program 1
Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba . pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8 bulan berjalan usahanya.

- Berikut adalah flowchatnya.
![image](https://user-images.githubusercontent.com/115794875/200202258-ee81883c-1c44-4f7d-84f0-609bd79b0785.png)

- Algoritmanya
1.Mulai

2.Mencetak latihan1

3.Mencetak "Program menghitung laba dengan modal awal 100 juta"

4.Membuat Note 

5.Mencetak Bulan pertama dan kedua = 0%

6.Mencetak bulan ke 3 = 1%

7.Mencetak bulan ke 5 = 5%

8.Mencetak bulan ke 8 = 2%

9.integer a = 100.000.000( modal awal)

10.Menggunakan fungsi looping for pada nilai x 1-9 untuk menampilkan 
bulan 1 sampai 
bulan 8.

11.Menggunakan fungsi if, untuk menghitung laba bulan 1 sampai 8

12.bulan pertama dan kedua laba adalah 0

13.bulan ke 3 dan ke 4 mendapat laba 1% sehingga modal di kali 1% = 
keuntungan

14.bulan ke 5 mendapatkan laba 5%, sehingga modal dikali 5% = keuntungan 

15.Bulan ke 8 mmendapatkan laba 2% sehingga keuntungan menurun dari 
bulan sebelumnya, 
modal dikali 2% = keuntungan.

16.Menghitung jumlah total laba dengan menjumlah keuntungan dari bulan 
ke 1 sampai 
bulan 8, hasilnya adalah total keuntungan yang didapat.

17.Selesai

- Syntax sebagai berikut
![Screenshot (103)](https://user-images.githubusercontent.com/115794875/200202373-116f2ac9-6316-4fda-a143-2ee4d9592615.png)

Ini hasil run
![Screenshot (104)](https://user-images.githubusercontent.com/115794875/200202397-f236dde2-a768-43b9-9054-5aaae4fb4e7d.png)

#SEKIAN, TERIMA KASIH
