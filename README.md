# UAS

Uas Pemrograman Web 2 Kelompok 2 Anggota :

Asep Indrawan 17101101498</br>
Aniessa Aulia 171011401448
Agus Salim 2016140870
Andhika Hamzah
Arif Rahman

DATA RELAWAN COVID 19

1. Form Login
![Login](https://user-images.githubusercontent.com/62058874/87854352-92b7e480-c93b-11ea-99fb-565b3b4b8f56.png)
Pada page login menggunakan php dan mysql untuk authentikasi. Setelah mengisikan form username dan password. 
Terdapat fungsi php isset($_GET['pesan']) untuk mengecek notifikasi apakah user dalam keadaan login / tidak
tedapat form untuk login dengan method post untuk mengirimkan data, pada form juga terdapat action'file_tujuan.php untuk menentukan file tujuan setelah submit


2. Form Dashboard
![dashboard](https://user-images.githubusercontent.com/62058874/87854477-87b18400-c93c-11ea-8a23-bc377bd5e6e9.png)
Menampilkan data pada web yang tekoneksi kedatabase.


3. Form Edit
![edit](https://user-images.githubusercontent.com/62058874/87854489-95ffa000-c93c-11ea-9efa-d5aaffd216f2.png)
Menampilkan form edit data untuk mengedit data yang sudah ada.
terdapat fungsi session_start untuk inisialisasi / mengaktifkan session
terdapat funsgi php include 'koneksi.php' untuk menghubungkan dengan file koneksi.php
terdapat fungsi $_GET[id] untuk mendapatkan id_pembayaran
terdapat form dengan method get dan action ke cek_edit data untuk proses edit data ke database
terdapat fungsi php mysqli_query dengan syntaks select untuk mendapatkan data dari database penerimaan kemudian data
tersebut di letakan pada value form untuk empermudah proses edit data


4. Form Tambah
![tambah](https://user-images.githubusercontent.com/62058874/87854493-9bf58100-c93c-11ea-8f2e-899992481013.png)
Menampilkan form tambah data untuk menambah data yang sudah ada.
Terdapat fungsi session_start untuk inisialisasi / mengaktifkan session
terdapat funsgi php include 'koneksi.php' untuk menghubungkan dengan file koneksi.php
terdapat fungsi isset($_GET[...]) untuk mengecek notifikasi apakah user dalam keadaan login / tidak
terdapat method $_POST[..] untuk mendapatkan data dari form
terdapat $_SESSIO[id_admin] untuk mendapakan data id_admin
terdapat mysqli_query dengan metode sql SELECT untuk mendapatkan id_alokasi dari jenis_alokasi
terdapat mysqli_query dengan metode sql INSERT untuk menambahan data tesebut ke database
