
<html>
<body>
<div align="center"><h1> Software Requirements Spesification </h1></div>

<p align="center"><b>Version 1.7 </b><br>
<p align="center">23 Oktober 2023 </b>
<p align="center">

</p>

<p align="center"><b> Sistem Informasi Penerimaan Siswa Baru SMP Al-Azhar Syifa Budi Pekanbaru II <br>
</b>
<p align="center">Kelompok 3 <br>
Denisa Ruthdiani Siagian    (2257301031)<br>
Daud Markhesywan    (2257301030)<br>
Desfian Zahta Gunawan   (2257301032)<br><br><br>

<p align="center"><b>Jurusan Teknik Informasi</b><br>
<p align="center"><b>Politeknik Caltex Riau</b>
<p align="center"><b>2023</b>
</p>
</body>
</html>

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Sistem Informasi Penerimaaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II". Dokumen ini dibangun untuk mempermudah bagi calon siswa yang akan mendaftar di SMP Al-Azhar Syifa Budi Pekanbaru II yang mengubah sistem lama secara konvensional dalam melakukan pendaftaran siswa baru tersebut menjadi secara terstruktur yaitu pendaftaran secara online. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "Sistem Informasi Penerimaan Siswa Baru SMP Al-Azhar Syifa Budi Pekanbaru II".

1.2   Lingkup
----------
Sistem Informasi Penerimaan Mahasiswa Baru SMP Al-Azhar Syifa Budi Pekanbaru II merupakan aplikasi yang kami bangun untuk mempermudah proses pendaftaran calon siswa dan untuk meningkatkan efisiensi dari waktu para guru atau panitia dan calon siswa itu sendiri.

1.3    Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses aplikasi |
| Software Requirement Specification | Perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| Use Case | Situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4 Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah:
-
-
-

1.5 Overview
---------
Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi dibidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari-hari.
Dalam studi kasus ini kami menganalisis kebutuhan suatu sekolah didaerah Pekanbaru. Kasus yang kami peroleh pembuatan laporan penerimaan siswa baru. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan sekolah dengan menerapkan sistem informasi penerimaan siswa baru SMP Al-Azhar Syifa Budi Pekanbaru II . Sehingga memudahkan dalam menginputkan data-data calon siswa. Software yang kami buat ini berbasis website dimana website sebagai admin, panitia PSB dan calon siswa. Sistem yang kami buat di dalamnya terdapat berikut adalah sistem penerimaan Al-Azhar:
1. Pendaftaran Online
2. Proses seleksi
3. Pengumuman Hasil
4. Proses Registrasi
5. Orientasi Siswa Baru
6. Pemantauan Akademik
7. Bimbingan dan Konseling
8. Pembaruan Informasi
9. Keamanan Data

Berikut ini fungsi user dalam bentuk grafik :

1. Isi biodata
2. 
3. 
4. 

2.1 Perspektif Produk
----------
Sistem Informasi Penerimaan Siswa Baru adalah sebuah sistem administrasi data yang diaplikasikan pada website. Terdapat 2 jenis yaitu panitia PSB dan calon siswa. Pengolahan data di kelola oleh panitia PSB pada website dan calon siswa hanya bisa melakukan pendaftaran dan registrasi pembayaran.
Pada sistem informasi penerimaan siswa baru ini akan menampilkan grafik penerimaan siswa yang sudah diinputkan oleh calon siswa.

**2.1.1 Antarmuka Sistem**
![enter image description here](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/UseCaseSistemInformasiPenerimaanSiswaBaru.jpg)
Sistem informasi penerimaan siswa baru SMP Al-Azhar Syifa Budi Pekanbaru II memiliki 2 user yaitu panitia PSB dan calon siswa. Panitia PSB mempunyai fungsi yaitu melakukan view grafik, bisa view laporan, mengelola data. Calon siswa untuk melakukan pendaftaran dan registrasi.

**2.1.2 Antarmuka Pengguna**

**2.1.3 Antarmuka Perangkat Keras**
![enter image description here](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/antarmukaperangkatkeras.drawio.png)
Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka Perangkat Lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Informasi Penerimaan Siswa Baru SMP AL-Azhar Syifa Budi Pekanbaru II antara lain :
1. Kabel Lan UTP RJ45
2. Modem
3. Wifi

**2.1.6 Batasan memori**

Tidak ada

**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses aplikasi atau website|
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak bukti pendaftaran |

**2.1.8 Kebutuhan adaptasi**

Tidak ada

2.2 Spesifikasi Kebutuhan fungsional
------------
  
**2.2.1 Panitia PSB Login**

Use Case : Login

Diagram :
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Untitled%20Diagram.drawio%20(1).png)

