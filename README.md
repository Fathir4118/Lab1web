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
4. • Jika hanya salah satu atribut yang diisi (misalnya width="250"), maka browser akan otomatis menyesuaikan proporsi
     tinggi/lebar gambar.
   • Jika dua-duanya diisi, maka gambar bisa jadi terdistorsi jika rasio tidak sesuai dengan ukuran asli gambar.
5. Nilai target menentukan di mana halaman link akan dibuka:
   • _blank → membuka link di tab/jendela baru.
   • _self → default, membuka link di tab yang sama.
   • _top → membuka link di jendela penuh, menimpa semua frame.
   • _parent → membuka link di frame induk (jika ada frame).

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
        <a href="profil.html">Profil Andrean Putra</a> |
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
    href="ttps://ecampus.pelitabangsa.ac.id/pb/">UNIVERSITAS PELITA BANGSA
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

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/0d1dc9756264aa73de3e2dce67416c97de2eed56/images/Screenshot%20from%202025-09-25%2013-11-07.png)

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

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/8c343f6dd573d88b21860bb2e9ceda27a4b9b017/images/Screenshot%20from%202025-09-25%2013-19-43.png)

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

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/6807241faa0760417b55e655659a8f5097d60094/images/Screenshot%20from%202025-09-25%2013-29-29.png)

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

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/38c7b88acc5226ced271120d512e5ba7d72c2ee3/images/Screenshot%20from%202025-09-25%2013-24-55.png)

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
<h3>MENAMBAH![gambar](https://raw.githubusercontent.com/M-Rakha/Lab1Web/73203a1509abda1a5f5ee589aecb49e8db73bf1a/Cuplikan%20layar%202025-09-23%20222251.png)KAN GAMBAR</h3>
    <img src="images/Logo-UPB.png" width="250" 
         title="Logo Universitas Pelita Bangsa" 
         alt="Logo UPB">

    <img src="images/Logoo.jpg" width="250"
        title="Logo Andrean Putra"
        alt="Logoo">

</body>
</html>
```

Simpan perubahannya, kemudian refresh browser.

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/869013dfb5a9820f66a0b3dfbf5158e3ed569b20/images/Screenshot%20from%202025-09-25%2013-33-52.png)

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
        <a href="profil.html">Profil Andrean Putra</a> |
    </nav>
    <hr>
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
    <img src="images/Logo-UPB.png" width="250" 
         title="Logo Universitas Pelita Bangsa" 
         alt="Logo UPB">

    <img src="images/Logoo.jpg" width="250"
        title="Logo Andrean Putra"
        alt="Logoo">

</body>
</html>
```
Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.

![gambar](https://github.com/andreanbadeh/Lab1Web/blob/89e7b0aa02e031d22b25d8e48e812bb227fd0ad6/images/Screenshot%20from%202025-09-25%2013-36-59.png)
