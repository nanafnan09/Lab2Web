# Lab2Web

Nama: Afnan Dika Ramadhan

NIM: 312410518

Kelas: TI24.A5

Mata Kuliah: Pemrograman Web

# Step 1

buatkan terlebih dahulu htmlnya
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/code1.png)

# Hasil dari Step 1

ini adalah tampilan awal sebelum di edit
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/1.png)

# Step 2

lalu tambahkan deklarasi CSS internal
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/after%20code%201.png)

# Hasil dari Step 2

deklarasi CSS internal tersebut akan membuat heading "CSS Internal dan inline CSS" "Hello Word" teks tersebut menjadi di posisi tengah dan berwarna biru
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/after%201.png)

# Step 3

lalu menambahkan inline CSS,fungsi ini akan text tersebut membuat posisinya menjadi ke tengah dan berubah warna menjadi abu
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/2.png)

# Hasil dari Step 3

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/after%202.png)

# Step 4

CSS EKSTERNAL fungsi padaa kode dibawah ini membuat bar warna hijau pada fungsi hyperlink tersebut
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/css.png)

Lalu ``<link>`` untuk menghubungkan ke file css ke html sebelumnya
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/after%20code%203.png)

# Hasil dari Step 4

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/after%203.png)

# Step 5

CSS selector ini berfungsi sebagai menambahkan elemen pada background untuk menambahkan warna 
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/css%201.png)

# Hasil dari Step 5

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/d2b7a5551f9a31c877da66f3285facb66d1bfabb/after%204.png)



# SOAL

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( ``<p id="paragraf-1" class="text-paragraf">`` )

# Jawaban

**1**.Header (h1): Warna biru pada teks "CSS Internal Inline CSS" berasal dari Internal CSS.

Navigasi: Latar belakang hijau tua dan teks putih di bilah navigasi ("CSS Dasar", "CSS Eksternal", "HTML Dasar") adalah hasil dari External CSS (nav selector).

Kotak Biru (ID Selector): Latar belakang biru muda pada kotak yang berisi ``"Hello Word"`` adalah hasil dari External CSS (``#intro selector``).

Tombol Merah (Class Selector): Tautan "Informasi Selengkapnya" berwarna merah adalah hasil dari External CSS (``.btn-primary selector``).

**2.** ``h1`` di Header: Teks "CSS Internal Inline CSS" berwarna biru tua (dari Internal CSS).

h1 di dalam #intro: Teks "Hello Word" berwarna putih dan rata kiri (terlihat rata tengah, namun ini karena paragraf di bawahnya, seharusnya rata kiri sesuai kode #intro h1 di External CSS).

Ini menunjukkan bahwa #intro h1 berhasil menimpa gaya dari h1 di Internal CSS untuk judul yang berada di dalam kotak biru, membuktikan bahwa ID descendant selector lebih spesifik dan menang.

**3.**![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/80ab50b7b012b00fa97f1e180cccfc2c25d3c554/Cuplikan%20layar%202025-10-01%20212647.png)

Kedua gaya ini (``color: #ccd8e4; dan text-align: center;``) berasal dari Inline CSS pada tag <p> di HTML. Jika ada External atau Internal CSS yang mengatur warna atau perataan elemen ``<p>``, Inline CSS tetap menang,dan hasil yang Anda lihat di foto adalah bukti visualnya.

**inilah yang akan terlihat**

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/80ab50b7b012b00fa97f1e180cccfc2c25d3c554/Cuplikan%20layar%202025-10-01%20212921.png)

**4** Apabila pada sebuah elemen HTML terdapat ID dan Class, dan masing-masing selector tersebut terdapat deklarasi CSS untuk properti yang sama, maka deklarasi dari ID Selector yang akan ditampilkan pada browser.

Penjelasan: Hierarki Spesifisitas (Specificity)
Prioritas dalam CSS ditentukan oleh Spesifisitas atau tingkat kekhususan. ID Selector memiliki tingkat kekhususan yang jauh lebih tinggi daripada Class Selector, sehingga ia memenangkan konflik gaya.

ID Selector (``#id-name``): Memiliki nilai Spesifisitas 100 Poin.

Class Selector (.class-name): Memiliki nilai Spesifisitas 10 Poin.

Karena 100 > 10, browser akan selalu mengutamakan aturan dari ID Selector

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/80ab50b7b012b00fa97f1e180cccfc2c25d3c554/jawaban%20code%20no%204.png)

**Hasilnya**

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/80ab50b7b012b00fa97f1e180cccfc2c25d3c554/jawaban%20%20hasil%20no%204.png)





