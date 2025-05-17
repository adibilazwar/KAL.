---
title: Persamaan Linear

---

# Persamaan Linear
## Pengertian 
Persamaan linear adalah persamaan aljabar yang setiap sukunya mengandung konstanta atau perkalian konstanta dengan variabel tunggal. Persamaan ini disebut linear karena hubungan matematisnya dapat digambarkan sebagai garis lurus dalam sistem koordinat kartesius.

## Rumus umum dalam persamaan aljabar linear 
Bentuk umum persamaan linear adalah 
Ax + By + C = 0.
di mana A, B, dan C adalah bilangan riil, A dan B merupakan koefisiensi dari x dan y; dan C merupkan bilangan konstanta. Sedangkan x dan y adalah variabel.

sementara itu, bentuk umum fungsi linear adalah y = mx + c.

- dalam persamaan linear, tidak ada eksponen selain 1 dalam suku apa pun. 
- dalam persamaan linear, penjumlahan dan pengurangan bilangan di kedua ruas tidak akan mengubah nilai persamaan tersebut. 
- dalam fungsi linear, m adalah kemiringan garis dan c adalah intersep y-nya. 
- dalam fungsi linear, jika b bernilai negatif, maka fungsi linear akan digambarkan garis dari kiri atas ke kanan bawah. 
- dalam fungsi linear, jika b bernilai nol, maka fungsi linear akan digambarkan garis yang sejajar dengan sumbu datar.

Dalam persamaan linear berlaku sifat-sifat persamaan linear sebagai berikut:

1. Nilai persamaan tidak berubah apabila:
Kedua ruas ditambah atau dikurangi dengan bilangan yang sama.
Kedua ruas dikalikan atau dibagi dengan bilangan yang sama.
2. Jika suatu persamaan dipindah ruas, maka:
Penjumlahan berubah menjadi pengurangan.
Perkalian berubah menjadi pembagian.
Berikut ini adalah contoh penerapan sistem persamaan linear dua variabel dalam soal matematika.

Tentukan himpunan penyelesaian sistem persamaan linear berikut menggunakan metode substitusi.

2x + y = 6
3x + y = 4

Langkah 1:
Pilih salah satu persamaan kemudian nyatakan y dalam x.

2x + y = 6, maka y = 6 - 2x

Langkah 2:
Substitusikan y yang diperoleh pada langkah 1 ke persamaan 2.

y = 6 - 2x disubstitusikan ke persamaan 3x + 4y = 4
Maka,
3x + 4y = 4
3x + 4 (6 - 2x) = 4
3x + 24 - 8x = 4
-5x = -20
x = 4

Setelah x diketahui, maka mari temukan nilai y.
y = 6 - 2x
y = 6 - 2 (4)
y = 6 - 8
y = -2.

## Solusi persamaan linear
Dalam memecahkan Persamaan linear terdapat beberapa solusi untuk dapat menyelesaikan persoalan tersebut. Berikut beberapa contoh metode : 

### Metode eliminasi
Metode ini bekerja dengan care mengeliminasi (menghilangkan) variabel-variabel di dalam sistem persamaan hingga hanya satu variabel yang tertinggal.

Pertama-tama, lihat persamaan-persamaan yang ada dan coba cari dua persamaan yang mempunyai koefisien yang sama (baik positif maupun negatif) untuk variabel yang sama. Misalnya, lihat persamaan (1) dan (3).Koefisien untuk y adalah 1 dan −1 untuk masing-masing persamaan. Kita dapat menjumlah kedua persamaan ini untuk menghilangkan y dan kita mendapatkan persamaan (4).

![Screenshot 2025-02-18 101749](https://hackmd.io/_uploads/rkN63OWq1l.png)

Perhatikan bahwa persamaan (4) terdiri atas variabel x dan z. Sekarang kita perlu persamaan lain yang terdiri atas variabel yang sama dengan persamaan(4).Untuk mendapatkan persamaan ini, kita akan menghilangkan y dari persamaan (1)dan (2). Dalam persamaan (1) dan (2), koefisien untuk y adalah 1 dan 3 masing-masing. Untuk menghilangkan y, kita kalikan persamaan (1) dengan 3 lalu mengurangkan persamaan (2) dari persamaan (1).

![Screenshot 2025-02-18 103003](https://hackmd.io/_uploads/r1AAA_b51x.png)

Dengan persamaan (4) dan (5), mari kita coba untuk menghilangkan z.

![Screenshot 2025-02-18 103250](https://hackmd.io/_uploads/rkkFyFW91e.png)

Dari persamaan (6) kita dapatkan x = 2. Sekarang kita bisa subtitusikan (masukkan) nilai dari x ke persamaan (4) untuk mendapatkan nilai z.

![Screenshot 2025-02-18 103434](https://hackmd.io/_uploads/H1001YW9ye.png)

Akhirnya, kita substitusikan (masukkan) nila dari x dan z ke persamaan (1) untuk mendapatkan y.

![Screenshot 2025-02-18 103559](https://hackmd.io/_uploads/SyZElKb5Jx.png)

Jadi solusi sistem persamaan linier di atas adalah x = 2, y = 3, z = 4.

### Eliminasi Gauss / Eliminasi Gauss-Jordan
Sistem persamaan liniear yang terdiri atas persamaan-persamaan (1), (2) dan (3) dapat juga dinyatakan dalam bentuk matriks teraugmentasi seperti berikut

![Screenshot 2025-02-18 103827](https://hackmd.io/_uploads/HyhplY-5yg.png)

Dengan melakukan serangkaian operasi baris (Eliminasi Gauss), kita dapat menyederhanakan matriks di atas untuk menjadi matriks Eselon-baris.

![Screenshot 2025-02-18 103919](https://hackmd.io/_uploads/ryvgWFbcye.png)

Kemudian kita bisa substitusikan kembali nilai-nilai yang kita dapat untuk mencari nilai dari semua variabel. Atau, kita juga bisa meneruskan dengan serangkaian operasi baris lagi sehingga matriks di atas menjadi matriks yang Eselon-baris tereduksi (dengan menggunakan Eliminasi Gauss-Jordan).

![Screenshot 2025-02-18 104001](https://hackmd.io/_uploads/HyX7-K-5kl.png)

Dengan melakukan operasi Eliminasi Gauss-Jordan, kita mendapatkan solusi dari sistem persamaan linier di atas pada kolom terakhir: 
x = 2, y = 3, z = 4 .