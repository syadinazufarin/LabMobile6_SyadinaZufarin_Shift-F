# LabMobile6_SyadinaZufarin_Shift-F
### Kode lengkap ada di Google Drive : 
https://drive.google.com/drive/folders/1V64ycFWDrNqunB9tuaEp5OkIVCtfMEH1?usp=sharing

### Penjelasan Proyek :
Proyek ini menambahkan komponen ionic card dan ionic select. 
Berikut adalah penjelasan singkat tentang komponen **`ion-card`** dan **`ion-select`** dalam Ionic:

### 1. Komponen `ion-card`

**`ion-card`** adalah komponen dalam Ionic yang berfungsi untuk menampilkan informasi dalam bentuk kartu, seperti nama, gambar, atau deskripsi. Kartu ini sering digunakan untuk menampilkan data yang berkelompok, seperti daftar profil atau produk, dengan tampilan yang rapi dan mudah dibaca. Kartu dapat berisi komponen lain, seperti header (`ion-card-header`), konten (`ion-card-content`), dan footer.

**Cara menambah `ion-card`:**
- Buka file HTML halaman (misalnya, `student.page.html`).
- Tambahkan elemen `<ion-card>`, dan masukkan informasi yang ingin ditampilkan di dalamnya.

### 2. Komponen `ion-select`

**`ion-select`** adalah dropdown menu dalam Ionic yang memungkinkan pengguna memilih satu atau beberapa opsi dari daftar. `ion-select` sangat cocok untuk membuat pilihan seperti kategori, filter, atau, seperti dalam contoh ini, jurusan mahasiswa.

**Cara menambah `ion-select`:**
- Tambahkan elemen `<ion-select>` di halaman yang sesuai.
- Gunakan atribut `[(ngModel)]` untuk menghubungkannya ke variabel data di TypeScript, dan masukkan opsi di dalam elemen `ion-select-option`.


### Langkah Menambahkan `ion-card` dan `ion-select`

1. **Membuat Halaman HTML**: Buka halaman HTML yang akan menggunakan komponen (dalam proyek ini yaitu file: `student.page.html`).
2. **Tambahkan Kode `ion-card`**: Letakkan elemen `<ion-card>` untuk setiap item atau grup informasi yang ingin ditampilkan dalam bentuk kartu.
3. **Tambahkan `ion-select` dalam `ion-card` atau `ion-item`**: Di dalam kartu atau item, tambahkan elemen `<ion-select>` untuk membuat dropdown pilihan jurusan.

### Langkah Membuat Proyek Ionic ini, sebagai berikut :

1. **Membuat Halaman Baru**: Jalankan perintah `ionic generate page student` di terminal untuk membuat Folder `StudentPage`. Ini akan menghasilkan file `student.page.html`, `student.page.scss`, dan `student.page.ts`.

2. **Siapkan Data Mahasiswa**: Buka file `student.page.ts`, lalu buat data mahasiswa (seperti nama dan NIM) serta daftar pilihan jurusan. Serta, Fungsi untuk memperbarui jurusan mahasiswa saat dipilih.

3. **Membuat Tampilan di HTML**: Buka `student.page.html` dan buat tampilan daftar mahasiswa menggunakan komponen Ionic, untuk proyek ini menggunakan `ion-card` untuk menampilkan informasi mahasiswa dan `ion-select` untuk dropdown jurusan. Setiap mahasiswa bisa memilih jurusan dari daftar yang ada.

4. **Membuat File CSS**: Buka file `student.page.scss` untuk menambahkan warna pastel agar tampilan lebih menarik. Untuk proyek ini menggunakan warna pink pastel. 

5. **Melakukan Konfigurasi Routing**: Buka `app-routing.module.ts` dan tambahkan rute ke halaman `StudentPage` agar halaman ini bisa diakses. Halaman `StudentPage` di set sebagai halaman utama agar dapat langsung ditampilkan saat aplikasi dibuka.

6. **Tambahkan Modul yang Diperlukan**: Buka `app.module.ts` dan pastikan `FormsModule` sudah ditambahkan untuk mendukung input data di form. Pastikan juga `StudentPage` terdaftar sebagai salah satu halaman yang ter- detect aplikasi.

7. **Jalankan Aplikasi**: Setelah semua langkah selesai, gunakan perintah `ionic serve` untuk menjalankan aplikasi.
   
### Screenshoot Aplikasi :

![Screenshot Halaman Utama](assets/Halaman%20Utama.png)
![Screenshot Memilih Jurusan](assets/Memilih%20Jurusan.png)
![Screenshot Halaman Akhir](assets/Tampilan%20Akhir.png)



