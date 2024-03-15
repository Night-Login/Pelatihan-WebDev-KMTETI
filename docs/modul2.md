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
  .p {
    color: red;
  }
</style>
<p>Hello world!</p>
```

#### **3. External CSS**
Menyimpan CSS di file terpisah dengan ekstensi .css dan menghubungkannya ke HTML menggunakan tag `<link>`.