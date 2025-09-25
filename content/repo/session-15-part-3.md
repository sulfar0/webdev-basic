---
date:  "2025-09-22T12:30:00+07:00"
draft: false
title: "garis"
short: "garis"
thumb:
    image: "cover.jpg"
    anima: ""
    video: ""
layout: ""
weight: 15
lister: 3
format:
    media: "article"
    model: ""
    datum:
        data: ""
outcome:
    - prop: ""
      name: "Konseptual"
      icon: ""
      desc: "Memahami fungsi garis dalam memisahkan konten dan menekankan elemen penting di halaman web." 
    - prop: ""
      name: "Konseptual"
      icon: ""
      desc: "Mampu membedakan berbagai jenis garis, seperti horizontal, border, dan dekoratif, serta penerapannya." 
    - prop: ""
      name: "Praktik"
      icon: ""
      desc: "Mampu membuat garis horizontal, garis border, dan garis dekoratif pada heading dengan benar." 
    - prop: ""
      name: "Praktik"
      icon: ""
      desc: "Mampu menerapkan garis yang konsisten, estetis, dan responsif di seluruh halaman web." 
require:
    - prop: ""
      name: ""
      icon: ""
      desc: ""
metadata:
    index: false
    thumb: "cover.jpg"
    group: []
    author: ["Sultan Fajar Ramadhan"]
description: "Memahami properti border CSS untuk membuat dan mengatur garis elemen."
---

# 1. Pendahuluan

Garis adalah salah satu elemen visual yang sering digunakan dalam halaman web untuk membagi konten atau memberikan aksen pada desain (Duckett, 2011). Elemen garis membantu pengguna membedakan section atau blok konten, sehingga navigasi lebih mudah dipahami. Penggunaan garis yang tepat meningkatkan keterbacaan dan estetika halaman secara keseluruhan.

Selain itu, garis juga memiliki potensi sebagai elemen desain untuk memperkuat branding. Misalnya, garis horizontal dapat memberikan ritme visual pada layout atau menekankan elemen tertentu. Dengan memahami cara membuat garis, developer dapat menyesuaikan tampilan sesuai kebutuhan desain.

Garis dapat diterapkan menggunakan properti CSS seperti `border`, `border-top`, `border-bottom`, atau tag HTML `<hr>` (MDN Web Docs, 2024). Pemahaman teknik garis yang berbeda memungkinkan pengembang membuat variasi visual, dari garis tipis sederhana hingga garis tebal atau bergelombang. Hal ini membuka peluang kreativitas dalam layout halaman.

Selain aspek estetika, garis juga memiliki fungsi praktis dalam tata letak responsif. Garis dapat disesuaikan lebarnya atau posisinya sesuai ukuran layar sehingga tetap konsisten dan proporsional. Pemahaman ini sangat penting untuk membuat desain modular dan profesional yang adaptif di berbagai perangkat.

---

# 2. Kenapa Penting

### Membagi Konten secara Visual

Garis berfungsi sebagai pembatas konten yang jelas, membantu pengguna memahami struktur halaman (Duckett, 2011). Dengan garis, setiap section terlihat lebih terpisah, sehingga pembaca lebih mudah fokus pada informasi tertentu.

Pemisahan visual ini meningkatkan keterbacaan halaman web. Tanpa garis, section dapat terlihat menyatu sehingga membingungkan pengguna. Garis membantu memberikan ritme dan hierarki visual pada layout.

Selain itu, garis juga mendukung desain modular. Setiap elemen atau container dapat dipisahkan dengan garis sehingga tetap konsisten, memudahkan tim developer dalam pengaturan layout.

---

### Menekankan Elemen Penting

Garis dapat digunakan untuk menonjolkan konten atau heading tertentu (Frain, 2015). Dengan garis horizontal atau vertikal, perhatian pengguna dapat diarahkan ke area spesifik.

Teknik ini meningkatkan user experience karena informasi penting lebih mudah dikenali. Garis yang konsisten menambah estetika tanpa membuat halaman terlihat ramai.

Selain itu, garis dapat dikombinasikan dengan warna atau tebal berbeda untuk memperkuat branding. Developer dapat membuat variasi visual yang sesuai dengan identitas halaman web.

---

### Membantu Layout Responsif

Garis CSS yang tepat dapat beradaptasi dengan ukuran layar, menjaga proporsionalitas layout (MDN Web Docs, 2024). Garis horizontal, misalnya, dapat mengisi container atau disesuaikan lebarnya agar tetap seimbang.

