CARA MEMBUAT REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB SERTA CARA MEMBUAT FILE README.md

Yang kalian butuhkan :

Akun GitHub
Software atau Program Git
DAFTAR AKUN GitHub

  Buat akun GitHub dengan cara membuka laman https://github.com
1. Masukan Username, Email dan Password yang akan kalian gunakan pada akun GitHub kalian.

![111](https://user-images.githubusercontent.com/57034810/67627704-9e361d80-f88b-11e9-8a2a-14c765192f4f.png)

2. Lalu buka email yang anda masukan tadi dan lakukan verifikasi. 
![222](https://user-images.githubusercontent.com/57034810/67627705-9e361d80-f88b-11e9-8abb-e0d8b5cdfaa7.png)

3. Setelah melakukan verifikasi, kalian akan di alihkan ke laman GitHub untuk selanjutnya membuat Repository baru, lalu masukan nama Repository kalian dan klik "create repository".

![Screenshot (8)](https://user-images.githubusercontent.com/57034810/67627749-8e6b0900-f88c-11e9-86eb-9998e5149939.png)

4. Seperti inilah tampilan Repository baru.

![333](https://user-images.githubusercontent.com/57034810/67627706-9e361d80-f88b-11e9-8f7a-75615569e785.png)

5. DOWNLOAD SOFTWARE Git


A. Untuk mendonwload![2](https://user-images.githubusercontent.com/57034810/67627784-2f59c400-f88d-11e9-844b-7e4d7e12980a.png)wnload software Git kita harus masuk ke laman https://git-scm.com

![1](https://user-images.githubusercontent.com/57034810/67627783-2ec12d80-f88d-11e9-83d8-24719034dd4e.png)

1. Pilih download dan sesuaikan dengan operating system dan spesifikasi laptop atau komputer kalian.
![2](https://user-images.githubusercontent.com/57034810/67627784-2f59c400-f88d-11e9-844b-7e4d7e12980a.png)

2. Lakukan instalasi Git pada laptop atau komputer kalian.

![3](https://user-images.githubusercontent.com/57034810/67627785-2ff25a80-f88d-11e9-90c0-c707025f4ea9.png)

3. Pastikan software atau program Git sudah terinstall 100%.

![4](https://user-images.githubusercontent.com/57034810/67627786-2ff25a80-f88d-11e9-85dd-093c7c8b2230.png)

4. Pastikan program Git sudah dapat di gunakan di perangkat kalian dengan cara membuka Command Prompt lalu ketik "git --version" jika sudah muncul berarti Git sudah dapat di gunakan.

![Screenshot (12)](https://user-images.githubusercontent.com/57034810/67627829-fd952d00-f88d-11e9-94ad-5b5d9b085b2a.png)

MEMBUAT REPOSITORY LOKAL DAN MEMBUAT FILE README.md

Buatlah "folder" baru di directory kalian lalu "klik kanan" pada folder tersebut dan pilih "Git Bash Here"

![555](https://user-images.githubusercontent.com/57034810/67627708-9eceb400-f88b-11e9-9c86-f17de5745aae.png)

Lalu konfigurasi dengan menggunakan perintah "git config --global user.name "nama_user" dan "git config --global user.email "email_user"

![666](https://user-images.githubusercontent.com/57034810/67627709-9f674a80-f88b-11e9-95de-1fb3656dc9d3.png)

Buatlah direktori baru dengan menggunakan perintah "mkdir latihan1" dan pindah ke direktori tersebut dengan menggunakan perintah "cd latihan1"

![777](https://user-images.githubusercontent.com/57034810/67627710-9f674a80-f88b-11e9-890a-2269f0aeb7d6.png)

Buat file kosong berformat .git dengan cara menjalankan perintah "git init".

![888](https://user-images.githubusercontent.com/57034810/67627711-9f674a80-f88b-11e9-8b2c-1beb337d00f1.png)

Buat file README.md dengan menggunakan perintah echo "#latihanphyton1" >> README.md"

![999](https://user-images.githubusercontent.com/57034810/67627712-9fffe100-f88b-11e9-86a1-cb68a96bc5ca.png)

Untuk melihat File, gunakan perintah ls -l

![1010](https://user-images.githubusercontent.com/57034810/67627713-9fffe100-f88b-11e9-9ae5-405507003ffd.png)

.Memasukan File README.md ke repository lokal dengan menggunakan perintah "git add README.md"

![Screenshot (22)](https://user-images.githubusercontent.com/57034810/67628029-6fbb4100-f891-11e9-993d-a4dbecef61cf.png)

.Simpan perubahan kedalam database repository dengan menggunakan perintah "git commit -m"

![Screenshot (21)](https://user-images.githubusercontent.com/57034810/67627982-9331bc00-f890-11e9-9b07-ccd1c490d7f2.png)

.Masuk ke laman GitHub dan buka URL yang sudah di buat di repository GitHub, gunakan perintah "git remote add origin [url]", contoh: git remote add origin https://github.com/alfinabdilah/latihanPhyton.git

![1111](https://user-images.githubusercontent.com/57034810/67627714-9fffe100-f88b-11e9-8e11-66ad3a418eef.png)

Kirim perubahan local repository ke GitHub dengan menggunakan perintah "git push -u origin master"

![1212](https://user-images.githubusercontent.com/57034810/67627716-a0987780-f88b-11e9-9516-a8e55787e3cb.png)

Semoga berhasi..l
