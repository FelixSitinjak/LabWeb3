# Nama : Felix Amon Sitinjak
# NIM : 312410063
# Kelas : TI.24.A1

**1.Membuat dokumen HTML file lab3_list.html**

<img width="959" height="500" alt="image" src="https://github.com/user-attachments/assets/335c04e3-b073-4719-b3f6-7219bbbf6761" />

**Code**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan - List</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>

    <!-- Ordered List -->
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol type="A" start="D">
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data 2</li>
        </ol>
    </section>

    <!-- Unordered List -->
    <section id="unorder-list">
        <h2>Unordered List</h2>
        <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
        </ul>
    </section>

    <!-- Description List -->
    <section id="desc-list">
        <h2>Description List</h2>
        <dl>
            <dt>Fakultas Teknik</dt>
            <dd>Teknik Industri</dd>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Lingkungan</dd>
            <dt>Fakultas Ekonomi dan Bisnis</dt>
            <dd>Akuntansi</dd>
            <dd>Manajemen</dd>
            <dd>Bisnis Digital</dd>
        </dl>
    </section>
</body>
</html>
```

**Penjelasan**
# Praktikum Web - Lab 3: Membuat List di HTML

## Deskripsi
Project ini merupakan latihan pada Lab 3 mata kuliah Pemrograman Web yang berfokus pada pembuatan berbagai jenis **list (daftar) di HTML.  
File utama: `lab3_list.html`

---

## Tujuan Pembelajaran
- Memahami perbedaan antara Ordered List Unordered List, dan Description List.  
- Mampu mengimplementasikan atribut tambahan seperti `type` dan `start` pada tag `<ol>` dan `<ul>`.  
- Menyusun data secara terstruktur menggunakan elemen list dalam halaman web.

**2.Membuat dokumen HTML file lab3_tabel.html**

<img width="958" height="494" alt="image" src="https://github.com/user-attachments/assets/5774288a-82ee-4697-a7bf-843e4c77bcf2" />

**Code**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan - Table</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>

    <table border="1" cellpadding="6" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

**Penjelasan**
# Praktikum Web - Lab 3: List dan Table HTML

## Deskripsi
Repository ini berisi hasil praktikum **Pemrograman Web (Lab 3)** yang berfokus pada pembuatan **List (Daftar)** dan **Table (Tabel)** menggunakan HTML5.  
Tujuan dari praktikum ini adalah memahami cara menampilkan data dalam bentuk **daftar terstruktur** dan **tabel** dengan berbagai atribut HTML.

