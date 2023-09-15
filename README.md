# BasicJS
## Homework Rakamin Academy
Disini saya menggunakan framework bootstrap pada tampilannya.

Berikut ini penjelasan penerapan untuk konsep OOP :
1.	Class `Pendaftar` memiliki tiga atribut: `nama`, `umur`, dan `uangSangu` dan constructor untuk membuat objek-objek dari class tersebut. Ini dapat digunakan untuk menggabungkan data yang berkaitan ke dalam satu entitas (objek) dan menjadikannya lebih terstruktur dan mudah dikelola. 
2.	Jika formulir di submit, maka sebuah objek `Pendaftar` dibuat berdasarkan input pengguna, dan objek tersebut dimasukkan ke dalam array `Listpendaftar`. Ini dapat digunakan untuk mengelola data pendaftar dengan lebih terstruktur dan mudah diakses.
3.	Fungsi updateTable digunakan untuk mengambil objek-objek `Pendaftar` yang tersimpan dalam array `Listpendaftar` dan menggambarkannya dalam bentuk tabel. 

Penjelasan JavaScript :
1.	`Pendaftar` : Class ini memiliki tiga atribut: `nama`, `umur`, dan `uangSangu`. Class ini digunakan untuk membuat objek pendaftar dengan informasi tersebut.
2.	`Listpendaftar` : Variabel ini merupakan sebuah array kosong yang akan digunakan untuk menyimpan objek-objek pendaftar yang dibuat melalui formulir.
3.	`Form` : Variabel ini merupakan elemen HTML dengan id "regist" (formulir pendaftaran) yang diambil dari dokumen.
4.	`tabeldaftar` : Variabel ini merupakan elemen HTML dengan id "tabeldaftar" (tabel yang akan menampilkan data pendaftar) yang diambil dari dokumen.
5.	`resume` : Variabel ini merupakan elemen HTML dengan id "resume" yang digunakan untuk menampilkan ringkasan informasi pendaftar seperti rata-rata umur dan uang saku.
6.	`Event Listener` pada Form mengikuti `submit` pada form. Jadi, ketika formulir diajukan (submitted), fungsi berikut dijalankan:
> Mendapatkan nilai-nilai input (nama, umur, uangSangu) dari elemen input dalam formulir.
Melakukan validasi apakah nama memiliki panjang minimal 10 karakter, umur lebih besar atau sama dengan 25, dan uang saku antara 100.000 hingga 1.000.000.
Jika data pendaftar memenuhi kriteria, maka objek ‘Pendaftar’ dibuat berdasarkan input, kemudian objek tersebut dimasukkan ke dalam array `Listpendaftar`.
7.	`form.reset` : Digunakan untuk mengosongkan formulir.
8.	`updateTable` : Fungsi ini digunakan untuk memperbarui tabel yang menampilkan data pendaftar.