Ini mempermudah pembuatan desain responsif, di mana elemen tetap rapi di berbagai perangkat. Garis yang fleksibel menjaga konsistensi visual dan modularitas halaman.

Selain itu, pemahaman properti garis membantu menghindari konflik layout. Developer dapat memastikan garis tidak menyebabkan overflow atau tumpang tindih dengan elemen lain.

---

# 3. Konsep Dasar

Garis pada CSS biasanya dibuat menggunakan properti `border` atau tag HTML `<hr>` (Duckett, 2011). Border dapat diterapkan pada sisi elemen tertentu: top, bottom, left, atau right. Properti ini memungkinkan developer menyesuaikan tebal, gaya, dan warna garis sesuai kebutuhan.

Contoh dasar:

```html
<hr style="border: 2px solid black;">
```

Penjelasan: Garis horizontal `<hr>` menggunakan border 2px berwarna hitam. Elemen ini memisahkan konten di halaman web dengan cara sederhana namun efektif.

Selain `<hr>`, garis juga dapat dibuat dengan `border-bottom` pada elemen div atau heading. Teknik ini sering digunakan untuk menekankan heading atau membuat efek underline dekoratif (Frain, 2015). Penggunaan border memungkinkan kontrol lebih fleksibel dibandingkan tag `<hr>` standar.

Contoh:

```html
<h2 style="border-bottom: 3px solid blue;">Heading dengan Garis</h2>
```

Penjelasan: Heading memiliki garis biru 3px di bawahnya, memisahkan konten secara visual. Teknik ini membantu membuat tampilan lebih menarik dan menekankan struktur halaman.

Garis juga dapat diatur gaya dan arah, misalnya `dashed`, `dotted`, atau `solid`. Properti ini memberikan variasi visual untuk keperluan desain. Pemahaman dasar ini penting agar garis tidak hanya fungsional tetapi juga estetis.

Selain estetika, garis mendukung konsistensi layout di seluruh halaman. Pengembang dapat menyesuaikan posisi, tebal, dan warna garis agar sesuai dengan style guide atau branding website. Ini membantu membuat desain modular dan profesional.

---

# 4. Jenis dan Contoh

### Garis Horizontal Standar

Garis horizontal standar menggunakan tag `<hr>` untuk memisahkan konten pada halaman web (Duckett, 2011). Garis ini sangat berguna untuk membagi section atau blok informasi. Penggunaannya sederhana dan langsung terlihat efeknya di halaman.

Contoh:

```html
<hr>
```

Penjelasan: `<hr>` membuat garis horizontal tipis yang memisahkan konten secara default. Developer dapat menambahkan atribut style untuk menyesuaikan warna, tebal, atau margin.

Garis horizontal membantu memberikan ritme visual pada halaman web. Penggunaan garis ini membuat halaman lebih mudah dibaca dan informasi lebih terstruktur.

---

### Garis dengan Border

Garis juga dapat dibuat menggunakan properti `border` pada elemen seperti div atau heading (Frain, 2015). Teknik ini memberi kontrol lebih atas tampilan garis, misalnya tebal, warna, dan gaya (solid, dashed, dotted).

Contoh:

```html
<div style="border-top: 3px solid red; width: 50%;"></div>
```

Penjelasan: Garis merah dengan lebar 50% dari container dibuat di atas elemen div. Teknik ini memungkinkan garis bersifat dekoratif dan fleksibel dibanding `<hr>`.

Dengan garis border, developer dapat menekankan konten tertentu atau menyesuaikan desain halaman dengan estetika yang diinginkan.

---

### Garis Dekoratif pada Heading

Garis dekoratif sering diterapkan pada heading untuk menambah nilai visual (MDN Web Docs, 2024). Teknik ini memperjelas hierarki konten dan membuat halaman lebih menarik.

Contoh:

```html
<h2 style="border-bottom: 4px dashed blue; width: 200px;">Judul dengan Garis Dekoratif</h2>
```

Penjelasan: Heading memiliki garis bawah biru putus-putus. Garis ini menekankan heading sekaligus memberikan efek dekoratif pada halaman.

Garis dekoratif dapat dikombinasikan dengan spacing untuk menyeimbangkan tampilan. Ini membantu menjaga konsistensi layout dan meningkatkan estetika halaman web.

---

# 5. Implementasi dari Setiap Contoh

### Garis Horizontal Standar

