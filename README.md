# Lab1Web

## Nama     : Muhammad Romdhon
## NIM      : 312010434
## Kelas    : TI.20.A1
## Matkul   : Pemograman web

## Belajar dasar HTML
## Langkah - langkah praktikum

<br> *Assalamu'alaikum Warahmatullahi wabarakatuh* 
<br> Nama saya Muhammad Romdhon disini saya akan menjelaskan cara membuat web  dengan html
<br> pertama siapkan *Visual Studio* Code dan *browser*
![p](gambar/gambar1.png)

<br> Kemudian buat file baru dengan nama **lab1_tag_dasar.html**
![p](gambar/gambar2.png)

<br> Selanjutnya buka file tersebut menggunakan browser. Disini saya menggunakan *Microsoft Edge*
![p](gambar/gambar3.png)

## 1. Membuat Paragraf
<br> Buatlah paragraf sederhana seperti berikut ini. Dan kemudian lihat hasilnya dengan menrefresh pada web browser
![p](gambar/gambar4.png)
![p](gambar/gambar5.png)

<br> Kemudian atur atribut paragraf seperti berikut dan lihat perubahannya
![p](gambar/gambar6.png)
![p](gambar/gambar7.png)

<br> simpan dan refresh web browser untuk melihat perubahannya. Selanjutnya untuk mengubah model paragraf nilai atributnya  (algin = Justify, left, right, dan center) untuk melihat perbdaannya

## 2. Menambahkan Judul 
<br> Judul memiliki 6 level yang berbeda mulai dari h1 sampai h6. kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragrf ke-2
![p](gambar/gambar8.png)
![p](gambar/gambar9.png)

<br> simpan dan lihat perubahannya

## 3. Memformat Teks
<br> Lakukan formatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks sehingga tampilannya akan berbeda seperti berikut.
<br> masukan code teks seperti berikut untuk melihat perubahan.
![p](gambar/gambar10.png)
<br> Dan hasilnya akan seperti ini.
![p](gambar/gambar11.png)

## 4. Menyisipkan Gambar
<br> Untuk menyisipkan gambar, siapkan terlebih dahulu gambar yang ingin dimasukan pada HTML dan sisipkan atau taruh gambar pada suatu folder dengan HTML seperti gambar berikut :
![p](gambar/gambar14.png)
<br> Kemudian tambahkan tag img setelah paragraf kedua, dengan menambahkan Heading 3 sebelumnya seperti berikut :
![p](gambar/gambar12.png)
<br> Gambar akan ditampilkan apa adanya sesuai ukuran. Untuk mengatur ukuran gambar dapat menggunakan atribut `witdh` dan `height` dengan nilai interger yang disesuaikan seperti contoh di atas. Nanti gambar akan seperti berikut ini :
![p](gambar/gambar13.png)

## 5. Menambahkan Hyper Links

<br> Tambahkan Hyperlink pada dokumen sebelum heading 1 seperti gambar berikut : 
![p](gambar/gambar15.png)
<br> Nanti hyperlink akan berada di atas seperti gambar berikut :
![p](gambar/gambar16.png)
 
 <br> Sekian penjelasan dari saya tentang membuat HTML menggunakan *Visual Studio Code* semoga muda di pahami sekian dari saya.
 <br> <p align="center"> **Terima Kasih**

 <br> *Wassalamu'alaikum Warahmatullahi Wabarakatuh*

 ## Jawab pertanyaan berikut 
 <br> 1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag?
<br> 2. Apa perbedaan dari tag < p > dengan tag < br >, berikan penjelasannya!
<br> 3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
<br> 4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
<br> 5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

## Jawaban
<br> 1. Saya akan melakukan perbedaan Tag-tag HTML sebelum dan sesudah perubahan. sebalum perubahan akan seperti gambar berikut ini:
![p](gambar/gambar17.png)
![p](gambar/gambar16.png)
<br> Setelah perubahan gambar akan seperti berikut ini :
![p](gambar/gambar18.png)
![p](gambar/gambar19.png)
<br> Disini saya melakukan perubahan dengan menghilangkan akhiran tag `</h1>` menjadi `<h1>` maka akan terjadi seluruh elemen dibawah tag terebut akan berubah mengikuti tag `<h1>` dikarenakan tidak ada penutup pada tag tersebut.

<br> 2. Tag `<p>` berfungsi untuk memberi perintah paragraf pada HTML. Tag `<br>` berfungsi untuk memberikan perintah breakline atau baris baru, seperti gambar berikut ini:
![p](gambar/gambar20.png)
![p](gambar/gambar21.png)

<br> 3. `title` berfungsi untuk memberikan judul pada gambar, sedangkan `alt` berfungsi untuk deskripsi tentang gambar, seperti gambar dibawah ini menunjukan perbedaan `title` dan `alt`.
![p](gambar/gambar22.png)
![p](gambar/gambar23.png)

<br> 4. Menurut saya tidak harus menggunakan keduanya karena jika menggunakan keduanya dengan ukuran angka yang sama ukuran gambar pada web tidak simetris. sedangkan jika hanya mengunakan salah satu ukurannya akan bertambah besar secara simetris. contoh seperti gambar di bawah berikut ini :
![p](gambar/gambar24.png)
![p](gambar/gambar25.png)

<br> 5. `<_blank>` untuk membuka link di tab baru 
        `<_self>` untuk membuka link di frame link itu berada
        `<_top>` untuk membuka link di frame paling atas (paling luar). contohnya jika website (A) di dalamnya ada website (B) lalu di website (B) di dalamnya ada website (C) lalu di website (C) ini ada link dan kita klik, maka link akan terbuka di websiite (C).
        `<_parent>` untuk membuka link di frame yang satu tingkat di atas frame link tersebu berada. contohnya jika website (A) di dalamnya ada website (B) lalu di website (B) ini ada link dan kita klik, maka link akan terbuka di website (A).