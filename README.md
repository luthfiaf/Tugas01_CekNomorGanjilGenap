# Tugas01_CekNomorGanjilGenap
 Aplikasi untuk mengecek ganjil atau genap
Muhammad Luthfianur Arifin 2210010213

Aplikasi Cek Nomor Ganjil Genap
Aplikasi ini dibuat untuk mengecek apakah sebuah angka yang dimasukkan oleh pengguna adalah angka genap atau ganjil, serta untuk menentukan apakah angka tersebut merupakan bilangan prima. Aplikasi ini menggunakan Java dengan GUI berbasis Swing.

Fitur
Menentukan apakah angka yang dimasukkan adalah genap atau ganjil.
Mengecek apakah angka tersebut adalah bilangan prima.
Input angka dibatasi hanya untuk angka (numerik).
Menyediakan opsi untuk mengulang input atau keluar dari aplikasi.
Prasyarat
Java Development Kit (JDK) 8 atau versi lebih baru.
IDE seperti NetBeans untuk menjalankan proyek.
Cara Penggunaan
Masukkan Angka:

Pada kolom input, masukkan angka yang ingin diperiksa.
Cek:

Klik tombol Cek untuk mengetahui apakah angka yang dimasukkan genap atau ganjil.
Hasil cek juga akan menampilkan apakah angka tersebut bilangan prima atau bukan.
Ulang:

Klik tombol Ulang untuk mengosongkan kolom input dan hasil yang telah ditampilkan.
Keluar:

Klik tombol Keluar untuk keluar dari aplikasi setelah konfirmasi.
Penjelasan Kode
Struktur Kelas
CekNomorGanjilGenapView:

Merupakan kelas utama yang menangani GUI dan logika aplikasi.
Menampilkan form dengan komponen-komponen untuk memasukkan angka dan menampilkan hasil cek.
Menyediakan tombol Cek, Ulang, dan Keluar.
Metode isPrime(int number):

Fungsi untuk mengecek apakah sebuah angka adalah bilangan prima. Fungsi ini memeriksa angka dengan membagi angka tersebut oleh semua angka yang lebih kecil dari akar kuadratnya.
Penggunaan Event Listener
FocusListener: Mengosongkan kolom input saat fokus dialihkan ke kolom input.
KeyListener: Membatasi input hanya pada angka.
ActionListener: Menangani aksi dari tombol Cek, Ulang, dan Keluar.
Tombol-Tombol:
Cek: Mengambil input dari kolom input dan menampilkan hasil apakah angka genap/ganjil dan bilangan prima.
Ulang: Menghapus teks yang ada di kolom input dan mengatur label hasil kembali ke "Hasil :".
Keluar: Menampilkan dialog konfirmasi sebelum keluar dari aplikasi.

