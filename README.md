Latihan1

![images](https://user-images.githubusercontent.com/46748866/51760204-7a775880-20fc-11e9-8e65-c9afe0147a61.jpg)

TUTORIAL CARA MENGGUNAKAN GIT
apa git itu ?

Git adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

Langkah-langkah Install GIT di berbagai jenis sistem

Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

1. Buka website ini dan download installer GIT untuk Windows.
2. Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.

PERINTAH DASAR GIT

1. git init, perintah untuk membuat repository local
2. git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
3. git commit, perintah untuk menyimpan perubahan kedalam database git.
4. git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
5. git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
6. git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).

Langkah-Langkah Menggunakan Git

1. Klik kanan pada monitor Klik " Git Bash Here"
![1](https://user-images.githubusercontent.com/46748866/51762760-39cf0d80-2103-11e9-9253-ca358393e2b8.png)

2. Maka akan ada tampilan command prompt seperti dibawah ini
![2](https://user-images.githubusercontent.com/46748866/51760656-7ac42380-20fd-11e9-8bc2-69f05f5a7e75.png)

3. Buka Drive yang ingin dipakai, semisal Drive D jalankan dengan perintah cd /d
![3](https://user-images.githubusercontent.com/46748866/51760766-dbebf700-20fd-11e9-89f9-81954ac41656.png)

4. Buat directory dengan printah "mkdir" sebagai contoh : directory Pemograman1
![4](https://user-images.githubusercontent.com/46748866/51760812-00e06a00-20fe-11e9-9cfb-49ea6ddfb714.png)

5. Buka directory Pemograman1 dengan perintah cd Pemograman1
![5](https://user-images.githubusercontent.com/46748866/51760905-384f1680-20fe-11e9-9a18-5adfdf14f3ff.png)

6. Buat directory latihan1 dan buka directory latihan1.
![6](https://user-images.githubusercontent.com/46748866/51760980-66ccf180-20fe-11e9-810a-5cb2a9cccf66.png)

7. Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md
![7](https://user-images.githubusercontent.com/46748866/51761000-7e0bdf00-20fe-11e9-923f-918e1192f3da.png)

8. Jalankan perintah git init untuk menjalankan repository local
![8](https://user-images.githubusercontent.com/46748866/51761109-c0cdb700-20fe-11e9-8d14-6560c43b5382.png)

9. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md
![9](https://user-images.githubusercontent.com/46748866/51761189-fb375400-20fe-11e9-89fe-6cedb26dbc3c.png)

10. Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"
![10cuk](https://user-images.githubusercontent.com/46748866/51762115-697d1600-2101-11e9-9b27-281c6572a463.png)

11. Buat repository server, isi nama repositorynya semisal : latihan1 ,kemudian klik tombol Creat repository
![10](https://user-images.githubusercontent.com/46748866/51761217-173af580-20ff-11e9-92b0-0746d464df2d.png)

12. Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak user.
![11](https://user-images.githubusercontent.com/46748866/51761249-346fc400-20ff-11e9-8d10-9740f478b385.png)

13. Mengirim perubahan ke server dengan perintah git push -u origin master 
![12](https://user-images.githubusercontent.com/46748866/51761289-494c5780-20ff-11e9-96a1-c47ee8e921e5.png)
14. Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut
hasil 01
![13](https://user-images.githubusercontent.com/46748866/51761338-63863580-20ff-11e9-940a-f71026415014.png)

15. Buka drive D kemudian klik Pemograman1, klik latihan1 klik latihan1
![14](https://user-images.githubusercontent.com/46748866/51762186-a0ebc280-2101-11e9-8481-d6c478e53d3d.png)

16. Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad
![15](https://user-images.githubusercontent.com/46748866/51762276-dc868c80-2101-11e9-8756-df51790c2094.png)

17. Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihan1"
![16](https://user-images.githubusercontent.com/46748866/51762356-122b7580-2102-11e9-8ff6-1f2dfc6e9b63.png)

18. Kemuidan lihat perubahannya pada laman github.com
![17](https://user-images.githubusercontent.com/46748866/51762395-312a0780-2102-11e9-8cdb-d97479b90536.png)

Sekian dan Terimakasih ~miftakhul yusro~
Sekian dan terima kasih
