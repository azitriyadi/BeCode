![image](https://github.com/kerjabhakti/PWA231/assets/15622730/77e25b4b-baca-49d1-9662-96a6291ac8bc)

# Framework CSS 
framework CSS adalah seperangkat aturan, pedoman, dan komponen yang telah dibuat sebelumnya yang digunakan dalam pengembangan web untuk merancang tampilan dan tata letak halaman web. 

Framework CSS memudahkan pengembang dalam merancang dan memformat halaman web dengan cepat dan konsisten, serta membantu mengatasi masalah umum dalam pengembangan web seperti responsivitas dan konsistensi lintas peramban.

GRID CSS
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/d031d1c5-4ffe-466c-8761-54bce790bb19)
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/25a084df-12b2-4d67-8350-5b5e968915da)

# Mempelajari TAILWIND CSS
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/0cb84ef7-b035-4015-8a54-96fd93b9ed31)

## Instalasi CLI
Install tailwindcss via npm, and create your tailwind.config.js file.
```
npm install -D tailwindcss
npx tailwindcss init
```
# Langkah Membuat Halaman Website Sederhana menggunakan HTML dan Tailwind CSS
1. Buat File HTML standar
2. Buat File Style.css
3. Siapkan dokumen asetnya (File Gambar) Bebas
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/d958bc2a-df67-468f-922d-0ed7648c9dd8)

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Membuat Website dengan Tailwind</title>
    <!-- Jangan lupa tambahkan koneksi HTML ke CSS/Tailwind  -->
    <link rel="stylesheet" href="style.css" />
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
```
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/4ff52287-f051-4bda-b00d-9d53dba3a56b)

## Instal Extension Tailwind
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/f040db65-9847-4159-9952-fd70734b4020)

## Background Position
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/926cb138-760f-423e-84e6-693ce88d4c22)

## Kodingan membuat class container
```
 <!-- Membuat class container dan ukurannya disini -->
    <!-- Menambahkan background Images -->
    <!-- Menambah posisi gambar agar ketengah -->
    <!-- Mengatur posisi ukurannya -->
    <div
      class="container min-h-screen bg-[url('images/image.png')] bg-center bg-cover px-28 py-5 relative"
    >
      <!-- membuat class name flex pada nav-->
      <nav class="flex items-center">
        <img
          src="images/logo.png"
          alt="logonyaini"
          class="w-40 cursor-pointer"
        />
```

## Margin dan Padding
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/7c41e8ca-1fd9-4895-afe0-dc6dd7a6c51b)

## Atur Posisi Logo
```
      <ul class="flex-1 text-center">
```
## Atur margin setelah inline-block dan padding setelah text-white
```
        <li class="list-none inline-block px-5">
            <a href="#" class="no-underline text-white px-2">Home</a>
          </li>
          <li class="list-none inline-block px-5">
            <a href="#" class="no-underline text-white px-2">About</a>
          </li>
          <li class="list-none inline-block px-5">
            <a href="#" class="no-underline text-white px-2">Features</a>
          </li>
          <li class="list-none inline-block px-5">
            <a href="#" class="no-underline text-white px-2">Contact</a>
          </li>
        </ul>
        <img src="images/cart.png" alt="keranjang" class="w-8 cursor-pointer" />
      </nav>
```
## Membuat text dan jarak
```
<div class="text-white mt-48">
        <h1 class="text-6xl font-semibold leading-normal">
          Belajar Ngoding Cepat<br>
           <span class="font-light">Tailwindcss 20 Menit</span>
        </h1>
        <p>
         Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam recusandae deleniti, <br>necessitatibus quisquam accusantium voluptas maxime, incidunt voluptatibus architecto <br>excepturi placeat numquam. Consequuntur sed assumenda eum. Culpa, esse minima,<br> eum dicta ea non officia dignissimos neque fugiat quaerat voluptatibus autem!
        </p>
```
## Hover
```
<div class="mt-10">
          <a
            href="#"
            class="bg-yellow-300 rounded-3xl py-3 px-8 font-medium inline-block mr-4 hover:bg-transparant hover:border-yellow-300 hover:text-white duration-300 hover:border border border-transparent"
            >Mari Belajar</a
          >
          <a href="#">Download Modulnya <span class="text-lg inline-block rotate-90">&#10148</span></a>
        </div>
