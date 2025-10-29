# lab5web.
# Richie Pranata 
# TI.24.A.5
# 312410451

### Hasil Penjelasan Running 

# form_button.html
Fungsi Utama: Demonstrasi sederhana manipulasi tampilan dasar halaman web (warna latar belakang dan warna teks) menggunakan tombol dan JavaScript.

# Penjelasan
Mengklik "Latar Belakang Hijau" akan menjalankan ubahwarnaLB('GREEN'), yang akan mengubah warna latar belakang halaman menjadi Hijau (document.bgColor = 'GREEN').2. Mengklik "Teks Kuning" akan menjalankan ubahwarnaLD('YELLOW'), yang akan mengubah warna teks default halaman menjadi Kuning (document.fgColor = 'YELLOW').langan ganjil.
Output	Hasil ("bilangan genap" atau "bilangan ganjil") akan ditampilkan di textbox T2.

# function_onload.html
Fungsi Utama: Contoh cara menjalankan fungsi JavaScript secara otomatis segera setelah seluruh konten halaman web selesai dimuat.

# Penjelasan 
Tampilan	Halaman ini akan terlihat kosong (hanya berisi tag <body>).
Interaksi	Segera setelah body halaman selesai dimuat, event onload pada tag <body> akan memanggil fungsi pesan().
Hasil	Sebuah kotak dialog Alert akan muncul di layar dengan pesan: "memanggil javascript lewat body onload".

# ifelse.html
Fungsi Utama: Menunjukkan penggunaan struktur kontrol if-else dalam JavaScript untuk menentukan kelulusan berdasarkan input nilai.

# Penjelasan
InteraksiSegera setelah dimuat, skrip akan menampilkan kotak dialog Prompt yang meminta pengguna memasukkan nilai (antara 0-100) dengan nilai default 0.
Proses Nilai yang dimasukkan pengguna akan diperiksa:* Jika nilai $\ge 60$, variabel hasil diatur menjadi "lulus".* Jika nilai $< 60$, variabel hasil diatur menjadi "tidak lulus".
OutputHasilnya akan ditulis ke halaman web, misalnya: hasil: lulus atau hasil: tidak lulus.

# prompt.html
Fungsi Utama: Contoh sederhana untuk mendapatkan input data dari pengguna menggunakan kotak dialog Prompt.

# Penjelasan 
Interaksi	Segera setelah dimuat, skrip akan menampilkan kotak dialog Prompt yang meminta: "siapa nama anda?" dengan teks default "masukan nama anda".
Output	Teks yang dimasukkan pengguna akan disimpan di variabel nama, dan kemudian ditulis ke halaman web dengan format: hai, [nama yang dimasukkan].

# switch.html
Fungsi Utama: Demonstrasi penggunaan pernyataan switch untuk memproses input pengguna.

# Penjelasan 
Tampilan	Menampilkan satu tombol dengan nilai "switch".
Interaksi	Mengklik tombol akan memanggil fungsi test().
Proses	Fungsi test() akan menampilkan kotak dialog Prompt yang meminta input nilai (1-5).
Output	Berdasarkan input, skrip akan menuliskan:
* "bilangan satu" jika input adalah "1".
* "bilangan dua" jika input adalah "2".
* ... dan seterusnya hingga "bilangan lima".
* Jika input bukan 1, 2, 3, 4, atau 5, maka akan ditulis "bilangan lainnya".

# form_input.html
Fungsi Utama: Program kecil untuk memeriksa apakah bilangan yang dimasukkan pengguna adalah genap atau ganjil menggunakan form dan operator modulo (%).

# Penjelasan 
Tampilan	Menampilkan form dengan dua textbox (T1 untuk input bilangan dan T2 untuk hasil) dan satu tombol "TEBAK".
Interaksi	Mengklik tombol "TEBAK" akan memanggil fungsi test().
Proses	Fungsi test() mengambil nilai dari textbox T1.
* Jika nilai tersebut dimodulo 2 hasilnya 0 (val1 % 2 == 0), maka nilai tersebut adalah bilangan genap.
* Jika tidak (sisanya 1), maka nilai tersebut adalah bilangan ganjil.
Output	Hasil ("bilangan genap" atau "bilangan ganjil") akan ditampilkan di textbox T2.
