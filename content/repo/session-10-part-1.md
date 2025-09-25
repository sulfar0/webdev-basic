---
date:  ""
draft: false
title: "sejarah CSS"
short: "sejarah"
thumb:
    image: "cover.jpg"
    anima: ""
    video: ""
layout: ""
weight: 10
lister: 1
format:
    media: "article"
    model: ""
    datum:
        data: ""
outcome:
    - prop: "CSS1 dan Awal Evolusi"
      name: "Konseptual"
      icon: ""
      desc: "Peserta memahami latar belakang munculnya CSS, kondisi web sebelum CSS, serta fitur dan keterbatasan CSS1 pada tahun 1996."
    - prop: "CSS2 dan CSS2.1"
      name: "Konseptual"
      icon: ""
      desc: "Peserta mengetahui perkembangan CSS2, penambahan layout dan media types, serta revisi CSS2.1 untuk stabilitas browser pada tahun 1998–2004."
    - prop: "CSS3 dan Standarisasi Modern"
      name: "Praktik"
      icon: ""
      desc: "Peserta dapat memahami modularisasi CSS3, fitur animasi dan responsivitas, serta peran W3C dalam standarisasi CSS modern."
    - prop: "Timeline dan Dampak Sejarah CSS"
      name: "Praktik"
      icon: ""
      desc: "Peserta dapat menelusuri perkembangan CSS dari 1996 hingga sekarang dan memahami dampak setiap versi terhadap desain web modern."
require:
    - prop: "Visual Code Editor"
      name: "Visual Code Editor"
      icon: ""
      desc: "Diperlukan teks editor untuk membaca dan menulis kode CSS, misalnya Visual Studio Code atau editor sejenis."
metadata:
    index: false
    thumb: "cover.jpg"
    group: []
    author: ["Muhammad Haydar Ilham Kamil"]
description: "Menelusuri sejarah perkembangan teknologi web dari awal hingga modern."
---

## 1. Pendahuluan

CSS (Cascading Style Sheets) adalah bahasa yang digunakan untuk mendesain dan mengatur tampilan halaman web. CSS memungkinkan pemisahan antara struktur konten (HTML) dan presentasi visualnya. Pemisahan ini mempermudah pengelolaan dan pemeliharaan situs web. CSS pertama kali diusulkan oleh Håkon Wium Lie pada tahun 1994 saat bekerja di CERN bersama Tim Berners-Lee. Tujuan utama dari CSS adalah untuk memberikan kontrol yang lebih besar atas tampilan halaman web tanpa mengubah struktur kontennya. CSS memungkinkan penggunaan berbagai gaya seperti warna, font, dan layout yang konsisten di seluruh halaman. Dengan CSS, pengembang dapat membuat desain yang responsif dan menarik secara visual. CSS juga mendukung prinsip desain yang terpisah antara konten dan presentasi, yang memudahkan kolaborasi antara pengembang dan desainer. 

---

## 2. Latar Belakang CSS

Sebelum adanya CSS, tampilan halaman web sepenuhnya bergantung pada HTML. HTML menyediakan elemen-elemen struktural seperti paragraf, tabel, dan gambar, namun tidak memiliki kemampuan untuk mengatur tampilan visual secara mendalam. Penggunaan atribut seperti `<font>` dan `<center>` dalam HTML untuk styling menyebabkan kode menjadi berantakan dan sulit dipelihara. Selain itu, penggunaan inline styles membuat pengelolaan desain menjadi tidak efisien, terutama untuk situs web besar dengan banyak halaman. Kebutuhan akan cara yang lebih terstruktur dan efisien untuk mendesain halaman web mendorong pengembangan CSS. CSS memungkinkan pengaturan gaya secara eksternal, sehingga memisahkan konten dari presentasi dan memudahkan pemeliharaan desain secara konsisten di seluruh situs.

---

## 3. Perkembangan dan Timeline CSS

### CSS1 (1996) – Fitur Awal dan Keterbatasan

CSS1 adalah versi pertama dari CSS yang dirilis oleh W3C pada tahun 1996. Versi ini memperkenalkan konsep dasar seperti selektor, properti, dan nilai untuk mengatur tampilan elemen HTML. CSS1 memungkinkan pengaturan gaya seperti warna teks, font, dan margin. Namun, CSS1 memiliki keterbatasan dalam hal layout dan kompatibilitas antar browser. Meskipun demikian, CSS1 menjadi langkah awal dalam pemisahan konten dan presentasi di web.

