---
layout: default
title: Modul 1
description: Modul 1 Pelatihan WebDev 2 KMTETI 2023/2024.
---

# **Intro to Web Development**
[← Kembali](./)

### **Apa itu Web Development?**
Web development adalah proses pembuatan dan pengembangan situs web atau aplikasi web yang dapat diakses melalui internet. Web development mencakup berbagai aspek, mulai dari pengembangan halaman web sederhana yang berisi teks statis hingga pembuatan aplikasi web yang kompleks, layanan web, dan jaringan sosial. 

### **Konsep Umum dalam Web Development**
Web development biasanya dibagi menjadi tiga komponen utama:
#### **1. Frontend Development**
Ini adalah bagian dari web development yang berfokus pada pengembangan antarmuka pengguna (user interface) yang dapat diakses dan digunakan oleh pengguna melalui browser web.
Teknologi utama yang digunakan dalam frontend development termasuk **HTML**, **CSS**, dan **JavaScript**, serta kerangka kerja (frameworks) dan pustaka (libraries) seperti **React**, **NextJS**, Angular, dan Vue.js.

#### **2. Backend Development**
Backend development berfokus pada server, database, dan aplikasi yang berjalan di belakang layar untuk mendukung fungsi dan logika dari situs web atau aplikasi web.
Teknologi yang sering digunakan dalam backend development termasuk bahasa pemrograman seperti JavaScript, Python, Ruby, dan PHP, serta sistem manajemen database seperti MongoDB, dan PostgreSQL.

#### **3. Fullstack Development**
Full-stack development mengacu pada pengembangan baik frontend maupun backend dari sebuah situs web atau aplikasi web.
Seorang full-stack developer memiliki kemampuan untuk bekerja pada semua aspek pengembangan web, mulai dari antarmuka pengguna hingga logika server dan manajemen basis data.

### **Tools dan Tech Stack yang Akan Digunakan**
#### **1. Tools**
**a. Web Browser**
Web browser adalah aplikasi untuk menampilkan HTML, CSS, serta menjalankan kode JavaScript.

**b. Visual Studio Code**
Visual Studio adalah Integrated Development Environment (IDE) yang paling populer di kalangan programmer. Sebuah IDE digunakan untuk melakukan coding.

[Link Download](https://code.visualstudio.com)

**c. NodeJS**
Umumnya, JavaScript hanya bisa dijalankan di dalam sebuah web browser. Untuk bisa menjalankan kode JavaScript di luar web browser diperlukan sebuah runtime. Runtime untuk JavaScript yang paling populer adalah NodeJS. Dengan menggunakan NodeJS, nantinya kita bisa menjalankan kode JS di luar browser.

[Link Download](https://nodejs.org/en/download/current)

**d. Git**
Git adalah suatu sistem version control. Ini digunakan untuk melacak perubahan pada source code kita. Selain itu, Git juga membuat kita bisa berkolaborasi dengan developer lain secara remote.

[Link Download](https://git-scm.com/downloads)

#### **2. Tech Stack**
**a. HTML**

**b. CSS**

**c. JavaScript**

**d. TypeScript**

**e. ReactJS**

**f. NextJS**

### **HTML**
HTML, singkatan dari Hypertext Markup Language, adalah bahasa markup standar yang digunakan untuk membuat dan mendesain halaman web. HTML bukanlah bahasa pemrograman, melainkan cara untuk menyusun dan memformat konten di internet. Berikut beberapa konsep dasar HTML yang penting untuk dipahami:

#### **1. Elemen HTML**
Elemen dasar dari halaman web, yang terdiri dari tag pembuka, konten, dan tag penutup. Contoh: 
```
<p>Ini adalah paragraf.</p>
```
- `<p>` adalah tag pembuka
- `Ini adalah paragraf` adalah kontennya 
- `</p>` adalah tag penutup.

#### **2. Atribut HTML**
Atribut memberikan informasi tambahan tentang elemen HTML, seperti sifat atau perilakunya. Atribut ditulis di dalam tag pembuka, contoh: 
```
<img
  id="gambar1"
  class="image"
  src="gambar.jpg"
  alt="Deskripsi Gambar"
/>
```
- `id` adalah atribut yang digunakan untuk identifikasi elemen.
- `class` adalah atribut yang digunakan untuk memberi kelas pada suatu elemen.
- `src` adalah atribut yang menunjukkan sumber gambar.
- `alt` adalah atribut yang memberikan teks alternatif jika gambar tidak dapat ditampilkan.

#### **3. Struktur Dasar HTML**
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0"
    />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

#### **4. Komentar HTML**
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Bagian ini tidak tampil di halaman browser -->
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0"
    />
    <title>Document</title>
  </head>
  <body>
    <!-- Bagian ini ditampilkan di halaman browser -->
    <h1>Hello World!</h1>
  </body>
</html>
```

#### **5. Styling**
```
<h1 style="color:darkblue">Ini Heading 1</h1>
<p 
 style="text-align: left; font-size: 20px; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
  Lorem, ipsum dolor sit amet 
  consectetur adipisicing elit. Repudiandae,sapiente.
</p>
```

#### **6. Tag-Tag HTML Lainnya**
- **Anchor Tag**
```
<a href="https://www.nightlogin.id">
  Web Night Login
</a>
```
```
<p>
  Kunjungi website Night Login
  <a href="https://www.nightlogin.id">di sini</a>
  .
</p>
```
- **Image Tag**
```
<img 
  id="gambar1" 
  class="image" 
  src="gambar.jpg" 
  alt="Deskripsi Gambar" 
/>
```
- **Div Tag**
```
<div>
  <p>Ini paragraf 1</p>
  <p>Ini paragraf 2</p>
  <p>Ini paragraf 3</p>
</div>
<div>
  <p>Ini paragraf 4</p>
  <p>Ini paragraf 5</p>
  <p>Ini paragraf 6</p>
</div>
```
- **Button Tag**
```
<button>Klik Di Sini</button>
```
- **Input Tag**
```
Masukkan nama anda: <input type="text" />
<br />
Masukkan password: <input type="password"/>
<br />
Masukkan umur anda: <input type="number"/>
<br />
Masukkan email anda: <input type="email"/>
<br />
<input type="range"/>
<br />
<input type="radio"/>
<br />
<input type="checkbox"/>
<br />
<input type="checkbox"/>
<br />
<input type="file"/>
<br />
<input type="date"/>
<br />
<input type="time"/>
<br />
<input type="color"/>
```
- **Style Tag**
```
<div style="background-color: red; color: white">
  <p id="p1">Ini paragraf 1</p>
  <p class="align-center">Ini paragraf 2</p>
  <p class="align-center">Ini paragraf 3</p>
</div>
<div style="background-color: lightblue; color: green">
  <p class="align-center">Ini paragraf 4</p>
  <p class="align-center">Ini paragraf 5</p>
  <p class="align-center">Ini paragraf 6</p>
</div>
```
```
<style>
  p {
    font-size: 20px;
    font-weight: 700;
  }
  #p1 {
    color: purple;
  }
  .align-center {
    text-align: center;
  }
</style>
```
#### **7. Sifat Element HTML**