```
## Tambah Gambar
```
</div>
      <img src="images/programmer.png" class="w-full xl:w-1/2 xl:absolute bottom-0 right-20 alt="">
    </div>
```
## Responsive Website
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/ca2b8dae-1737-4933-ad0f-36931c9bc496)

# Hasil Akhir
![image](https://github.com/kerjabhakti/PWB231/assets/15622730/8fbc4901-b2e8-47df-932c-4145e0ff3634)
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/d4e48e7e-6ee0-4eb0-ba14-6405d5a187fa)


# JavaScript
# Praktikum JavaScript
## Langkah mudah mempelajari Javascript
1. Membuat File Javascript
2. Masukan Codingan
3. Jalankan Script JavaScript

## Membuat hello World! JavaScipt
``` js
<h2>Membuat JavaScript bisa membaca halaman dari</h2>
    <p id="coba">Isi akan berubah setelah kita klik button KLIK DISINI</p>
    <p>Menampilkan Waktu</p>
    <button
      type="button"
      onclick='document.getElementById("coba").innerHTML = "Hello World Selamat Datang di JavaScript"'
    >
      Klik Disini
    </button>
```

## Menampilkan waktu menggunakan JavaScript
```Js
 <!-- Ini codingan button yang kedua -->
    <button
      type="button"
      onclick="document.getElementById('waktu').innerHTML = Date()"
    >
      "Klik Disini untuk menampilkan Waktu.
    </button>
    <p id="waktu"></p>
```
## Hasilnya
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/aa4f68db-c1ac-4c47-a7c9-0e6d4d9db502)

## Menggunakan Source Value untuk menyalakan dan mematikan Lampu dari W3Scholl
``` js
<!-- Menyalakan Lampu Source Asli dari W3Scholl -->
    <h2>Menyalakan Lampu Source Asli dari W3Scholl</h2>
    <button
      onclick="document.getElementById('gambar').src='https://raw.githubusercontent.com/kerjabhakti/PWA231/main/Chapter06/pic_bulbon.gif'"
    >
      Nyalakan Lampunya
    </button>
    <img
      id="gambar"
      src="https://raw.githubusercontent.com/kerjabhakti/PWA231/main/Chapter06/pic_bulbon.gif"
      alt=""
    />
    <button
      onclick="document.getElementById('gambar').src='https://raw.githubusercontent.com/kerjabhakti/PWA231/main/Chapter06/pic_bulboff.gif'"
    >
      Matikan Lampunya
    </button>
```

# Hasilnya
## Lampu Menyala
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/bddb96b1-1651-41b8-a3ce-3b6bb6628e4d)
## Lampu Mati
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/2a7d5a6b-766e-4f98-9561-5745b4d1af10)

## Memasukan data Aritmatik pada COnsole JavaScript
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/98be1940-3c55-4aa2-acb9-4d816f411144)
Deskripsinya : Inputan terakhir itu akan error karena salah menggunakan syntax

## Membuat Variable JavaScript
``` js
<!-- Membuat Variable -->
    <h2>Membuat Variable</h2>
    <p>ini adalah sebuah variable didalam JavaScript</p>
    <p>JavaScript dapat melakukan apa saja yang anda perintahkan</p>
    <p id="variable"></p>
    <script>
      x = 10;
      y = 12;
      z = x * y;
      document.getElementById("variable").innerHTML = "isinya adalah = " + z;
    </script>
```
## hasilnya
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/9efdcd15-5dd0-4ac4-b284-9ac930cec0b4)

## Membuat Let Pada JavaScript
``` Js
    <!-- Membuat Let Pada JavaScript -->
    <h2>Ini Contoh Let</h2>
    <p id="let"></p>
    <script>
      let x = 20;
      {
        let x = 2;
      }
      document.getElementById("let").innerHTML = x;
    </script>
```
# hasilnya
![image](https://github.com/kerjabhakti/PWA231/assets/15622730/1dce4e34-44f1-4c9d-bf71-f1d581efcb18)

# Tugas Praktikum
1. Buat Folder NPM_NAMA_JS
2. Buatkan 1 tampilan website sederhana yang yang sudah dikerjakan sebelumnya
3. menggunakan HTML dan CSS Tailwind
4. Aritmatik, Syntax, Statement, Image Change, Button, Penggantian Paragraf dari Button
5. Buatkan Readme.md sesuai Studi kasus masing-masing




