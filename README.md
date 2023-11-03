<img width="523" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/0f49894d-c1f6-4587-a53e-1b223ed0f3be">KELOMPOK 1
Nama Anggota: Muhammad Yusril Arjulio Prayitno (2209116065)
              Valentina Febrizah Peni Sogen    (2209116090)

Nama Projek: M-Banking

Deskripsi Projek : 
Program Mbangking adalah sebuah aplikasi perbankan sederhana yang memungkinkan pengguna untuk mengelola akun rekening mereka. Program ini memiliki beberapa fitur utama, termasuk daftar akun, informasi rekening, ubah PIN, dan tutup rekening. Program ini juga mendukung dua jenis rekening: rekening giro dan rekening tabungan, dengan perbedaan utama dalam tingkat bunga yang diberikan untuk masing-masing jenis rekening.

Deskripsi program Mbangking secara keseluruhan adalah sebagai berikut:

1. Daftar Akun:
Program Mbangking memungkinkan pengguna untuk mendaftarkan akun mereka. Setiap akun memiliki informasi pribadi pengguna, seperti nama, nomor akun, dan jenis rekening (giro atau tabungan).
2. Lihat Informasi Rekening:
Pengguna dapat melihat informasi lengkap tentang rekening mereka, termasuk saldo, nomor akun, dan jumlah bunga yang diperoleh. Informasi ini ditampilkan dengan memperhitungkan jenis rekening yang dimiliki oleh pengguna, sehingga pengguna dapat melihat jumlah bunga yang diperoleh untuk masing-masing jenis rekening.
3.Ubah PIN:
Pengguna dapat mengganti PIN mereka melalui program ini. Ini adalah fitur keamanan yang penting untuk menjaga kerahasiaan akun pengguna.
4. Tutup Rekening:
Jika pengguna memutuskan untuk menutup salah satu rekening mereka, mereka dapat menggunakan fitur ini. Program akan menghapus rekening yang ditutup dari daftar akun pengguna.
5. Jenis Rekening:
Program Mbangking mendukung dua jenis rekening: rekening giro dan rekening tabungan. Kedua jenis rekening ini memiliki perbedaan dalam tingkat bunga yang diberikan. Informasi mengenai bunga yang diperoleh ditampilkan dalam informasi rekening.

Dengan demikian, program Mbangking adalah aplikasi perbankan sederhana yang memungkinkan pengguna untuk mengelola rekening mereka dengan mudah, melihat informasi tentang saldo dan bunga yang diperoleh, serta mengelola pengaturan keamanan seperti PIN. Program ini juga mencapai efisiensi dalam pengelolaan jenis rekening berbeda melalui penggunaan inheritance dalam kode program.