Deskripsi Singkat
Panitia PSB memerlukan login terlebih dahulu sebelum masuk ke tampilan home, apabila tidak dapat mengakses atau gagal, Panitia PSB dapat mencoba lagi atau mengatur ulang kata sandi jika perlu.

Deskripsi langkah-langkah
1. Panitia PSB membuka halaman login sistem.
2. Panitia PSB memasukkan username dan password mereka.
3. Sistem memeriksa kecocokan informasi login yang dimasukkan dengan data yang ada di basis data.
4. Jika informasi login benar, sistem memberikan akses penuh ke fitur dan fungsi khusus yang hanya dapat diakses oleh panitia PSB.

Xref: Bagian 3.2.1, Login Panitia PSB

**2.2.2 Panitia PSB mengelola verifikasi dokumen**

Use Case : Mengelola verifikasi dokumen

Diagram :
![](https://github.com/denisaruthdiani/Sistem-Informasi-Penerimaan-Siswa-Baru/blob/main/Usecase-Page-2.jpg)

Deskripsi Singkat
Panitia Penerimaan Siswa Baru (PSB) mengelola verifikasi dokumen yang diajukan oleh calon siswa sebagai bagian dari proses pendaftaran. Tujuannya adalah untuk memeriksa dan memvalidasi dokumen-dokumen yang diterima dari calon siswa.

Deskripsi langkah-langkah
1. Panitia PSB memilih opsi "Mengelola Verifikasi Dokumen" dalam antarmuka sistem.
2. Sistem menampilkan daftar calon siswa yang telah mengajukan dokumen pendaftaran.
3. Panitia PSB memilih calon siswa yang akan diperiksa dokumennya.
4. Panitia PSB memeriksa dokumen yang diajukan oleh calon siswa, seperti akte kelahiran, rapor sekolah, dan dokumen lainnya.
5. Panitia PSB memutuskan apakah dokumen tersebut lengkap, valid, dan memenuhi persyaratan penerimaan.
6. Sistem mencatat hasil verifikasi dokumen dan status calon siswa yang bersangkutan.

Xref: Bagian 3.2.2, Mengelola Verifikasi Dokumen

**2.2.3 Calon Siswa login**


**2.2.4 Calon Siswa input data kependudukan**

**2.2.5 Admin melihat data kependudukan**

**2.2.6 Generate Laporan**

**2.2.7 Admin mengelola user**

2.3   Spesifikasi Kebutuhan non-fungsional
--------------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platform OS 
  
2.4   Karakteristik pengguna
--------------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem dan bisa juga dengan secara langsung tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). 
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.
  
2.6   Asumsi-asumsi
----------
Maksimal penginputan ukuran gambar pada website ini adalah 2048 MB, lebih dari itu program akan muncul peringatan "Anda telah melebihi batas maksimum".

2.7   Kebutuhan Penyeimbang
----------
Tidak ada

BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakses aplikasi ini yaitu dengan hak akses yang di berikan oleh panitia PSB, login melalui website ini dengan membuat akun dengan informasi pribadi dan mengisi formulir pendaftaran. Setelah login berhasil, calon siswa dapat melihat status pendaftaran mereka setelah pendaftaran.
   
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1

**3.2.1 Kepala desa Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Kepala desa |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman login |
| Basic Path | 1. Kepala desa mengisi form login dengan username dan password <br> 2.Kepala desa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Kepala desa dapat login dan mengakses aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbene |
| Exception Push | Username dan password salah |
      
**3.2.2 Kepala desa melihat laporan kependudukan**

|  |  |
|--|--|
| Nama Fungsi | View laporan kependudukan |
| Xref | Bagian 2.2.2, View laporan kependudukan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Membuka halaman grafik kependudukan |
| Basic Path | 1. Kepala desa mengklik navbar laporan <br> 2. Sitem akan menampilkan combobox pilihan bulan dan tahun <br>3. Kepala desa memilih combobox tersebut dan klik tombol lihat <br> 4. Sistem akan menampilkan hasil laporan. |
| Alternative | Tidak ada |
| Post Condition | Kepala desa melihat laporan kependudukan |
| Exception Push | Tidak ada koneksi |
   
**3.2.3 Admin login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.3, Login admin |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman login admin |
| Basic Path | 1. Admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin berhasil login dan mengakses aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Exception Push | Username dan password salah |
   
**3.2.4 Admin input data kependudukan**

|  |  |
|--|--|
| Nama Fungsi | Input data kependudukan |
| Xref | Bagian 2.2.4, Input data kependudukan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman utama admin |
| Basic Path | 1. Admin melakukan input data kependudukan, pekerjaan, agama, pendidikan dan lain-lain <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menyimpan data kependudukan <br> 4. Bila data sudah ada sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data kependudukan |
| Exception Push | Tidak ada koneksi |
   
