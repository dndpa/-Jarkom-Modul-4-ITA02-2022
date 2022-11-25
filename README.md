# Jarkom-Modul-4-ITA02-2022

## Hasil Pengerjaan Modul 1 Praktikum Komunikasi Data & Jaringan Komputer 2022

Anggota Kelompok ITA02:
1. Muhammad Faris Anwari (5027201008)
2. Calvindra Laksmono Kumoro (5027201020)
3. Adinda Putri Audyna (5027201073)

Diberikan topologi sebagai berikut:
![soal shift 4 1](https://user-images.githubusercontent.com/58323466/203952335-763aef8a-4ef7-40f6-a6b3-61c487c2e553.png)


Setelah dilakukan perhitungan tabel dimana membutuhkan total host sebanyak 2608 dan netmask terbesar yang dibutuhkan ialah /22, maka kita dapat menggunakan netmask /20 untuk memberikan pengalamatan IP pada subnet.

Jadi untuk NID paling atas yaitu 192.211.0.0 dengan netmask /20. Berikut ini gambaran pohon sekaligus subnetting untuk pembagian IP:

![image](https://user-images.githubusercontent.com/58323466/203987947-6981fe1c-2906-49b4-80ea-a0f8a72f85a7.png)

Penjelasan:

- 192.211.0.0/20 dipecah menjadi 2 cabang yaitu 192.211.0.0/21 dan 192.211.8.0/21 
(jika panjangnya /21 maka addressessnya 2048, dimana 2048 itu 8 x 255 (255 merupakan max dalam 1 oktet)

- 192.211.0.0/21 dipecah menjadi 2 cabang yaitu 192.211.0.0/22 dan 192.211.4.0/22 
(jika panjangnya /22 maka addressessnya 1024, dimana yang mendekati 1024 itu 4 x 255 = 1020)

- 192.211.4.0/22 dipecah menjadi 2 cabang yaitu 192.211.4.0/23 dan 192.211.6.0/23
(jika panjangnya /23 maka addressessnya 512, dimana yang mendekati 512 itu 2 x 255 = 510)

dan seterusnya hingga bagian A18



 


