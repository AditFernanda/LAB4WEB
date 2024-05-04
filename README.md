# Lab4Web
Nama    : Adit Fernanda
<br>
Kelas   : TI.22.C6
<br>
NIM     : 312210509

# Persiapan
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab4_php_modular pada docroot webserver (htdocs).

# Tugas/Latihan
Implementasikan konsep modularisasi pada kode program praktikum 3 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

# Langkah Praktikum
1. Buat file baru dengan nama header.php lalu simpan ke dalam folder lab4_php_modular.
2. Buat file baru dengan nama footer.php, kemudian simpan ke dalam folder lab4_php_modular.
3. Buat file baru dengan nama home.php, kemudian simpan ke dalam folder lab4_php_modular.
4. Buat file baru dengan nama tambah.php, kemudian simpan ke dalam folder lab4_php_modular.
5. Buat file baru dengan nama ubah.php, kemudian simpan ke dalam folder lab4_php_modular.
6. Buat file baru dengan nama hapus.php, kemudian simpan ke dalam folder lab4_php_modular.
7. Buat file baru dengan nama koneksi.php, kemudian simpan ke dalam folder lab4_php_modular.
8. Membuat Routing
   Routing digunakan untuk mempermudah akses halaman web agar SEO Friendly. Langkah awal adalah menyiapkan file utama index.php yang berisi routing untuk mengakses banyak halaman.
   Contohnya:
   - Halaman Home ( http://localhost/lab4_php_modular/index.php?mod=home )
   - Halaman Tambah ( http://localhost/lab4_php_modular/index.php?mod=tambah )
9. Buat file baru dengan nama index.php, kemudian simpan ke dalam folder lab4_php_modular.
10. Aktivasi mod_rewrite (.htaccess)
    Mod_rewrite digunakan untuk mengubah URL dari query string menjadi SEO Friendly. Langkah awal yang harus disiapkan adalah aktivasi mod_rewrite pada webserver Apache2 pada configurasi httpd.conf.
    Cara mengakses httpd.conf :
      - Klik folder xampp
      - Pilih folder apache
      - Pilih folder conf
      - Pilih httpd.conf, kemudian aktifkan LoadModule mod_rewrite dengan cara melakukan un-comment pada baris tersebut, kemudian restart Apache2. Seperti gambar di bawah ini :
11. Kemudian membuat file .htaccess, kemudian simpan ke dalam folder lab4_php_modular.
12. Hasilnya :
![Screenshot (22)](https://github.com/AditFernanda/Lab4Web/assets/149259905/ca7bd9c7-b4bf-401d-8892-54aee4a2764a)
![Screenshot (21)](https://github.com/AditFernanda/Lab4Web/assets/149259905/18bf6141-9159-44a4-a47c-0039a45d1ce7)

# Terimakasih