### CSS2 (1998) – Penambahan Layout dan Media Types

CSS2 dirilis pada tahun 1998 dan memperkenalkan fitur-fitur baru seperti positioning, z-index, dan media queries. Fitur positioning memungkinkan elemen untuk ditempatkan secara spesifik di halaman, sedangkan media queries memungkinkan pengaturan gaya berdasarkan jenis perangkat atau ukuran layar. CSS2 juga memperkenalkan konsep cascading yang memungkinkan gaya dari berbagai sumber digabungkan dengan prioritas tertentu. Namun, implementasi CSS2 tidak konsisten di berbagai browser, yang menyebabkan tantangan bagi pengembang web. 

### CSS2.1 (2004) – Revisi untuk Stabilitas Browser

CSS2.1 adalah revisi dari CSS2 yang dirilis pada tahun 2004. Versi ini bertujuan untuk memperbaiki ketidakstabilan dan inkonsistensi implementasi di berbagai browser. CSS2.1 menghapus beberapa fitur yang kurang didukung dan menekankan pada fitur-fitur yang lebih stabil dan luas dukungannya. Meskipun demikian, CSS2.1 belum sepenuhnya memenuhi kebutuhan desain web modern, sehingga pengembangan berlanjut ke versi berikutnya. 

### CSS3 (2005–Sekarang) – Modularisasi, Animasi, Responsivitas

CSS3 memperkenalkan pendekatan modular, di mana spesifikasi dibagi menjadi beberapa modul yang dapat dikembangkan secara independen. Modul-modul ini mencakup fitur-fitur seperti animasi, transisi, grid layout, dan flexbox. CSS3 memungkinkan pembuatan desain yang lebih dinamis dan responsif tanpa memerlukan JavaScript. Fitur-fitur seperti media queries memungkinkan pengaturan gaya berdasarkan ukuran layar, mendukung desain web yang responsif di berbagai perangkat. CSS3 telah menjadi standar de facto dalam desain web modern dan terus berkembang dengan penambahan fitur-fitur baru.

### CSS4 dan CSS5 (2015–Sekarang) – Evolusi Berkelanjutan

CSS4 dan CSS5 tidak dirilis sebagai versi terpisah, melainkan sebagai kumpulan modul-modul CSS yang terus berkembang. Modul-modul ini mencakup fitur-fitur baru seperti container queries, subgrid, dan custom properties. Pengembangan CSS saat ini berfokus pada peningkatan fleksibilitas dan kemampuan desain, memungkinkan pengembang untuk membuat layout yang lebih kompleks dan interaktif tanpa bergantung pada JavaScript. CSS terus berkembang untuk memenuhi kebutuhan desain web yang semakin kompleks dan beragam.

---

## 4. Peran W3C dalam Standarisasi CSS

W3C (World Wide Web Consortium) memainkan peran penting dalam standarisasi CSS. Sejak awal, W3C membentuk kelompok kerja CSS untuk mengembangkan dan memelihara spesifikasi CSS. Kelompok kerja ini terdiri dari berbagai pihak, termasuk pengembang, desainer, dan perwakilan dari perusahaan teknologi. W3C bertanggung jawab untuk merilis spesifikasi resmi CSS dan memastikan bahwa standar tersebut diterima dan diimplementasikan secara luas di industri. Melalui proses ini, W3C memastikan bahwa CSS tetap relevan dan dapat memenuhi kebutuhan desain web yang terus berkembang.

---

## 5. Kesimpulan

CSS telah berkembang pesat sejak pertama kali diusulkan pada tahun 1994. Dari versi awal yang sederhana hingga modul-modul canggih saat ini, CSS telah memungkinkan pengembang untuk menciptakan desain web yang menarik dan fungsional. Peran W3C dalam standarisasi CSS memastikan bahwa teknologi ini tetap konsisten dan dapat diandalkan di seluruh platform. Dengan terus berkembangnya CSS, masa depan desain web terlihat semakin cerah dan penuh inovasi.

---