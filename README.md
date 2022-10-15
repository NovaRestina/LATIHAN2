# LATIHAN2
Tutorial Penggunaan Git
Download Git di web resmi (git-scm.com)
    1. Login Git
Masukkan username yang diperintah
$ git config --global user.name "Nova Restina Maharani"
$ git config --global user.email "novarestina03@gmail.com"
![Gambar 1](screenshot/ss1)

    2. Login GitHub
Masuk ke http://github.com untuk membuat server repository
![Gambar 2](screenshot/ss2)
buat akun di github
klik New Repository
isi nama repositorynya
lalu klik tombol creat repository

    3. Buat Folder
Buat New folder dilocaldisk kalian
![Gambar 3](screenshot3)
tulis Labs2, didalamnya LATIHAN2
untuk membuat dan membuka folder dengan menggunakan perintah tersebut
$ pwd
$ cd /d/Labs2/
![Gambar 2](screenshot/ss2)
buka halaman akun anda di github untuk menyalin link
![Gambar 4](screenshot/ss4)
kemudian kembali dihalaman gitbash
$ git clone https://github/NovaRestina/LATIHAN2.git
kemudian buka folder pilih README buka dengan Visual Studio code
![Gambar 5](screenshot/ss5)
$ cd LATIHAN2/
$ git add LAT2_tag_dasar.html di folder tersebut bisa dibuka dengan firefox
![Gambar 6](screenshot/ss6)
$ git status dan muncul tulisan new file: LAT2_tag_dasar.html
$ git commit -m "menambahkan file LAT2_tag_dasar.html supaya muncul dihalaman web github akun kita
![Gambar 7](screenshot/ss7)
![Gambar 8](screenshot/ss8)
$ git push -u origin main 
kemudian muncul github di browser untuk mengirim file repository
setelah itu menghubungkan server github untuk login akun anda
pilih Authorize
muncul Authention succeeded
![Gambar 8](screenshot/ss8)



