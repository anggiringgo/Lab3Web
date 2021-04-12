# Lab3Web
# Lab3Web - Praktikum 3

# **MEMBUAT LIST DI HTML**
## 1. Membuat Dokumen HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat List</h1>
</header>
</body>
</html>
```

![Screenshot (36)](https://user-images.githubusercontent.com/81921974/114421261-5326dc00-9bdf-11eb-8b81-1c60b132f33a.png)

## 2. Membuat Ordered List

Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.

```
<section id="order-list">
<h2>Ordered List</h2>
<ol>
<li>Pemrograman Web</li>
<li>Sistem Informasi</li>
<li>Basis Data 2</li>
</ol>
</section>
```
![Screenshot (37)](https://user-images.githubusercontent.com/81921974/114423339-4acfa080-9be1-11eb-8832-612ceb624eac.png)
![Screenshot (38)](https://user-images.githubusercontent.com/81921974/114423579-81a5b680-9be1-11eb-80f0-4f75991db919.png)

## 3. Membuat Unordered List

Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada section unordered-list, seperti berikut.
```
<section id="unorder-list">
<h2>Unordered List</h2>
<ul type="square">
<li>Jaringan Komputer</li>
<li>Struktur Data</li>
<li>Algoritma &amp; Pemrograman</li>
</ul>
</section>
```
![Screenshot (39)](https://user-images.githubusercontent.com/81921974/114423833-c29dcb00-9be1-11eb-9ecd-40f8249c9f27.png)
![Screenshot (40)](https://user-images.githubusercontent.com/81921974/114423839-c5002500-9be1-11eb-83fe-7bfaf05a086c.png)

## 4. Membuat Description List

Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
```
<section id="unorder-list">
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
```
![Screenshot (41)](https://user-images.githubusercontent.com/81921974/114424111-0395df80-9be2-11eb-8433-a5989eba8288.png)
![Screenshot (42)](https://user-images.githubusercontent.com/81921974/114424123-05f83980-9be2-11eb-985f-50d50bc68119.png)

# **MEMBUAT TABLE DI HTML**
## 1. Membuat Dokumen Di HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Table</h1>
</header>
</body>
</html>
```
## 2. Menambahkan Kode Pada Dokumen
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
```
<table border="1" cellpadding="4" cellspacing="0">
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
<td>Teknik</td>
<td>Teknik Informatika</td>
</tr>
<tr>
<td>2.</td>
<td>Teknik</td>
<td>Teknik Industri</td>
</tr>
<tr>
<td>3.</td>
<td>Teknik</td>
<td>Teknik Lingkungan</td>
</tr>
</tbody>
</table>
```
![Screenshot (45)](https://user-images.githubusercontent.com/81921974/114424749-9fbfe680-9be2-11eb-89da-2b0730bc3108.png)
![Screenshot (46)](https://user-images.githubusercontent.com/81921974/114424762-a2224080-9be2-11eb-9e11-11865a07d9ef.png)

## 3. Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan cellspacing pada tag table.
**```<table border="1" cellpadding="4" cellspacing="0">```**
![Screenshot (46)](https://user-images.githubusercontent.com/81921974/114424762-a2224080-9be2-11eb-9e11-11865a07d9ef.png)

## 4. Menggabungkan Sel Data
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara horizontal).
```
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
```
![Screenshot (50)](https://user-images.githubusercontent.com/81921974/114425595-6b98f580-9be3-11eb-97f3-710664611e4f.png)

# **MEMBUAT LIST DI HTML**
## 1. Membuat Form
Buat file baru dengan nama lab3_form.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Form</h1>
</header>
</body>
</html>
```
## 2. Memasukan Kode Untuk Membuat Tabel
```
<form action="proses.php" method="post">
<fieldset>
<legend>Data Pelanggan</legend>
<p>
<label for="nama">Nama</label>
<input type="text" id="nama" name="nama">
</p>
<p>
<label for="alamat">Alamat</label>
<textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
</p>
<p>
<label>Jenis Kelamin</label>
<input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
<input id="jk_p" type="radio" name="kelamin" value="P" /><label
for="jk_p">Perempuan</label>
</p>
<p><input type="submit" value="Login"></p>
</fieldset>
</form>
```
![Screenshot (51)](https://user-images.githubusercontent.com/81921974/114425809-a0a54800-9be3-11eb-8804-e4ece68304cd.png)
![Screenshot (52)](https://user-images.githubusercontent.com/81921974/114425822-a307a200-9be3-11eb-8bfa-ff8ea7dedc3e.png)

## 3. Menambahkan Style pada Form
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
```<style>
form p > label {
display: inline-block;
width: 100px;
}
form input[type="text"], form textarea {
border: 1px solid #197a43;
}
form input[type="submit"] {
border: 1px solid #197a43;
background-color: #197a43;
color: #ffffff;
font-weight: bold;
padding: 5px 15px;
}
</style>
```
![Screenshot (53)](https://user-images.githubusercontent.com/81921974/114426063-e19d5c80-9be3-11eb-97c4-ea89c07a66b9.png)
![Screenshot (54)](https://user-images.githubusercontent.com/81921974/114426077-e3ffb680-9be3-11eb-9f9a-e207f5ea7b86.png)



# Pertanyaan dan Tugas
## 1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
**Memasukan kode dibawah pada dokumen.**
```
<p>Pilih Agama:</p>
         <select>
        <option nama="agama" value="Islam">Islam</option>
        <option nama="agama" value="Kristen">Kristen</option>
        <option nama="agama" value="Budha">Budha</option>
        <option nama="agama" value="Hindu">Hindu</option>
        </select>
        <p>Pilih Jurusan:</p>
        <select name="Jurusan" size="3">        
         <option value="1">Teknik Informatika</option>        
        <option value="2">Manajemen</option>        
        <option value="3">Arsitek</option>        
        <option value="4">Teknik Lingkungan</option>        
        <option value="5">Sistem Informatika</option>        
         </select> 
```
![Screenshot (55)](https://user-images.githubusercontent.com/81921974/114426540-60929500-9be4-11eb-8f0d-6fb8355d5368.png)
![Screenshot (56)](https://user-images.githubusercontent.com/81921974/114426547-625c5880-9be4-11eb-8d78-65397e2004a0.png)
