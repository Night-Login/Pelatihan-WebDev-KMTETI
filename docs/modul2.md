---
layout: default
title: Modul 1
description: Modul 1 Pelatihan WebDev 2 KMTETI 2023/2024.
---

# **CSS and TailwindCSS**
[← Kembali](./)

[Versi Google Docs](https://docs.google.com/document/d/1wa5O2ZyeqsU9dBnCOjotH5rwXc1apYnosM_5K1dEgCc/edit?usp=sharing)

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

#### **2. Properti**
- Tekstual: Mengatur font, warna, ukuran teks, dll.
- Latar Belakang: Mengatur warna latar belakang, gambar latar belakang, dll.

### **Layout dan Posisi**
##### **1. Box Model**
Memahami margin, border, padding, dan konten.

#### **2. Position**
Mengatur posisi elemen (static, relative, absolute, fixed).

#### **3. Flexbox**
Menggunakan Flexbox untuk layout fleksibel.

#### **4. Grid** 
Menggunakan Grid untuk layout grid.

### **Responsive Design**
#### **1. Media Queries**
Menggunakan media queries untuk desain responsif.

#### **2. Viewport dan Unit Relatif**
Mengatur viewport dan menggunakan unit relatif seperti %, vw, vh.

### **Styling Lanjutan**
##### **1. Transisi dan Animasi**
Membuat transisi dan animasi dengan CSS.

#### **2. Transformasi**
Menggunakan transformasi CSS seperti rotate, scale, translate, dll.

#### **3. Pseudo-kelas dan Pseudo-elemen**
Menggunakan pseudo-kelas dan pseudo-elemen untuk styling spesifik.

#### **4. Variabel CSS**
Menggunakan variabel CSS untuk menyimpan nilai yang dapat digunakan kembali.