Garis horizontal standar sangat mudah diterapkan menggunakan tag `<hr>` untuk memisahkan konten di halaman web (Duckett, 2011). Elemen ini tidak memerlukan perhitungan tambahan dan langsung memberikan efek visual.

Contoh implementasi:

```html
<hr style="border: 1px solid gray; margin: 20px 0;">
```

Penjelasan: Garis horizontal dengan ketebalan 1px dan jarak margin 20px memisahkan section konten dengan rapi. Teknik ini membantu menjaga keterbacaan dan memberikan ritme visual.

Garis horizontal juga cocok untuk layout responsif. Margin dan lebar garis dapat disesuaikan agar tetap proporsional di berbagai perangkat, sehingga halaman terlihat rapi di desktop maupun mobile.

---

### Garis dengan Border

Garis menggunakan properti `border` memberi fleksibilitas lebih dalam desain (Frain, 2015). Garis dapat ditempatkan pada div atau heading dengan tebal, warna, dan gaya sesuai kebutuhan.

Contoh implementasi:

```html
<div style="border-top: 2px dashed red; width: 70%; margin: 10px 0;"></div>
```

Penjelasan: Garis merah putus-putus dengan lebar 70% membuat pemisahan konten lebih dekoratif. Margin atas dan bawah memberi jarak sehingga tidak terlalu menempel ke elemen lain.

Teknik ini cocok untuk section yang membutuhkan penekanan visual lebih dibanding `<hr>`. Garis border dapat menyesuaikan lebar container dan warna tema halaman.

---

### Garis Dekoratif pada Heading

Garis dekoratif pada heading menekankan hierarki konten sekaligus menambah estetika (MDN Web Docs, 2024). Teknik ini membuat heading lebih menonjol tanpa mengganggu layout.

Contoh implementasi:

```html
<h2 style="border-bottom: 3px solid blue; width: 180px; margin-bottom: 15px;">Heading dengan Garis</h2>
```

Penjelasan: Garis biru tebal 3px menekankan heading. Margin bawah memberi jarak agar konten berikutnya tidak terlalu dekat, menjaga keteraturan visual.

Implementasi ini membantu pengguna memahami struktur halaman sekaligus memberikan efek visual yang menarik. Garis dekoratif dapat digunakan untuk membedakan section penting.

---

# 6. Kesalahan Umum

### Garis Tidak Konsisten

Kesalahan umum pertama adalah penggunaan garis yang tidak konsisten antar section (Frain, 2015). Hal ini membuat tampilan halaman terlihat berantakan dan membingungkan pengguna.

Contoh salah:

```html
<hr style="border: 1px solid gray;">
<div style="border-top: 3px dashed red;"></div>
```

Contoh benar:

```html
<hr style="border: 2px solid gray; margin: 20px 0;">
<hr style="border: 2px solid gray; margin: 20px 0;">
```

Penjelasan: Pada contoh salah, gaya garis berbeda sehingga layout tidak seragam. Pada contoh benar, semua garis menggunakan gaya, ketebalan, dan margin yang sama, menjaga konsistensi visual.

---

### Garis Terlalu Dekoratif

Kesalahan kedua adalah penggunaan garis terlalu dekoratif sehingga mengganggu fokus pengguna (Duckett, 2011). Garis yang terlalu tebal atau warna kontras berlebihan bisa mengalihkan perhatian dari konten utama.

Contoh salah:

```html
<hr style="border: 5px dashed red;">
```

Contoh benar:

```html
<hr style="border: 2px solid gray;">
```

Penjelasan: Garis 5px merah terlalu mencolok dan mengganggu konten. Garis 2px abu-abu lebih netral dan tetap memisahkan section tanpa mengalihkan fokus.

---

### Garis Tidak Responsif

Kesalahan ketiga adalah garis tidak menyesuaikan lebar container atau layar (MDN Web Docs, 2024). Hal ini menyebabkan garis terlihat pecah atau terlalu panjang pada beberapa perangkat.

Contoh salah:

```html
<div style="border-top: 3px solid blue; width: 600px;"></div>
```

Contoh benar:

```html
<div style="border-top: 3px solid blue; width: 80%;"></div>
```

Penjelasan: Pada contoh salah, garis tetap 600px sehingga tidak proporsional di layar kecil. Contoh benar menggunakan persentase, menjaga garis tetap proporsional dan responsif.

---

### Tabel Perbandingan

