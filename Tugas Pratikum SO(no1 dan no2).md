## Informasi Mahasiswa
**Nama: Herdian Arya Erlangga**\
**NIM: 09011182328099**\
**Kelas: SK3C**
<br>
<div align="Center">
  
### TUGAS PRATIKUM SISTEM OPERASI(Ubuntu)

</div>

No 1.Buatlah laporan proses instalasi di computer mahasiswa dan tampilkan 
screenshotnya.

#PROSES INSTALLASI UBUNTU DI VIRTUAL BOX

1. Install dan download Virtual box beserta DVD Iso Ubuntu
2. Buka virtual box, dan klik "New"
![Buka virtual box, dan klik "new'](https://github.com/user-attachments/assets/f0089d91-c634-4eaf-ad0f-6f6a41e4dd56)
3. Buat nama untuk Virtual machine nya dan tentukan lokasi untuk menyimpan virtual machine, dan langsung masukan DVD Iso ubuntu yang sdh didownlaod tadi pada kotak "ISO IMAGES"
![2](https://github.com/user-attachments/assets/df36b4c4-dcef-4ac5-8f28-707cc49a7113)
4. Buat Username dan password, untuk domain itu optional
![3](https://github.com/user-attachments/assets/a54c14f7-13d0-4caf-855b-b16d89f6e7f3)
5. Atur untuk base memory dan jumlah prosesor yg akan digunakan(disini saya hanya menggunakan 2 gb ram dan 1 prosesor saja)
![4](https://github.com/user-attachments/assets/f9811c62-581d-4236-9977-87ecf88b740c)
6. sama seperti tadi disini atur jumlah untuk penyimpanan virtual machine nya(disini saya hanya menggunakan 25 gb saja)
![5](https://github.com/user-attachments/assets/88fc4868-b526-498f-b3dc-3282816deeaa)
7. jika sudah selesai semua klik finish, dan jangan lupa untuk mengubah pada setting network nya menjadi "NAT"(agar dpt akses internet)
8. Pada tampilan awal Pada virtual machine, klik di menu sebelah kiri "install Ubuntu"
![7](https://github.com/user-attachments/assets/a6e64344-0d7a-4e7d-8ae4-b1651be5d8ce)
9. Kemudian akan muncul menu pilihan.
![8](https://github.com/user-attachments/assets/a970fe4d-62a5-42b5-b086-be7d973588e6)
![9](https://github.com/user-attachments/assets/8ac3c035-2c6b-4b0b-a3f7-4cdf3626e620)
![10](https://github.com/user-attachments/assets/47cd1eb0-f6d9-4a02-b760-9b2e48577671)
![11](https://github.com/user-attachments/assets/165a7ff3-a4f1-463b-8461-161a3b901963)
![12](https://github.com/user-attachments/assets/eef85a42-763a-401a-a07d-9dfff1850103)
![13](https://github.com/user-attachments/assets/aca27bd3-f369-4140-9ffa-cb68320df7c9)
![14](https://github.com/user-attachments/assets/c7f75b58-db82-4c86-b327-7b6b9398bfec)
![15](https://github.com/user-attachments/assets/0f5f4639-8317-4df7-90d6-0c4556035c8b)
![16](https://github.com/user-attachments/assets/1c8e755d-da8b-4640-84fc-f4fd14d6ca6d)
![17](https://github.com/user-attachments/assets/296c4bf0-e598-4360-b6ca-966de391d877)
![18](https://github.com/user-attachments/assets/b0e08b74-0548-42b8-ad98-6a410521a3df)
![19](https://github.com/user-attachments/assets/0fc28769-606c-4708-95f7-1637febcc167)
![20](https://github.com/user-attachments/assets/ea83f06b-c50f-4356-bc43-036fb7497a3c)
10. Jika semua nya sdh dipilih, klik "install", dan tunggu hingga proses Installasi Ubuntu selesai
![21](https://github.com/user-attachments/assets/d156ae81-7b5f-4bf0-b1af-c71daf049a5d)
11. dan jangan lupa untuk meng-update package ny, dengan mengetikan "sudo apt-get update" pada terminal.
![22](https://github.com/user-attachments/assets/33f67e12-8937-4fdb-bab2-ee5d3ca3cfe5)


No 2.Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi mount point ?
![image](https://github.com/user-attachments/assets/53277fdd-7d8f-4c22-b459-ea1e44608bb3)

Jawab : Tanda “/” Pada sistem file di mount point tersebut digunakan untuk menunjukan, mengakses dan mengambil data dari direktori root, yg dimana ini adalah direktori tertinggi dalam hierarki sistem file, yang artinya semua file ada dibawah direktori “/” yg dimana jika file ISO Ubuntu tersebut disimpan di Documents itu sdh pasti masuk ke direktori root yakni /C:/Documents/ISO.
