---
layout: default
title: Modul 2
description: Modul 2 Pelatihan WebDev 2 KMTETI 2023/2024.
---

# **CSS and TailwindCSS**
[← Kembali](./)

[Versi Google Docs](https://docs.google.com/document/d/1pYqaDKJUzoRkqn0GgxNgbZCm4ipUVSYD58YhC3VpTxs/edit?usp=sharing)

### **Apa itu CSS?**
CSS adalah singkatan dari Cascading Style Sheets. Ini adalah bahasa style sheet yang digunakan untuk mendeskripsikan tampilan dan format dari dokumen yang ditulis dalam bahasa markup, seperti HTML. CSS digunakan untuk mengontrol gaya, layout, dan penampilan elemen pada halaman web.

### **Menyisipkan CSS ke dalam HTML**
Ada 3 cara untuk menyisipkan *styling* ke elemen HTML, 2 di antaranya sudah dibahas di [modul sebelumnya](./modul1.html).

#### **1. Inline**
Menulis CSS langsung di dalam tag HTML.

`<p style="color: red">Hello world!</p>`

#### **2. Tag Style**
Menulis CSS di dalam tag `<style>` di dokumen HTML.

```
<style>
  p {
    color: red;
  }
</style>
<p>Hello world!</p>
```

#### **3. External CSS**
Menyimpan CSS di file terpisah dengan ekstensi .css dan menghubungkannya ke HTML menggunakan tag `<link>`.

### **Selector dan Property CSS**

#### **1. Selector**
- Elemen: Menargetkan elemen HTML berdasarkan nama tag.
- Kelas: Menargetkan elemen berdasarkan atribut kelas.
- ID: Menargetkan elemen berdasarkan atribut ID.

[CSS Selectors](https://www.w3schools.com/css/css_selectors.asp)

#### **2. Properti**
- Tekstual: Mengatur font, warna, ukuran teks, dll.
- Latar Belakang: Mengatur warna latar belakang, gambar latar belakang, dll.

### **Layout dan Posisi**
#### **1. Box Model**
- [CSS Margins](https://www.w3schools.com/css/css_margin.asp)
- [CSS Paddings](https://www.w3schools.com/css/css_padding.asp)
- [CSS Borders](https://www.w3schools.com/css/css_border.asp)


#### **2. Position**
Mengatur posisi elemen (static, relative, absolute, fixed).

[CSS Positions](https://www.w3schools.com/css/css_positioning.asp)

#### **3. Flex**
Flex adalah salah satu metode layout yang sering digunakan untuk layouting. Flex memberikan kemampuan pada developer untuk mengatur flow dari dokumen supaya lebih mudah ketika membuat layout yang responsif.

[CSS Flex](https://www.w3schools.com/css/css3_flexbox.asp)

#### **4. Grid** 
Grid adalah salah satu metode layout untuk mengatur flow dokumen dalam format mirip dengan tabel.

[CSS Grid](https://www.w3schools.com/css/css_grid.asp)

### **Responsive Design**
#### **1. Media Queries**
Menggunakan media queries untuk desain yang responsif.

[CSS Media Queries](https://www.w3schools.com/css/css3_mediaqueries.asp)

#### **2. Viewport dan Unit Relatif**
CSS menyediakan unit satuan yang bisa digunakan relatif terhadap value lainnya. Contohnya %, vw, vh, rem, em dll.

### **Styling Lanjutan**
#### **1. Transformasi**
Melakukan transformasi matematis seperti scale, translate, skew, rotate, dll.

#### **2. Transisi dan Animasi**
Membuat transisi dan animasi dengan CSS.

#### **3. Variabel CSS**
Menggunakan variabel CSS untuk menyimpan nilai yang dapat digunakan kembali.

[CSS Variables](https://www.w3schools.com/css/css3_variables.asp)

### **TailwindCSS**
TailwindCSS / Tailwind adalah salah satu framework CSS yang sangat populer di kalangan developer *front-end* karena fleksibilitasnya yang tinggi dan kemampuannya mempercepat *development*. Extension Tailwind juga tersedia di VS Code untuk membantu penggunaannya.

Tailwind bekerja dengan cara membuatkan banyak class CSS yang memberikan properti tertentu. Artinya kita tidak perlu mendefinisikan setiap class dan propertinya, cukup kita tambahkan class yang diperlukan ke HTML kita.

[Tailwind Play CDN](https://tailwindcss.com/docs/installation/play-cdn)

```
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>
```

### **Hands-on**
[Figma Design](https://www.figma.com/file/hkJayXOWUj9zltzHgqBajg/User-Profile---Business-Card-(Community)?type=design&node-id=0%3A1&mode=design&t=6kBN5aIvg6swJOCL-1)