Flowchart
![Flowchart PA final](https://github.com/Kelompok1PAPBO/PA/assets/126448864/894a4a8a-c092-4400-89b1-28ae4e369930)

ERD
![Logicalfix](https://github.com/Kelompok1PAPBO/PA/assets/126448864/4a08c601-d733-4da7-aaf8-f188767a3a83)

Hierarki Kelas

![hierarkikelas1](https://github.com/Kelompok1PAPBO/PA/assets/126448864/d5186f53-2eaa-45b6-961e-ce18f1663809)

Disini Kami menerapkan Inheritance pada Kelas Rekening, Giro dan Tabungan dimana rekening yang menjadi superclass untuk giro dan tabungan. Selain itu kami juga menerapkan polimorfisme overriding pada kelas giro dan tabungan.

Penjelasan Codingan

Class Database
<img width="497" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/2c831c05-cc21-4f5d-bbda-c2cc149fa4bd">

Disini kita membuat property static untuk Database kita.

<img width="627" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/01d14d9e-643c-41cd-9002-f6c6c5e195f6">

disini kita membuat sebuah method final bernama openconnection yang bertujuan untuk membuka koneksi ke database yang kita miliki yaitu mbanking method ini akan kita pakai jika kita ingin mengakses data yang ada pada database saat kita menggunakan program.

<img width="525" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/df4f86d8-1645-4adf-8d64-49eafa7ad10b">

disini kita membuat sebuah method final bernama closeconnection yang bertujuan untuk menutup koneksi ke database setelah penggunaan database sudah selesai dalam program. 

<img width="428" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/cf7f189b-e21f-4cd6-b531-cad67040c861">

disini kita membuat method displayerrors agar untuk menampilkan error yang terjadi ketika proses eksekusi perintah SQL.

<img width="509" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/fbd3013c-f61a-405b-bc49-3ac2eba4373e">

isini kita membuatmethod generateLastId untuk mengambil primary key dari data yang baru aja terbuat.

<img width="322" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/49aa7a7a-92ef-4a98-9fa3-920cbec151e4">

disini kita membuat properti rekeninglist yang berfungsi sebagai wadah untuk menyimpan informasi rekening-rekening yang dimiliki oleh nasabah tertentu. Getter getRekeningList() digunakan untuk mendapatkan akses ke daftar rekening tersebut.

<img width="415" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/4191f99b-e7ab-4552-a9a1-5a95e4455b64">

disini kita membuat sebuah properties yang akan membuat sebuah angka acak yang bakal dijadikan nomor rekening oleh orang yang membuat akun baru

<img width="273" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/4bbadfc5-97f1-48c2-80ac-d6125045f899">

disini kita membuat properti utama nasabah yang sama dengan yang ada ditabel nasabah;

<img width="332" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/475b1802-4648-42d4-877d-33c86dbd37d8">

<img width="428" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/cc1f92a8-32c4-4e10-9ef5-59bcca7b7536">

ini merupakan setter dan getter properti utama nasabah

<img width="727" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/7d896486-f1d7-463c-975d-34d01c0c2b3d">

ini merupakan konstruktor untuk kelas nasabah

<img width="730" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/ff3d48ea-7a87-403e-afa5-7f2ce7fb9f7e">

<img width="730" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/ce6daa3c-e711-48fd-a864-ddbe9045453c">


disini kita membuat sebuah method create yang digunakan nantinya pada gui untuk membuat sebuah akun baru. Disini kita bakal memasukkan 5 nilai dan id nya bakal ke generate secara otomatis (auto-increment) dan setiap akun baru yang terdaftar bakal terbuat sebuah nomor rekening acak dan saldo 50.000 untuk rekening nasabah yang baru mendaftar.

<img width="733" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/60fb2212-afee-4c83-94c1-979c6ed64716">

disini kita membuat method update untuk mengubah pin berdasarkan index id_nasabah yang kita pakai untuk login.

<img width="730" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/dbf752bd-2bd8-4db4-b79f-c9f37aaba5e4">

disini kita membuat method login yang digunakan untuk verifikasi login pada gui nanti nya dimana method ini akan mengambil nama nasabah sebagai username dan pin sebagai password.

<img width="730" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/5bb1cfb8-6c3b-4bfd-9277-290d10f372fe">

ini merupakan method baru untuk  melanjutkan method update agar bisa diterapkan pada GUI nantinya.

<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/b1898b80-7d6c-42ab-822d-1d0a2df69895">

ini merupakan method untuk menarik sebuah nomor rekening dan saldo dari database dengan indeks yang ditarik adalah rekening dari id nasabah yang login.

<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/f75f08ec-5c2b-4bed-a8c5-272e9bdab8a4">

ini merupakan method yang digunakan untuk menghapus akun dan rekening dengan indeks yang dihapus adalah akun dan rekening id nasabah yang login

<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/a678f07d-d95f-407e-a521-ad5cdda8ba63">

ini merupakan method untuk mengecek apakah ada nama yang sama di database dengan nama yang kita pakai untuk mendaftar.

Class Rekening (Superclass)

<img width="731" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/321c929d-c89e-4a9a-ac72-612d12fc13a3">

ini merupakan properti dari rekening serta setter dan getter dari rekening di gambar diatas juga ada konstruktor untuk kelas rekening

<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/c1cb6029-e9c2-4608-80e9-dfed99c81b4e">

di gambar atas ada 3 method yaitu tambahbunga yang digunakan untuk override pada subclass giro dan tabungan lalu ada hitungbungasaldo yang juga nntinya dipakai untuk subclass giro dan tabungan lalu yang terakhir adalah tambahsaldo ini adalah method untuk menambah saldo

<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/ab2435ed-bdbf-435a-a2b6-2faae17e1337">

di sini adalah method untuk menambah saldo lalu kita masukkan saldo yang telah tertambah tadi ke database.

Class Tabungan

<img width="731" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/0244491e-dd10-4cf0-a22b-27ab7155b010">

disini kita membuat sebuah class tabungan dimana dia merupakan subclass dari rekening sehingga mewarisi properti nomor rekening dan saldo setelah itu class tabungan juga mempunyai sebuah properti static yang digunakan untuk method tambahbunga dan hitungbungasaldo di class tabungan.

Class Giro

<img width="734" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/faf6bcb4-7f93-4363-babf-04beeb85aff3">
disini kita membuat sebuah class tabungan dimana dia merupakan subclass dari rekening sehingga mewarisi properti nomor rekening dan saldo setelah itu class giro juga mempunyai sebuah properti static yang digunakan untuk method tambahbunga dan hitungbungasaldo di class giro.

GUI.Daftarakun

<img width="725" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/e4427f56-c64a-4e06-bbb9-5027ca0f7bad">

method diatas digunakan untuk melakukan error handling ketika membuat akun.

<img width="725" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/24f52910-227c-49dc-8663-17fe617a9ee8">

<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/33f6e25e-99b6-4b1b-9238-b4c9ed7092a5">

digunakan untuk melakukan login pada GUI.

<img width="513" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/e3f2340c-6719-49cb-a4dd-04078b6cc170">

untuk kembali ke menu awal

GUI.MenuAwal

<img width="523" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/3259c33c-ff2d-48d6-aab3-3cfa724ad2e3">

Untuk memilih masuk ke menu login atau register

GUI.MenuNasabah

<img width="479" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/3135e227-b072-417e-bed1-e4a75983c6e6">

untuk masuk ke menu setoran.

<img width="727" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/1105d2e1-ac2d-42d1-b012-fd12cf60b9c6">
<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/da12007e-ce6d-482c-8546-16919e0ad5ac">

Kode ini membuat teks informasi rekening untuk seorang nasabah dan menampilkannya dalam sebuah dialog pop-up. Dalam prosesnya, program mengambil informasi rekening dari daftar rekening nasabah yang sedang masuk. Untuk setiap rekening, jenisnya diperiksa dan objek rekening yang sesuai dibuat. Jika jenis rekening tidak dikenali, program akan menampilkan pesan kesalahan. Setiap informasi rekening, termasuk nomor rekening, saldo, jenis rekening, dan bunga, ditambahkan ke teks yang akan ditampilkan. Jika terjadi kesalahan selama proses, pesan kesalahan akan ditambahkan ke teks. Akhirnya, teks tersebut ditampilkan dalam dialog pop-up dengan judul "Informasi Rekening".

<img width="730" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/75ec8d10-f2ae-455b-be61-58d7cc18d179">

untuk masuk ke menu ubahpin

<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/88c4cb53-e275-4fcf-8453-4df3f8d545f4">

untuk masuk ke menu tutuprekening

<img width="733" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/78e99f30-aeeb-4106-8b28-736ecf0dcb44">

untuk kembali ke menu login

GUI. Setoran
<img width="721" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/cd48e15a-f32f-4b7a-b3c5-9e2e3a62d6e6">

Kode ini mengambil input setoran dari sebuah teks dalam sebuah formulir (mungkin sebuah jTextField). Kemudian, ia memeriksa apakah input tidak kosong. Jika tidak kosong, program mencoba mengonversi input tersebut menjadi nilai numerik (angka). Jika berhasil, setoran tersebut ditambahkan ke saldo rekening nasabah yang sedang masuk (logged in) dan juga disimpan ke dalam database.

<img width="728" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/2fe09ba9-3d9b-4cd6-a6d3-54640382d811">

untuk kembali ke menu nasabah

GUI.TutupRekening

<img width="727" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/7554a706-ac46-4227-b7d2-8bab38c6a35d">

Kode ini mencoba menghapus akun nasabah yang sedang masuk (logged in) dari sistem. Pertama, program memanggil metode deleteAccount dari objek loggedInNasabah, yang kemudian menghapus akun dan rekening nasabah dari database. Hasil operasi penghapusan disimpan dalam variabel isDeleted.

<img width="500" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/b4b0117c-c8e5-4252-99ca-b725cf8279d5">

kembali ke menu nasabah

<img width="563" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/feb39d61-5bdf-4de0-ad92-c20225977766">

untuk keluar dari program

GUI.ubahpin

<img width="724" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/e9c83b56-9dd5-4565-9f0a-ce3e8d8038f4">

Kode ini mengambil input PIN baru dari suatu teks input (diasumsikan sebagai txtPinBaru). Pertama, program memeriksa apakah PIN baru sama dengan PIN lama yang dimiliki oleh nasabah yang sedang masuk (loggedInNasabah). Jika sama, program menampilkan pesan kesalahan menggunakan dialog pop-up JOptionPane yang menyatakan bahwa PIN baru tidak boleh sama dengan PIN lama

GUI.Login

<img width="732" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/9876a332-e05b-4ee0-b800-f0d4a6cafc8e">

Kode tersebut mengambil input username dan password dari antarmuka pengguna. Selanjutnya, ia mencoba melakukan login dengan memanggil metode login pada objek nasabah. Jika login berhasil, program menampilkan pesan "Login Berhasil" dan membuka jendela aplikasi utama. Jika login gagal, program menampilkan pesan kesalahan "Username atau Password anda salah".

Tampilan Progam

Menu Awal

<img width="238" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/695949dd-bffd-4b10-9e82-cb60d6b4a85f">

di menu ini kita bisa memilih untuk login ataupun register akun

Daftar Akun (Registrasi)

<img width="273" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/7f7e66bf-0ef5-4bb0-beb9-3df1769849d9">

disini kita bisa mendaftar akun dengan menginput beberapa informasi dan memilih jenis rekening

Login

<img width="264" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/5c591448-274c-4294-8234-ed7561d02c88">

disini kita bisa login menggunakan akun kita.

Menu Nasabah

<img width="251" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/2e9309c4-22d6-4cba-bc53-090071e6d4f6">

di menu nasabah kita bisa mengakses informasi rekening, tutup rekening, melakukan penarikan dan mengubah pin 

Menu Setoran

<img width="251" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/df3b4f57-9f10-4946-926b-4fc1550e4de4">

disini kita bisa setor uang pada rekening kita

Tutup Rekening

<img width="227" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/b6d8f19b-49a6-4211-81fa-8d2d0a970c62">

disini kita bisa menutup rekening milik kita

Ubah Pin

<img width="251" alt="image" src="https://github.com/Kelompok1PAPBO/PA/assets/126448864/c8477f4b-c330-4357-88d7-1cfeaf8e701b">

disini kita bisa mengubah pin rekening kita.


























































