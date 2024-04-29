---
layout: default
title: Modul 3
description: Modul 3 Pelatihan WebDev 2 KMTETI 2023/2024.
---

# **TypeScript**

[← Kembali](./)

## **Apa itu TypeScript**
TypeScript (TS) adalah bahasa pemrograman modern yang bersifat _open-source_. TS dikembangkan dan di-_maintain_ oleh Microsoft. Ia adalah _superset_ of JavaScript, artinya kode JS yang valid juga merupakan kode TS yang valid pula. TS menambahkan fitur opsional berupa _static typing_ dam fitur-fitur lainnya ke JS untuk mempermudah _development_ pada aplikasi _large-scale_.

## **Instalasi**
Pastikan sudah terinstal Node.js dan NPM di device, jika belum, bisa download di [sini](https://nodejs.org/en/download).

Jika sudah, buka Command Prompt (CMD), kemudian ketikkan command `npm install -g typescript`, setelah itu, jalankan command `tsc` untuk memastikan intalasi sudah berjalan.

## **Compiling**
_Compiling_ adalah nama proses yang mengubah file TypeScript (.ts) menjadi JavaScript (.js).

Cara melakukan _compile_ adalah dengan command `tsc <nama-file>`.

## **Basic Syntax**
TypeScript menambahkan fitur _type annotations_ pada JavaScript supaya kita bisa mendeklarasikan tipe data secara eksplisit pada variabel dan fungsi.

**1. Number** → Tipe data angka baik itu bilangan bulat (_integer_) maupun bilangan desimal (_float_).

**2. String** → Tipe data teks (sederetan karakter)

**3. Boolean** → Tipe data yang berisi `true` atau `false`.

**4. Array** → Tipe data yang berbentuk deretan nilai, bisa dideklarasikan dengan 2 cara:  `type[]` atau `Array<type>`.

**5. Tuple** → Tipe data mirip dengan array, tetapi **banyaknya tetap**, **tipenya diketahui**, dan **tipenya tidak perlu sama**. Eg: `let tuple: [string, number]`

**6. Enum** → Memberikan nama pada sebuah urutan angka. Eg: angka 0 sampai 6 diberikan nama hari `enum Days {Sun, Mon, Tue, Wed, ...}`

## **Type Annotations**