Buat 50 command line di ubuntu

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
31. sudo chown