**3.2.5 Admin melihat data kependudukan**

|  |  |
|--|--|
| Nama Fungsi | View data kependudukan |
| Xref | Bagian 2.2.5, View data kependudukan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman form input data |
| Basic Path | 1. Sistem akan menampilkan data kependudukan desa Lohbener. <br> 2. Admin melihat data dan dapat mengedit atau menghapusnya. <br> 3. Sistem menampilkan edit data kependudukan <br>4. Admin  mengedit data kependudukan yang baru atau yang sudah ada<br>5. Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan|
| Alternative | Tidak ada |
| Post Condition | Halaman data kependudukan |
| Exception Push | Tidak ada koneksi |
   
**3.2.6 Cetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.6, Cetak Laporan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | halaman utama admin |
| Basic Path | 1. Admin mengklik tombol laporan <br> 2. Sistem menampilkan laporan kependudukan <br> 3. Admin memilih combobox tersebut dan klik tombol lihat <br>4. Sistem akan menampilkan hasil laporan. <br>5. Admin mencetak laporan  |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.7  Admin mengelola user**

|  |  |
|--|--|
| Nama Fungsi | Mengelola user |
| Xref | Bagian 2.2.7, Mengelola user |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener | 
| Precondition | halaman utama admin |
| Basic Path | 1. Sistem menampilkan form.<br>2. Admin mengisi form user dengan jabatan, tanggal mulai, tanggal berakhir, dll kemudian klik tombol simpan.<br>3. Sistem akan menyimpan data user ke database.  |
| Post Condition | Halaman user |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/erd_proyek2.png)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| int | Nomer auto increment Id_user|
| Username | varchar | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |
| level | varchar | untuk membedakan level saat login antara admin dan user

**Tabel Warga**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| NIK | varchar | nomer kependudukan|
| Nama | varchar | nomer kependudukan|
| jns_kelamin | varchar | Identifikasi jenis kelamin|
| Tgl_lahir | date | tanggal lahir peserta |
| Agama | varchar | Identifikasi agama |

**Tabel Pegawai**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pegawai| int | Nomer auto increment Id_bioadmin|
| Id_user| int | untuk mengambil username dan password admin pada tabel user|
| nik| varchar | nik admin|
| jabatan | varchar | mendefinisikan level user |
| tgl_masuk | date | awal jabatan|
| tgl_keluar | date | akhir jabatan|

**Tabel Kelahiran**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kelahiran| int | Nomer auto increment Id_kelahiran|
| Id_warga| int | foreignt key tabel warga |
| tgl_lahir| date | tanggal lahir anak |
| jns_kelamin| varchar | jenis kelamin anak|
| ayah | varchar | nama ayah|
| ibu | varchar | nama ibu|
| tmp_lahir| varchar | tempat lahir anak |
| rt | int | nomor rt|
| rw | int | nomor rw|

**Tabel Kematian**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kematian| int | Nomer auto increment Id_kematian|
| Id_warga| int | foreignt key tabel warga |
| tmp_kematian| varchar | tempat lahir anak |
| tgl_kematian| date | tanggal lahir anak |
| rt | int | nomor rt|
| rw | int | nomor rw|

**Tabel Pekerjaan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pekerjaan| int | Nomer auto increment Id_pekerjaan|
| Id_warga| int | foreignt key tabel warga |
| pekerjaan| varchar | pekerjaan masyarakat  |
| tgl_input | date | tanggal input pekerjaan |

**Tabel Pendidikan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pendidikan| int | Nomer auto increment Id_pendidikan|
| Id_warga| int | foreignt key tabel warga |
| pendidikan| varchar | pendidikan masyarakat  |
| tgl_masuk | date | tanggal masuk pendidikan |

**Tabel ktp**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_ktp| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_ktp| varchar | Identifikasi memiliki atau belum memiliki ktp |
| masa_berlaku | date | tanggal berlaku ktp |

**Tabel kk**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kk| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| kepala_keluarga| varchar | nama kepala keluarga |
| no_kk | varchar | nomor kk |

**Tabel pindah**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pindah| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| tgl_pindah | date | tanggal akan pindah |
| ket | varchar | alamat pindah |

**Tabel datang**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_datang| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| tgl_datang | date | tanggal kedatangan |
| ket | varchar | alamat sebelum datang |

**Tabel pilih**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pilih| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_pilih | varchar | hak pilih |

**Tabel kawin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kawin| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_kawin | varchar | status warga |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| int | Nomer auto increment Id_laporan|
| Id_warga| int | foreignt key tabel warga |
| laporan | varchar | berisi laporan kependudukan |

**Tabel Agama**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_agama| int | Nomer auto increment Id_laporan|
| Id_warga| int | foreignt key tabel warga |
| agama| varchar | berisi agama penduduk |



