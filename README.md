#  Cara Menggunakan GitHub & Perintah Dasar GitHub
## Pengenalan
Jika kita berbicara tentang version control system, maka ada banyak sekali GIT yang bagus, baik dari sisi relevansi maupun performa. GIT dikembangkan oleh pengembang UNIX, Linus Torvalds, pada tahun 2005 dan hari ini telah digunakan oleh jutaan perusahaan untuk melakukan manajemen efisiensi kode dan kontrol versi untuk project mereka. Software ini bersifat open source dan bisa di-download untuk Linux, Windows, Solaris dan Mac. Informasi lebih lengkap tentang GIT bisa Anda temukan disini. Dalam tutorial ini, kita akan banyak membahas tentang perintah GIT.
## Yang Anda butuhkan
Sebelum memulai, yang Anda butuhkan adalah:

.GIT yang telah ter-install di sistem Anda

# Cara Install Git di Windows
Cara install Git di Windows terdiri dari 10 langkah. Berikut adalah penjelasannya:

## 1. Download File Git
untuk menginstall Git, Anda perlu mengunduh file-nya terlebih dahulu di situs resminya. Download sesuai tipe sistem operasi pada komputer Anda. Apabila tipe sistem operasi komputer Anda 64bit,  pilih Git yang mendukung Windows 64bit. Tujuannya adalah agar tidak terjadi error saat proses instalasi Git.

## 2. Install Git
Setelah selesai mengunduh file Git, buka setup aplikasi Git untuk memulai proses instalasi. Halaman awal setelah Anda membuka setup aplikasi Git adalah tampilan Document License dari Git. Klik Next untuk melanjutkan instalasi.
![Screenshot1](https://user-images.githubusercontent.com/72791776/95842961-60b6f280-0d71-11eb-9f8a-b650ddcef2ac.png)

## 3. Tentukan Lokasi Instalasi Git
Selanjutnya, pilih lokasi untuk install Git pada komputer Anda. Pada tutorial ini kami menginstall di lokasi **C:\Program Files\Git**. Setelah menentukan lokasi instalasi Git, klik Next untuk melanjutkan.
![Screenshot2](https://user-images.githubusercontent.com/72791776/95842968-6280b600-0d71-11eb-844f-f8cb7d5d60c2.png)

## 4. Pilih Komponen Tambahan
Kemudian pilih komponen tambahan untuk install Git. Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar. Sesuaikan komponen tambahan yang dipilih seperti pada gambar di bawah ini. Jika sudah klik Next untuk melanjutkan instalasi.
![Screenshot3](https://user-images.githubusercontent.com/72791776/95842971-63194c80-0d71-11eb-89c9-b1e08e25dfdd.png)

## 5. Tentukan Nama Aplikasi Git
Sebenarnya Anda bebas mengganti nama aplikasi Git yang akan ditampilkan pada Start Menu. Akan tetapi, demi kemudahan saat mencari aplikasi ini, sebaiknya gunakan nama Git saja.
![Screenshot4](https://user-images.githubusercontent.com/72791776/95842976-644a7980-0d71-11eb-8d56-fdc780ef3153.png)

## 6. Tentukan File Editor
Untuk mengedit script melalui Git, Anda memerlukan file editor. Anda bebas menggunakan file editor apa pun untuk dikombinasikan dengan Git. Pada tutorial ini, kami menggunakan Vim Editor. Klik Next apabila Anda sudah menentukan file editor yang akan Anda gunakan.
![Screenshot5](https://user-images.githubusercontent.com/72791776/95842994-690f2d80-0d71-11eb-966f-0833872483df.png)

## 7. Atur Path Environment
Selanjutnya adalah pengaturan Path Environment. Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih Git from the command line and also from 3rd-party software agar saat menjalankan perintah Git dapat dikenali di Command Prompt (CMD) pada Windows.
![Screenshot_6](https://user-images.githubusercontent.com/72791776/95843066-7a583a00-0d71-11eb-99ca-83068ecdadce.png)

## 8. Pilih Aplikasi SSH
Kemudian untuk mengeksekusi SSH, Anda bisa menggunakan aplikasi dari Git atau  dari platform lain seperti PuTTY dan Bitvise. Pada tutorial ini kami menggunakan Use OpenSSH, aplikasi default SSH dari Git. Klik Next untuk melanjutkan instalasi.
![Screenshot_7](https://user-images.githubusercontent.com/72791776/95843073-7c21fd80-0d71-11eb-9331-cfdf5cddc0f4.png)

## 9. Pilih Line Ending
Selanjutnya, Anda perlu memilih pengaturan line ending. Pada tutorial ini kami memilih Checkout Windows-style, commit Unix-style line endings. Klik Next untuk melanjutkan instalasi.
![Screenshot_8](https://user-images.githubusercontent.com/72791776/95843089-7f1cee00-0d71-11eb-816d-6ea9fc5941b7.png)

## 10. Pilih Emulator Terminal
Setelah itu, Anda perlu memilih emulator terminal yang akan digunakan. Anda bisa menggunakan Command Prompt atau MinTTY. Karena ingin menggunakan Command Prompt, pada tutorial ini kami memilih Use Windows’ default console windows. Klik Next untuk melanjutkan instalasi.
![Screenshot_9](https://user-images.githubusercontent.com/72791776/95843092-804e1b00-0d71-11eb-93ab-7d0589638264.png)

## 11. Tentukan Opsi ekstra
Terdapat beberapa opsi ekstra yang bisa Anda pilih. Pertama, pilih Enable File System Caching agar Git memiliki fungsi system caching. Kedua, pilih Enable Git Credential Manager agar Git bisa dikombinasikan dengan aplikasi lain seperti Visual Studio, Android Studio, dan GitHub. Klik Next untuk melanjutkan instalasi.
![Screenshot_10](https://user-images.githubusercontent.com/72791776/95843097-8217de80-0d71-11eb-81d6-78564207ebbe.png)

## 12. Mulai Proses Instalasi
Setelah menambahkan konfigurasi ekstra pada Git, Anda bisa memulai proses instalasi Git. Klik Install untuk melanjutkan proses.
![Screenshot_11](https://user-images.githubusercontent.com/72791776/95843102-83490b80-0d71-11eb-9bce-82404425ab93.png)
Berikut ini adalah tampilan proses instalasi Git. Tunggu hingga proses selesai dan Anda bisa menggunakan Git pada Windows.
![Screenshot_12](https://user-images.githubusercontent.com/72791776/95843110-8643fc00-0d71-11eb-8e1c-fd6442addd1b.png)

## 13. Cek Versi Git
Setelah proses instalasi selesai, Anda perlu mengecek apakah instalasi Git berhasil atau tidak. Anda bisa mengeceknya melalui Command Prompt. Klik Win+R lalu ketik CMD untuk membuka Command Prompt seperti di bawah ini.
![Screenshot_13](https://user-images.githubusercontent.com/72791776/95843126-8a701980-0d71-11eb-94eb-d265f7bb253f.png)

# Cara Penggunaan Git






