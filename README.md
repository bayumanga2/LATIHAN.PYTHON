BERIKUT LANGKAH-LANGKAH PEMBUATAN REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB DAN MEMBUAT FILE README.md
HAL HAL YANG DIBUTUHKAN ADALAH
--> SOFTWARE GIT & AKUN GIT
1. UNDUH SOFTWARE GIT di git-scm.com pilih sesuai os laptop atau pc
![unduh git](https://user-images.githubusercontent.com/56962466/67504823-54470f00-f6b4-11e9-973f-94ff61ce12e2.png)

2. SETELAH TERUNDUH LANJUT INSTAL GIT, DAN KLIK NEXT SAJA
3. UJI GIT SUDAH BERJALAN ATAU TIDAK DENGAN CMD. OPEN CMD LALU KETIK git --version
bila sudah terpasang akan muncul tulisan seperti ini
![cek git sdh terpasang](https://user-images.githubusercontent.com/56962466/67505363-4a71db80-f6b5-11e9-8a55-74a1116f346f.png)

4. Lanjut, pembuatan akun di web github.com. isi biodata seperti berikut
![buat akun](https://user-images.githubusercontent.com/56962466/67505471-873dd280-f6b5-11e9-9b59-a8c74e9365ef.png)
5. LALU VERIFY AKUN DENGAN CAPTCHA,PILIH FREE 0$ USD, PILIH A LITTLE dan klik skip
6. git akan mengirim pesan di gmail untuk melakukan verify
![verifikasi email](https://user-images.githubusercontent.com/56962466/67505858-38446d00-f6b6-11e9-9071-0a0e0e2c96e7.png)

Lanjut, klik creat a new repository isi repository name lalu klik creat repository
![pembuatan resitory](https://user-images.githubusercontent.com/56962466/67506104-ad17a700-f6b6-11e9-8a2a-8250560154d0.png)
7. Lanjut, klik kana pada dekstop lalu klik git bash here
![klik git base](https://user-images.githubusercontent.com/56962466/67506245-e94b0780-f6b6-11e9-8939-791c0595b501.png)
8.Lanjut konfigurasikan dengan memasukan perintah "git config --global user name "nama_user" dan
"git config --global user.email"name@"
![git 1 config global](https://user-images.githubusercontent.com/56962466/67506523-64142280-f6b7-11e9-9cf3-6c42051f2335.png)
9. Buat direktori baru dengan perintah "mkdir latihan 1" lalu "cd latihan 1"
![gi 2 mkdir](https://user-images.githubusercontent.com/56962466/67506615-9887de80-f6b7-11e9-934a-1328a9ace492.png)
10. Masukan perintah "git init" lalu enter. Untuk membuat file kosong berformat .GIT
![git 3 init](https://user-images.githubusercontent.com/56962466/67506861-0a602800-f6b8-11e9-9e1f-2c91149ddf8d.png)
11. Lanjut, masukan perintah "echo "#latihanpythn1" >> README.md" untuk membuat file bernama README.md
 masukan perintah "ls -l" untuk melihat file
 ![git 4 echo](https://user-images.githubusercontent.com/56962466/67507290-d0dbec80-f6b8-11e9-9023-2fd96a1af3fa.png)
12. Lanjut masukan perintah "git add" untuk menambahkan file README.md
![git 5 mnmbh file READ dan melihat file](https://user-images.githubusercontent.com/56962466/67507096-780c5400-f6b8-11e9-9550-62ca0297bb43.png)
13. Jalankan perintah "git commit -m" untuk menyimpan perubahan yang ada ke dalam database repository
![git 9 git push](https://user-images.githubusercontent.com/56962466/67508389-20231c80-f6bb-11e9-8f9f-22882b840dfb.png)
14. copy url akun GIT pada tampilan repository. url tersebut akan digunakan untuk perintah "git remote add origin [url]
15. Masukan perintah "git remote add origin[url] yang telah di copy

16. Cek hasilnya di github dan lihat repositornya
![git 10 hasil repository](https://user-images.githubusercontent.com/56962466/67509276-d804f980-f6bc-11e9-87e3-6f90a8b77011.png)