| Kesalahan               | Contoh Salah                                                                                 | Contoh Benar                                                  | Dampak                                       |
| ----------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------------------- | -------------------------------------------- |
| Garis tidak konsisten   | `<hr style="border: 1px solid gray;">` dan `<div style="border-top: 3px dashed red;"></div>` | `<hr style="border: 2px solid gray;">`                        | Layout terlihat berantakan                   |
| Garis terlalu dekoratif | `<hr style="border: 5px dashed red;">`                                                       | `<hr style="border: 2px solid gray;">`                        | Mengalihkan fokus dari konten                |
| Garis tidak responsif   | `<div style="border-top: 3px solid blue; width: 600px;"></div>`                              | `<div style="border-top: 3px solid blue; width: 80%;"></div>` | Garis pecah atau tidak proporsional di layar |

---

# 7. Best Practice

### Gunakan Garis Konsisten di Seluruh Halaman

Menggunakan gaya garis yang konsisten membuat tampilan halaman lebih rapi dan profesional (Frain, 2015). Ketebalan, warna, dan margin sebaiknya sama di seluruh section agar visual harmonis.

Contoh implementasi:

```html
<hr style="border: 2px solid gray; margin: 20px 0;">
```

Penjelasan: Semua garis horizontal menggunakan ketebalan 2px, warna abu, dan margin 20px, sehingga layout terlihat seragam. Konsistensi ini membantu pengguna lebih mudah memahami struktur halaman.

Selain itu, konsistensi mempermudah tim developer. Semua anggota mengikuti standar yang sama sehingga workflow lebih rapi dan efisien.

---

### Pilih Garis yang Sesuai dengan Desain

Garis harus disesuaikan dengan estetika halaman dan branding (Duckett, 2011). Misalnya, garis tipis untuk layout minimalis atau garis tebal untuk menekankan section penting.

Contoh implementasi:

```html
<div style="border-top: 3px solid blue; width: 70%;"></div>
```

Penjelasan: Garis biru tebal menekankan section tertentu. Pemilihan gaya, warna, dan ketebalan membantu menjaga konsistensi dengan desain keseluruhan halaman.

Pemilihan garis yang tepat meningkatkan pengalaman pengguna. Garis yang sesuai dengan tema halaman membuat visual lebih nyaman dan profesional.

---

### Pastikan Garis Responsif

Garis harus menyesuaikan ukuran container atau layar untuk menjaga proporsionalitas (MDN Web Docs, 2024). Gunakan persentase atau unit fleksibel agar garis tetap proporsional di berbagai perangkat.

Contoh implementasi:

```html
<div style="border-top: 2px solid gray; width: 80%;"></div>
```

Penjelasan: Garis menyesuaikan lebar container dengan persentase. Ini menjaga proporsionalitas di desktop maupun mobile, sehingga layout tetap rapi.

Garis responsif juga mengurangi risiko layout pecah atau overflow. Praktik ini sangat penting untuk desain yang modular dan adaptif.

---

# 8. Kesimpulan

Garis CSS adalah elemen visual penting yang membantu memisahkan konten, menekankan heading, dan memperbaiki keterbacaan halaman web (Duckett, 2011). Pemahaman tentang penggunaan garis yang tepat meningkatkan kualitas tampilan dan navigasi pengguna. Dengan mengaplikasikan border, `<hr>`, atau garis dekoratif pada heading, developer dapat menciptakan layout yang lebih rapi dan estetis.

Selain itu, konsistensi, responsivitas, dan pemilihan gaya garis yang sesuai desain sangat berpengaruh terhadap pengalaman pengguna. Penerapan best practice membuat halaman lebih harmonis dan mudah diadaptasi pada berbagai perangkat. Garis bukan hanya pemisah konten, tetapi juga alat desain yang efektif.

**Gagasan Utama:**

* Garis memisahkan konten dan menekankan section penting.
* Konsistensi gaya, ketebalan, warna, dan margin garis penting untuk layout harmonis.
* Pilih garis sesuai estetika dan branding halaman.
* Pastikan garis responsif agar proporsional di berbagai perangkat.

---

# 9. Referensi

Duckett, J. (2011). *HTML and CSS: Design and Build Websites*. Wiley.

Frain, B. (2015). *Responsive Web Design with HTML5 and CSS3*. Packt Publishing.

MDN Web Docs. (2024). *CSS Borders*. Mozilla Developer Network. Diakses dari [https://developer.mozilla.org/en-US/docs/Web/CSS/border](https://developer.mozilla.org/en-US/docs/Web/CSS/border)

