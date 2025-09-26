# MEMBUAT MODUL PRAKTIKUM PEMROGRAMAN WEB

NAMA : MUHAMMAD FATHIR NURCHOLIS

NIM : 312410287

KELAS : TI.24.A.4

MATKUL : PEMROGRAMAN WEB 1


# PERTANYAAN
![image](https://github.com/Fathir4118/Lab1web/blob/main/Gambar/IMG_20250926_074751.jpg) 

# JAWABAN

1. tidak ada error pada program HTML melainkan hanya tidak memunculkan tag yang bermasalah
2. <p> digunakan untuk membuat paragraf baru, otomatis menambahkan spasi atas-bawah.
   <br> digunakan untuk membuat baris baru (line break) tanpa spasi tambahan.
3. alt → teks alternatif yang muncul jika gambar gagal dimuat, serta dibaca oleh screen reader (aksesibilitas).
   title → teks yang muncul sebagai tooltip ketika kursor diarahkan ke gambar.
4. | Jika hanya salah satu atribut yang diisi (misalnya width="250"), maka browser akan otomatis menyesuaikan proporsi
     tinggi/lebar gambar.
   | Jika dua-duanya diisi, maka gambar bisa jadi terdistorsi jika rasio tidak sesuai dengan ukuran asli gambar.
5. Nilai target menentukan di mana halaman link akan dibuka:
   | _blank → membuka link di tab/jendela baru.
   | _self → default, membuka link di tab yang sama.
   | _top → membuka link di jendela penuh, menimpa semua frame.
   | _parent → membuka link di frame induk.

# PRAKTEK

# SOURCE CODE HTML
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
    <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a> |
        <a href="lab1_halaman2.html">Halaman 2</a> |
        <a href="http://www.google.com" target="_blank">Halaman Web Eksternal Google</a> |
        <a href="https://github.com/Fathir4118/Lab1web">Profil Muhammad Fathir Nurcholis</a> |
    </nav>
    <hr>
    <h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA <b>MUHAMMAD FATHIR NURCHOLIS</b> dengan <b>NIM 312410287</b> sedang belajar <mark>HTML dasar</mark>, pada matakuliah 
        <b>Pemrograman Web1</b> di Prodi <i>Teknik Informatika Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
    <h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
    <h3>MENAMBAHKAN GAMBAR</h3>
   
    <img src="https://bloguna.com/wp-content/uploads/2025/08/Logo-Universitas-Pelita-Bangsa-UPB-Format-PNG-CDR-EPS-SVG-PDF-AI-1024x778.png" width="250">
    <p>
    <a
    href="https://ecampus.pelitabangsa.ac.id/pb/">UNIVERSITAS PELITA BANGSA
    </a>
    </p>

</body>
</html>
```

# MODUL PRAKTIKUM PEMROGRANAN WEB SERTA PENJELASAN CODE TERSEBUT

HTML (Hypertext Markup Language) adalah bahasa markup untuk membuat dan menampilkan halaman web. Struktur dasar HTML terdiri dari :
- Document Type Declaration (DOCTYPE) untuk menentukan standar dokumen.
- Header berisi info halaman (judul, meta, CSS, dll.).
- Body berisi isi halaman web.

Contoh pengaplikasiannya : 
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>

</body>
</html>
```

Kemudian selanjutnya, buka file tersebut pada web browser untuk membuktikan hasilnya :

![gambar](https://github.com/Fathir4118/Lab1web/blob/main/Gambar/Screenshot_20250926_081054.jpg)

# 1. MEMBUAT PARAGRAF

Tag HTML adalah kode dalam kurung siku < >. Ada tag pembuka dan penutup, misalnya  ... /p. Beberapa tag tidak punya penutup seperti br/, img/.
Paragraf dan pemisah baris :
- p untuk membuat paragraf.
- br untuk pindah baris.
- hr untuk garis horizontal.

Contoh pengaplikasiannya :
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
<p>SAYA MUHAMMAD FATHIR NURCHOLIS dengan NIM 312410287 sedang belajar HTML dasar, pada matakuliah 
Pemrograman Web1 di Prodi Teknik Informatika Universitas Pelita Bangsa. 
Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
dalam rangka mengenal tag-tag dasar HTML.</p>

<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
saling mendukung sehingga menjadi satu kesatuan. 
Paragraf dibuat dengan menggunakan tag dasar html.</p>
</body>
</html>
```

Kemudian selanjutnya, buka file tersebut pada web browser untuk membuktikan hasilnya :

![gambar](https://github.com/Fathir4118/Lab1web/blob/main/Gambar/Screenshot_20250926_081342.jpg)

# 2. MENAMBAHKAN JUDUL
Seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu mulai h1 sampai h6. Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
<h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA MUHAMMAD FATHIR NURCHOLIS dengan NIM 312410387 sedang belajar HTML dasar, pada matakuliah 
        Pemrograman Web1 di Prodi Teknik Informatika Universitas Pelita Bangsa. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
<h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
</body>
</html>
```
Kemduian simpan, lalu kita liat hasilnya :

![gambar](https://github.com/Fathir4118/Lab1web/blob/main/Gambar/Screenshot_20250926_081539.jpg)

# 3. MEMFORMAT TEKS
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya. Ada beberapa tag yang dapat digunakan untuk memformat teks pada paragraf, sehingga tampilannya seperti berikut.
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
<h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA <b>MUHAMMAD FATHIR NURCHOLIS</b> dengan <b>NIM 312410287</b> sedang belajar <mark>HTML dasar</mark>, pada matakuliah 
        <b>Pemrograman Web1</b> di Prodi <i>Teknik Informatika Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
<h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
</body>
</html>
```
Selanjutnya, mari kita lihat hasilnya :

![gambar](https://github.com/Fathir4118/Lab1web/blob/main/Gambar/Screenshot_20250926_081738.jpg)

# 4. Menyisipkan Gambar
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan gambar dari website external. Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya. Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
<h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA <b>ANDREAN PUTRA ARYA</b> dengan <b>NIM 312410241</b> sedang belajar <mark>HTML dasar</mark>, pada matakuliah 
        <b>Pemrograman Web1</b> di Prodi <i>Teknik Informatika Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
<h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
    <h3>MENAMBAHKAN GAMBAR</h3>
   
    <img src="https://bloguna.com/wp-content/uploads/2025/08/Logo-Universitas-Pelita-Bangsa-UPB-Format-PNG-CDR-EPS-SVG-PDF-AI-1024x778.png" width="250">
    <p>
    <a
    href="https://ecampus.pelitabangsa.ac.id/pb/">UNIVERSITAS PELITA BANGSA
    </a>
    </p>

</body>
</html>
```

Simpan perubahannya, kemudian refresh browser.

![gambar](https://github.com/Fathir4118/Lab1web/blob/main/Gambar/Screenshot_20250926_083520.jpg)

# 5. Menambahkan Hyperlink
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lab1 - Tag Dasar HTML</title>
</head>
<body>
    <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a> |
        <a href="lab1_halaman2.html">Halaman 2</a> |
        <a href="http://www.google.com" target="_blank">Halaman Web Eksternal Google</a> |
        <a href="https://github.com/Fathir4118/Lab1web">Profil Muhammad Fathir Nurcholis</a> |
    </nav>
    <hr>
    <h1>BELAJAR DASAR HTML</h1>
    <p>
        SAYA <b>MUHAMMAD FATHIR NURCHOLIS</b> dengan <b>NIM 312410287</b> sedang belajar <mark>HTML dasar</mark>, pada matakuliah 
        <b>Pemrograman Web1</b> di Prodi <i>Teknik Informatika Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>
    <h2>PARAGRAF PADA HTML</h2>
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang 
        saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar html.
    </p>
    <h3>MENAMBAHKAN GAMBAR</h3>
   
    <img src="https://bloguna.com/wp-content/uploads/2025/08/Logo-Universitas-Pelita-Bangsa-UPB-Format-PNG-CDR-EPS-SVG-PDF-AI-1024x778.png" width="250">
    <p>
    <a
    href="https://ecampus.pelitabangsa.ac.id/pb/">UNIVERSITAS PELITA BANGSA
    </a>
    </p>

</body>
</html>
```
Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.

![gambar](https://github.com/Fathir4118/Lab1web/blob/main/Gambar/Screenshot_20250926_084046.jpg)
