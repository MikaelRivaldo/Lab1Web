# Tugas
1. Buatlah repository baru dengan nama Lab1Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus.

# Pertama buatlah sebuah file dan masukan code seperti dibawah ini  :
![gambar 1](https://github.com/MikaelRivaldo/Lab1Web/assets/115770247/17581abe-a79b-4566-931e-fe4d6bce3475)

`Lalu simpan file tersebut dengan shourcut CTRL+S,setelah disimpan buka dokumen dan klik kanan pada folder htmlnya,lalu klik open with dengan browser kesukaan kalian.seperti contoh Mozila,Crohome,dan Edge`

`Seperti gambar dibawah ini`

![tampilan web browser](https://github.com/MikaelRivaldo/Lab1Web/assets/115770247/5baf13a7-75db-4589-907f-ce798698ae5e)



# Selanjutnya Membuat Paragraf

`Selanjutnya buatlah paragraf sederhana sebagai berikut  :`

```html
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
tag dasar html.</p>
```
`Dan untuk hasilnya akan seperti ini  :`

![tampilan perubahan paragraf](https://github.com/MikaelRivaldo/Lab1Web/assets/115770247/491bad00-4790-4aad-bba0-da314d7503a3)

`Selanjutnya atur atribut paragraf dan Menambahkan Judul seperti berikut  :`

```html
<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
tag-tag dasar HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa
kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
dengan menggunakan tag dasar html.</p>
```
`Dan untuk hasil menambahkan judul dan Atribut paragraf akan seperti ini  :`

![tampilan menambahkan judul](https://github.com/MikaelRivaldo/Lab1Web/assets/115770247/af9334dd-dea6-4cfd-b901-1d09ca7ad278)

`Selanjutnya Memformat tesk`
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada
penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.

`Dan untuk hasilnya akan seperti ini  :`

![tampilan format ](https://github.com/MikaelRivaldo/Lab1Web/assets/115770247/e2fb12ee-6a49-493e-9d2d-c6ce0ad46305)

`Selanjutnya Menisipkan gambar`

Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian
simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan
gambar dari website external.

`Selanjutnya tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3
sebelumnya.menggunakan code seperti dibawah ini  :`

```html
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="Logo_UPB.png" title="Logo Univeritas Pelita Bangsa">

`Dan untuk hasilnya akan seperti ini  :`

![tampilan logo upb](https://github.com/MikaelRivaldo/Lab1Web/assets/115770247/61747416-60f2-4632-a462-8400aa882480)

`Selanjutnya Menambahkan Hyperlink Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut`

```html
<!-- menambahkan link navigasi -->
<nav>
<a href="lab1_tag_dasar.html">Dasar HTML</a>
<a href="lab1_halaman2.html">Halaman 2</a>
<a href="http://www.google.com">Halaman Web Eksternal Google</a>
</nav>
<hr>
```

`Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag
html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya`

`Dan untuk hasilnya akan seperti ini  :`

![tampilan hyperlink](https://github.com/MikaelRivaldo/Lab1Web/assets/115770247/55d2b764-5300-45d1-96ee-e85c0cc32661)

# Jawab Pertanyaan Berikut

2.Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
   
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

# Jawab


2Perbedaan antara tag <p> dan tag <br> adalah sebagai berikut:

`Tag <p> (paragraph) digunakan untuk membuat paragraf teks, dan secara otomatis menambahkan jarak vertikal (baris baru) sebelum dan setelah paragraf. Ini adalah elemen blok dan biasanya digunakan untuk mengelompokkan teks.`

`Tag <br> (line break) digunakan untuk membuat jarak vertikal (baris baru) dalam teks, tetapi tidak membentuk paragraf baru. Ini adalah elemen inline dan digunakan untuk mengatur pemisahan dalam teks, seperti dalam alamat atau stihiran.`

3.Perbedaan antara atribut title dan alt pada tag <img> adalah sebagai berikut:

`Atribut alt: Atribut ini digunakan untuk memberikan teks alternatif untuk gambar. Ini penting untuk aksesibilitas web, karena akan menampilkan teks jika gambar tidak dapat dimuat atau jika pembaca layar digunakan. Teks alternatif ini juga membantu mesin pencari memahami isi gambar.`

`Atribut title: Atribut ini digunakan untuk memberikan judul atau informasi tambahan tentang gambar saat pengguna mengarahkan kursor mouse ke gambar tersebut (tooltip). Ini adalah informasi tambahan dan tidak ditampilkan jika gambar tidak dimuat. Ini dapat membantu dalam memberikan keterangan atau deskripsi singkat tentang gambar.`

4.`Untuk mengatur ukuran gambar agar tampilan gambar proporsional, sebaiknya kedua atribut width dan height diisi. Ini karena ketika hanya satu atribut diisi, gambar mungkin menjadi terdistorsi dan tidak proporsional. Jika Anda hanya mengisi salah satu atribut (misalnya, hanya width atau hanya height), browser akan secara otomatis menghitung nilai atribut yang lain agar gambar tetap proporsional. Tetapi, lebih baik mengisi keduanya dengan nilai yang sesuai agar hasilnya lebih dapat diprediksi dan sesuai dengan desain yang diinginkan.`

5.Atribut target digunakan untuk mengendalikan perilaku hyperlink. Berikut adalah penjelasan untuk nilai-nilai atribut target yang berbeda:

`_blank: Jika menggunakan _blank, tautan akan membuka halaman yang terhubung dalam tab atau jendela browser yang baru. Ini memungkinkan pengguna tetap berada di halaman asal.`

`_self: Ini adalah perilaku default. Jika menggunakan _self, tautan akan membuka halaman yang terhubung di jendela atau tab yang sama di mana tautan itu ada.`

`_top: Jika menggunakan _top, tautan akan membuka halaman yang terhubung di jendela atau tab utama (paling atas) dan menggantikan semua bingkai (frames) jika ada.`

`_parent: Jika menggunakan _parent, tautan akan membuka halaman yang terhubung di jendela atau tab yang menggantikan bingkai (frame) yang berisi tautan tersebut, jika ada bingkai yang digunakan dalam halaman.
Pilihan nilai atribut target ini memberikan kontrol atas cara halaman web yang terhubung dibuka dan memengaruhi pengalaman pengguna.`



