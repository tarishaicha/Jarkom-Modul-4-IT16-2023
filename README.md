
# Jarkom-Modul-4-IT16-2023

- Tarisha Syira Mazaya Putri (5027211061)
- Evan Darya Kusuma (5027211069)

## Daftar Isi
- [CPT-VLSM](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/tree/main#cpt--vlsm)
- [GNS-CIDR](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/tree/main#gns-cidr)

## Topologi
![Screenshot 2023-11-28 235649](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/assets/107459188/33de07cf-9aed-48fc-b54b-8742f90313ed)

Pertama-tama, melakukan pembagian rute sesuai dengan topologi yang diberikan.

### Pembagian Rute
Berikut ini merupakan pembagian rute subnet kami
![WhatsApp Image 2023-12-02 at 3 45 32 PM](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/assets/107459188/35fc0aa6-d39f-47a6-98b9-3fb29f299e61)

Lalu, dapat didetailkan seperti yang tertera pada sheets berikut. Jumlah ip pada subnet didapat dari hasil penambahan host yang akan digabung, misal pada `A1 397 + 625 + 1(router) = 1023`. Lalu, length didapat dari tabel modul yang disesuaikan dengan jumlah ip.
![image](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/assets/107459188/aca28446-16af-4be6-a2d9-4d8f0e456d99)

### CPT-VLSM
#### Pembuatan Tree 
Berdasarkan total IP dan netmask yang dibutuhkan, maka kita dapat menggunakan netmask /19 untuk memberikan pengalamatan IP pada subnet. Subnet besar yang dibentuk memiliki NID 192.241.0.0/19. Berdasarkan NID dan netmask tersebut terbentuklah pohon seperti ini untuk menentukan pembagian IPnya.

![Jakom-Modul-4-IT16-VLSM-TREE drawio](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/assets/107459188/00b93619-de08-4458-b058-2cfaba23f0c9)

#### Pembagian IP
Berikut adalah hasil dari pembagian IP yang telah kami peroleh dari hasil pemecahan tadi menjadi jaringan yang lebih kecil.
![image](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/assets/107459188/24658828-22c6-41a4-b5a0-6288db7e7e0f)

Setelah melakukan pembagian IP, lakukan konfigurasi pada masing-masing node,server, dan client sesuai dengan pembagian subnet tadi yang sudah dilakukan.

#### Routing
Setelah dilakukan konfigurasi pada masing-masing node,server, dan client. Lalu, lakukan routing pada masing-masing node,server, dan client dengan path seperti ini dan checklist bila sudah berhasil.
![image](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/assets/107459188/30570ea0-1592-4dda-b8e9-8bc7bc44a63d)

#### Testing (result)
![image](https://github.com/tarishaicha/Jarkom-Modul-4-IT16-2023/assets/107459188/05a12f3a-7989-4020-83f6-ed530a72ebea)
Dapat dilihat seluruh percobaan telah sukses.



