# latihan01
# LANGKAH LANGKAH AWAL DALAM MENGGUNAKAN GITHUB

# Membuat akun pada layanan github
untuk menggunakan git, dibutuhkan sebuah layanan. Layanan yang tersedia sangat banyak namun saya menggunakan github, tidak masalah kalau nanti misalnya mau pindah ke layanan lain seperti gitlab seperti yang saya lakukan sekarang, karena saya tetap menggunakan keduanya.

![1111](https://user-images.githubusercontent.com/46512870/51582177-85b06580-1efd-11e9-8759-adbacbcfc414.png)

Setelah terbuat akun-nya, login dengan akun baru (kalau langsung diarahkan ke halaman utama), setelah itu pada pojok kanan atas terdapat tombol “+”, klik button tersebut dan pilih “new repository”.

# Membuat Repositori online
![99](https://user-images.githubusercontent.com/46512870/51588545-24958b80-1f17-11e9-9451-415f398805de.png)


![333](https://user-images.githubusercontent.com/46512870/51588743-ac7b9580-1f17-11e9-97fa-93600e0e22cb.png)

Lalu kalian akan diarahkan ke halaman pembuatan repository, pembuatan repositori ini tergantung dari project kalian yang mau kalian upload, jadi saya harapkan kalian sudah punya proyek yang ingin di upload ke repositori.

Untuk mengisi, ada beberapa hal yang perlu di perhatikan :

•	Repository name : nama repository(isi saja dengan nama proyek), akan lebih rapi kalau misalnya nama repository juga di beri jenis pemogramannya juga contohnya “Android/test” atau “js/test”.

•	Description : deskripsi repository (bisa kisah project dan siapa yang terlibat)

•	Public/Private : kondisi repository mau di public (di buat umum) atau private(di buat pribadi atau tertutup)

•	Intiallize the repository with README : ini adalah isi dokumentasi pada project yang dikerjakan, saya sarankan tidak usah di centang karena mempermudah praktek untuk mengelola git.

Setelah di isi sesuai dengan keinginan, klik saja tombol “create repository”, maka pada halaman selanjutnya akan menampilkan repositori yang sudah dibuat, dan tahap selanjutnya adalah upload project ke repository online.

![4](https://user-images.githubusercontent.com/46512870/51582738-05d7ca80-1f00-11e9-8a77-1b470da0f8c4.png)

Mengupload folder(repositori lokal)

Sebelum melakukan upload pastikan di PC atau laptop sudah tersedia git, untuk Windows bisa menggunakan cmder yang sempat saya tulis disini untuk memudahkan proses penggunaan git, sedangkan untuk pengguna linux bisa menginstall dengan menggunakan perintah “sudo apt-get install git” jika menggunakan OSX install dengan brew, jika sudah file siap di upload ke repository online.


jika sudah memiliki proyek yang ingin diletakkan di repository online, buka saja folder project tersebut dengan perintah command line, atau jika belum terbiasa di command line (nanti belajar command line) buka saja folder tersebut menggunakan file exploler dan klik kanan “open terminal/cmder here”. Ada beberapa perintah dasar yang akan digunakan, perintah ini sudah tersedia kok saat membuat repo tadi (lihat gambar atas) 

git init 

git add .

git commit -m "first commit" 

git remote add origin https://github.com/AbimanyuYoga/Latihan1.git

git push -u origin master
 
