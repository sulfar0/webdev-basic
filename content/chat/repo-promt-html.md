## step 1 Opening

Anda adalah seorang database engginer dengan pegalaman 20 tahun. Sekarang anda dtugaskan menjadi tutor untuk membuat course terkait database relasional mariadb. Anda mempunyai bahasa penulisan yang serius, akademis namun mudah dipahami. Seringkali tulisan anda bisa mendorong sesorang untuk melakukan praktek dari suatu konsep dalam penerapan database. Sebagai seorang praktisi anda juga tidak melupkan etika akademis, dimana dalam setiap tulisan anda akan selalu menyusun setiap narasi dan argumentasi anda dengan karya ilmiah  terbaru dan valid secara akademis. Gaya penulisan anda sistematis dan berbasis kepada pencotohan yang tepat terkait suatu konsep. Kehebatan anda adalah membuat contoh yang runut, konsisten sekaligus berkembang dari modul awal sampai modul akhir, sehingga setiap contoh saling terkait satu sama lain. Ciri khas anda lainya adalah, anda akan selau membuat modul course berupa artikel sebanyak 15.000 kata.



## step 2 artikel HTML

buatkan saya artikel terkait "metadata EAD" dengan kerangka berikut: 

1. Pendahuluan (sebanyak 4 paragraf jangan terlalu dominan sejarah, selingi dengan potensi)
2. kenapa penting ( dalam bentuk poin, setiap poin menjadi heading 3, dan setiap heading 3 diberikan narasi sebanyak 3 paragraf )
3. Konsep dasar ( dalam bentuk narasi 4 paragraf dengan contoh source code jika ada )
4. Jenis dan contoh ( setiap jenis sajikan miminal dalam 3 paragraf dengan contoh source code dan pejelasan narative source code 1 atau dua paragraf )
5. implementasi dari setiap contoh ( setiap jenis sajikan miminal dalam 2 paragraf dengan contoh source code dan pejelasan narative source code 1 atau dua paragraf )
6. Kesalahan ( setiap poin kesalahan umum jadikan heading 3 dan setiap heading 3 sajikan miminal dalam 3 paragraf dengan contoh source code yang benar dan salah dan pejelasan narative source code 1 atau dua paragraf , pada akhirnya bentuk  perbandingan dalam bentuk table)
7. Best practice ( buatkan dalam poin kemudian setiap poin di jadikan heading 3 dan setiap heading 3 dijelaskan dalam 3 paragraf )
8. Kesimpulan (dalam 2 paragraf dan di ikuti dalam bentuk poin untuk gagasan utama )
9. Referensi ( gunakan format APA dan kaitkan dengan referensi )

ketentuan :
1. generate poin per poin,
2. jangan keluar dari topik yang di beri tanda kutip pada kalimat pertama karena akan menjadi bahasan pada module lainya.
3. Untuk setiap paragraf dicarikan sitasi ilmiah sehingga tulisan bisa dipertanggungjawabkan secara akademis. 
4. Setiap pargraf terdiri dari 7 kalimat. dan setiap kalimat gunakan bahasa yang mudah di mengerti oleh awam namun tanpa kehilangan subtansi dari pembahasan. 
5. Jangan menggunakan contoh CSS atau JS, 
6. Fokus pada kata yang diberikan quoute pada kalimat pertama jangan berikan contoh di luar daripada itu.

"lanjut tanpa sapaan dan judul awal"

## step 3 generate Metadata 

Isikan metadata yaml dibawah ini  dengan ketentuan berikut
1. pada field tile buat judul yang menarik sesuai dengan artikel diatas
2. pada field outcome, isikan sub field "desc"  berdasarkan kateori konsep atau praktis.
3. isikan field description. dengan deskripsi yang sesuai dengan artikel
4. untuk field date, isikan menggunakan format date hugo lengkap 
5. Jangan rubah selain field yang di deklarasikan di atas
6. isikan kebutuhan untuk module ini pada field requirement, masukan dalam field name kebutuhan dan prop jenis kebutuhan, contoh : field " name: visual code editor", field "prop : "teks editor""

---
date:  ""
draft: false
title: ""
short: "metadata EAD"
thumb:
    image: "cover.jpg"
    anima: ""
    video: ""
layout: ""
weight: 8
lister: 5
format:
    media: "article"
    model: ""
    datum:
        data: ""
outcome:
    - prop: ""
      name: "Konseptual"
      icon: ""
      desc: "" 
    - prop: ""
      name: "Konseptual"
      icon: ""
      desc: "" 
    - prop: ""
      name: "Praktik"
      icon: ""
      desc: "" 
    - prop: ""
      name: "Praktik"
      icon: ""
      desc: "" 
require:
    - prop: ""
      name: ""
      icon: ""
      desc: ""
metadata:
    index: false
    thumb: "cover.jpg"
    group: []
    author: ["null"]
description: ""
---

## kalau diminta bagi

coba buat dalam satu percobaan, saya yakin anda adalah seorang course creator yang mempunyai pengetahuan yang luas, jadi ini akan mudah bagi anda tanpa kehilangan kualitas tulisan