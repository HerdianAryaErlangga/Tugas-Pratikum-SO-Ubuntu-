## Informasi Mahasiswa
**Nama: Herdian Arya Erlangga**\
**NIM: 09011182328099**\
**Kelas: SK3C**
<br>
<div align="Center">
  
## Buat 50 command line di ubuntu
</div>


command line :


![1](https://github.com/user-attachments/assets/3f07b660-9f9c-42c5-b734-84745c52e5ea)


1. lsb_release -a (melihat versi Ubuntu)
2. pwd (melihat directory saat ini)
3. ls (melihat isi directory)
4. mkdir project (membuat direktori baru dengan nama "project")
5. cd project (masuk ke direktori baru)
6. touch tes.txt (membuat file kosong dengan nama "tex.txt")
7. nano tes.txt (membuka file "tes.txt" dengan editor text)
8. echo "hello" > tes.txt (menambahkan teks yakni "hello" ke dalam tes.txt)
9. cat tes.txt (melihat isi file(hanya baris pertama saja yg ditampilkan))
10. cp tes.txt tes2.txt (menyalin file dari tes.txt ke tes2.txt)
11. mv tes2.txt herdian.txt (mengganti nama file dari "tes2.txt" ke "herdian.txt")
12. echo "file2" . dupe.txt (membuat file dan menambah isinya)
13. cat herdian.txt dupe.txt > gabungan.txt (menggabungkan dua file menjadi 1 ke dalam file "gabungan.txt")
14. rm dupe.txt (menghapus file "dupe.txt")
15. mkdir newfolder(membuat folder baru di dalam folder)
16. mv herdian.txt newfolder/ (memindahkan file "herdian.txt" ke folder "newfolder")
17. cp -r newfolder/ newfolder2/ (menyalin direktori dan isinya dari "newfolder1" ke "newfolder2")
18. ls -R (melihat isi direktori secara rekursif, yg dimana pada bagian ini melihat direktori "project")
19. clear (Untuk membersihkan/mengosongkan terminal)
20. cd .. (untuk keluar satu tingkat dari direktori yg dibuka sebelumnya)



![2](https://github.com/user-attachments/assets/a5352f84-25ec-461d-aabd-4ea7f2ef50c8)


21. df -h (melihat penggunaan disk)
22. du -sh project (melihat penggunaan ruang dalam direktori "project")
23. ls -a (menampilkan file tersembunyi di direktori)
24. rmdir newfolder2 (menghapus direktori kosong, karena newfolder2 saya berisi file maka tidak bisa dihapus)
25. rm -r newfolder2 (menghapus direktori beserta isinya)
26. chmod +x script.sh (membuat file dengan hak akses tertentu)
27. ./script.sh (menjalankan script bash)
28. ps aux


![3](https://github.com/user-attachments/assets/e978cf90-f9e3-4705-8eba-622a61a42c47)


29. kill 3806 (membunuh proses yang berjalan berdasarkan nomor PIDD yg di tampilkan pada command ps aux sebelumnya)
30. find . -name "herdian.txt" (mencari file dalam direktori)
31. sudo command_name ("sudo" untuk menjalankan perintah dengan hak akses root
32. sudo chown angga:angga tes.txt (mengganti kepemilikan file, karena saya hanya memiliki satu user jadi cmn ada name user "angga"
33. sudo apt update (meng-update package list)


![4](https://github.com/user-attachments/assets/cb41d161-cc1d-4e20-8889-309cd1259070)

34. sudo apt upgrade (meng-upgrade sistem)


![5](https://github.com/user-attachments/assets/02da54a1-436b-4940-8bcf-8cecdc303175)


35. sudo apt install vim (menginstall aplikasi)
36. sudo apt remove vim (menghapus aplikasi)
37. sudo apt autoremove (membersihkan package yang tidak terpakai)
38. grep "hello" tes.txt ("grep" untuk mencari teks dalam file)
39. man ls (menampilkan halaman manual dari perintah)
40. wx -l tes.txt (menghitung jumlah baris dalam file)
41. swapon --show (menampilkan ruang swap)


![6](https://github.com/user-attachments/assets/4df17090-0c44-4a57-93da-6eb9fc14a8ca)


42. ip add (melihat ip address)
43. ifconfig (melihat konfigurasi jaringan)


![7](https://github.com/user-attachments/assets/bc266ca2-d288-4d69-a89e-fe8ca4020406)


44. sudo adduser guest (menambahkan user baru yakni "guest")


![8](https://github.com/user-attachments/assets/8db78164-7700-46c3-9d98-bb63cf04488a)


45. sudo deluser guest (menghapus user guest)


![9](https://github.com/user-attachments/assets/389d7e17-0373-47f7-ac74-912221b3a28b)


46. sudo lshw -short (menampilkan informasi hardware)


![10](https://github.com/user-attachments/assets/b5a9f4f7-afa1-4a55-bfa9-aaa05b63efbb)


47. ifstat (melihat statistik penggunaan jaringan)


![11](https://github.com/user-attachments/assets/24201a62-7da9-4c28-894e-03a59abf9458)


48. netstat -tuln (menampilkan daftar port yang sedang dibuka oleh sistem)
49. tar -czvf archive.tar.gz project/ (membuat arsip tar dan mengompresnya dengan gzip)
50. sudo timedatectl set-timezone Asia/Jakarta
51. sudo shutdown now (mematikan/men-shutdown sistem)
