## Nama     : Ahmad Alfian Chandra
## NIM      : 312010336
## Kelas    : TI.20.A.2
## Matkul   : Pemograman Web

## Pertemuan 11 Lab 9 Web Praktikum 9 <b>

Di pertemuan 11 ini kita akan mempelajari tentang PHP Modular

## Langkah - langkah Praktikum

## 1. Menjalankan XAMPP SERVER 

![1](https://user-images.githubusercontent.com/101621068/170316591-9b2d7261-33a7-4493-81c9-9a1e675eb5b9.png)

## 2. Membuat Folder Baru Bernama lab9_php_modular sebagai berikut :

![2](https://user-images.githubusercontent.com/101621068/170317051-ed2e9883-2e18-4050-8a7f-21405872b92b.png)

Setelah membuat Folder pada Localhost server dengan mengakses URL :
http://localhost/lab9_php_modular/

![3](https://user-images.githubusercontent.com/101621068/170317382-2438ab9b-c0ac-4f18-a950-6af4924da83c.png)

## 3. Membuat File Baru Bernama header.php

Code Header :
```mysql
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet"
media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
        </nav>
```

Dan berikut contoh gambarnya

![4](https://user-images.githubusercontent.com/101621068/170317867-0f50fb94-7a04-4160-95f7-ea014a77f62e.png)

## 4. Membuat File Baru Bernama footer.php

Code Footer :
```mysql
            <footer>
                <p>&copy; 2022, Informatika, Universitas Pelita Bangsa</p>
            </footer>
    </div>
</body>
</html> 
```

Dan berikut contoh gambarnya

![5](https://user-images.githubusercontent.com/101621068/170318193-106ea59c-a868-442c-92cf-a41efd5f2a4d.png)

## 5. Membuat File Baru Bernama home.php

Code Home :
```mysql
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

Dan berikut contoh gambarnya

![6](https://user-images.githubusercontent.com/101621068/170318465-1c400e26-2302-472e-a648-30eb5bfa95e2.png)

## 6. Membuat File Baru Bernama about.php

Code About :
```mysql
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

Dan berikut contoh gambarnya

![7](https://user-images.githubusercontent.com/101621068/170318720-c1a8b0bc-d7e0-4e75-b554-70e6fde4461c.png)

## 7. Tampilan Di Browsernya

Tampilan Home Page pada Browser yang menggunakan modular deader dan footer.

![8](https://user-images.githubusercontent.com/101621068/170319170-675c977a-5209-4547-bae1-a8a4f0d30aa5.png)

![9](https://user-images.githubusercontent.com/101621068/170320626-a9bfc540-b989-4330-9a1f-1176732505c6.png)

# TERIMAKASIH