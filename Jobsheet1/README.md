# LAPORAN PRAKTIKUM JOBSHEET 01
**Topik:** Dasar HTML & Sistem Perpustakaan Sederhana  
### 📁STRUKTUR FOLDER
```
Jobsheet-1
   │   index.html
   │   README.md
   │   
   ├───Anggota
   │       list.html
   │       tambah.html
   │       
   └───Buku
           list.html
           tambah.html
```

## Ringkasan
1. index.html (Halaman Utama): 
    * Berfungsi sebagai menu utama yang memiliki tombol untuk membuka halaman data anggota dan data buku.

2. Folder Anggota (Jobsheet 1/anggota/):
   * list.html: Halaman untuk melihat daftar semua anggota yang sudah terdaftar dalam bentuk tabel, lengkap dengan tombol untuk menambah anggota baru.
   * tambah.html: Halaman berisi formulir untuk memasukkan data anggota baru (seperti nomor ID, nama, jenis kelamin, dan program studi).

3. Folder Buku (Jobsheet 1/buku/):
   * list.html: Halaman untuk melihat daftar buku yang ada (seperti kode, judul, pengarang, penerbit, tahun, dan status buku) beserta tombol untuk menambah buku.
   * tambah.html: Halaman berisi formulir untuk memasukkan data buku baru ke dalam sistem.

## Latihan Reflektif
1. Kenapa field "Alamat" dan "No. HP" tidak diberi `required`, sedangkan
   "Nama" dan "No. Anggota" diberi?
        
        Karena field Alamat dan No. HP bersifat opsional atau tidak wajib diisi oleh pengguna, sementara Nama dan No. Anggota adalah data penting yang wajib diisi.

2. Apa yang akan terjadi (di browser) kalau kamu klik tombol "Simpan"
   tanpa mengisi field "Nama"? Coba buka filenya di browser dan praktikkan.

        Browser akan menampilkan pesan peringatan bawaan dan proses pengiriman formulir akan dicegah sampai kolom tersebut terisi

3. Form ini juga **belum punya `action`** pada tag `<form>`-nya — apa
   dampaknya saat tombol "Simpan" ditekan?
        
        Formulir tidak akan dikirimkan ke file pemroses data, sehingga halaman hanya akan melakukan reload ke dirinya sendiri tanpa menyimpan data ke sistem.