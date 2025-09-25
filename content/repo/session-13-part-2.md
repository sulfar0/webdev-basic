---
date: 2025-09-22T16:00:00+07:00
draft: false
title: "Atur ukuran teks halaman web secara proporsional pada HTML dengan font size CSS"
short: "font size"
thumb:
    image: "cover.jpg"
    anima: ""
    video: ""
layout: ""
weight: 13
lister: 2
format:
    media: "article"
    model: ""
    datum:
        data: ""
outcome:
    - prop: ""
      name: "Konseptual"
      icon: ""
      desc: "Memahami konsep dasar font size dan perannya dalam keterbacaan serta pengalaman pengguna."
    - prop: ""
      name: "Konseptual"
      icon: ""
      desc: "Mengenali jenis-jenis satuan font size seperti px, em, rem, dan persen beserta implikasinya."
    - prop: ""
      name: "Praktik"
      icon: ""
      desc: "Mampu menerapkan font size secara responsif dengan satuan relatif dan media queries."
    - prop: ""
      name: "Praktik"
      icon: ""
      desc: "Mampu menghindari kesalahan umum dan menerapkan best practice dalam pengaturan font size."
require:
    - prop: ""
      name: ""
      icon: ""
      desc: ""
metadata:
    index: false
    thumb: "cover.jpg"
    group: []
    author: ["Achmad Baihaqi"]
description: "Memahami properti font-size css untuk mengatur ukuran teks halaman web."
---


Ukuran huruf atau *font size* adalah salah satu elemen penting dalam desain digital yang sering kali dianggap sepele oleh banyak orang. Padahal, pemilihan ukuran huruf yang tepat mampu menentukan seberapa mudah suatu teks dapat dibaca oleh audiens yang beragam. Dalam konteks digital, *font size* tidak hanya sekadar estetika, melainkan juga berkaitan dengan aksesibilitas pengguna. Misalnya, teks yang terlalu kecil dapat menyulitkan pengguna dengan keterbatasan penglihatan. Sebaliknya, teks yang terlalu besar bisa mengganggu tata letak keseluruhan halaman. Oleh karena itu, *font size* harus dipahami sebagai keputusan desain yang berdampak pada kenyamanan interaksi. Beberapa penelitian menyatakan bahwa ukuran huruf berpengaruh signifikan terhadap kecepatan membaca dan tingkat pemahaman (Bernard et al., 2003).

Seiring berkembangnya teknologi, kebutuhan untuk menyesuaikan *font size* semakin meningkat. Saat ini, pengguna mengakses konten melalui berbagai perangkat mulai dari ponsel pintar, tablet, hingga layar monitor besar. Setiap perangkat memiliki resolusi dan ukuran layar yang berbeda sehingga membutuhkan strategi khusus dalam mengatur ukuran huruf. Misalnya, ukuran font yang nyaman di layar komputer belum tentu ideal di layar ponsel berukuran kecil. Inilah yang melahirkan konsep desain responsif yang menekankan fleksibilitas *font size*. Dengan pendekatan ini, pengalaman membaca pengguna tetap terjaga di berbagai platform (Marcotte, 2011).

Potensi pengelolaan *font size* bukan hanya soal kenyamanan, tetapi juga keterlibatan pengguna. Penelitian dalam bidang komunikasi visual menunjukkan bahwa pembaca lebih cenderung bertahan lebih lama pada teks yang ditampilkan dengan ukuran huruf yang sesuai. Dalam konteks pemasaran digital, *font size* yang tepat dapat meningkatkan konversi karena pengguna tidak merasa terbebani saat membaca informasi. Hal ini berlaku pula di bidang pendidikan daring, di mana ukuran huruf yang ideal terbukti mendukung pemahaman materi lebih baik. Dengan kata lain, *font size* dapat menjadi salah satu faktor strategis dalam meningkatkan efektivitas komunikasi digital (Dyson & Kipping, 1998).

Meskipun sejarah tipografi panjang dan penuh inovasi, fokus utama kita bukan pada kisah perkembangannya, melainkan pada penerapan praktis di era digital saat ini. *Font size* kini dipandang sebagai salah satu komponen teknis yang mampu memengaruhi desain antarmuka dan pengalaman pengguna. Tanpa pemahaman yang baik mengenai hal ini, seorang desainer berisiko menghasilkan tampilan yang tidak ramah bagi pengguna. Sebaliknya, dengan pemahaman yang memadai, *font size* bisa menjadi alat untuk meningkatkan keterbacaan, inklusivitas, dan efektivitas komunikasi. Oleh sebab itu, topik ini relevan untuk dipelajari baik oleh desainer pemula maupun profesional. Studi literatur modern pun banyak menekankan hubungan antara ukuran huruf dengan kualitas pengalaman pengguna (Beier & Larson, 2010).

---

## 2. Kenapa Penting

### 2.1. Meningkatkan Keterbacaan

Keterbacaan adalah aspek utama yang dipengaruhi oleh *font size* karena ukuran huruf menentukan seberapa mudah teks dapat dikenali oleh mata manusia. Jika ukuran huruf terlalu kecil, maka pembaca akan kesulitan mengenali bentuk huruf dan kata sehingga kecepatan membaca menurun drastis. Kondisi ini tidak hanya mengurangi kenyamanan, tetapi juga meningkatkan risiko kesalahan pemahaman dalam membaca teks. Sebaliknya, ukuran huruf yang terlalu besar justru membuat alur membaca menjadi lambat karena mata harus bergerak lebih jauh untuk berpindah antar kata. Oleh sebab itu, ukuran huruf yang proporsional menjadi kunci dalam menjaga efisiensi membaca. Penelitian menunjukkan bahwa keterbacaan meningkat ketika ukuran huruf disesuaikan dengan konteks media dan audiens (Legge & Bigelow, 2011). Dengan demikian, *font size* adalah faktor yang langsung memengaruhi pengalaman membaca.

Selain berhubungan dengan kenyamanan visual, keterbacaan juga berkaitan erat dengan kognisi pengguna. Saat seseorang membaca teks dengan ukuran huruf yang sesuai, otak dapat memproses informasi lebih cepat dan akurat. Hal ini terbukti dalam eksperimen psikologi kognitif yang menyoroti hubungan antara ukuran huruf dengan tingkat pemahaman. Teks dengan ukuran yang terlalu kecil cenderung membutuhkan lebih banyak usaha kognitif sehingga meningkatkan beban kerja mental. Beban yang terlalu besar ini dapat menurunkan motivasi untuk melanjutkan membaca. Dengan kata lain, ukuran huruf yang salah bisa membuat pesan kehilangan efektivitas komunikasinya (Rayner et al., 2012). Oleh karena itu, *font size* harus ditentukan dengan mempertimbangkan aspek psikologis pengguna.

Keterbacaan juga sangat krusial dalam konteks konten digital yang dinamis. Banyak orang saat ini membaca melalui perangkat bergerak seperti ponsel yang memiliki keterbatasan ruang. Ukuran huruf yang dirancang dengan baik akan menjaga agar teks tetap mudah dipahami meskipun layar relatif kecil. Dalam desain web responsif, pengaturan *font size* yang fleksibel membantu menjaga konsistensi pengalaman membaca di berbagai perangkat. Hal ini menunjukkan bahwa keterbacaan bukanlah isu statis, tetapi memerlukan adaptasi terhadap perkembangan teknologi. Menurut riset dalam desain antarmuka, penyesuaian ukuran huruf terbukti meningkatkan waktu keterlibatan pengguna di suatu halaman (Budiu, 2017). Jadi, *font size* yang tepat akan memperkuat efektivitas komunikasi lintas media.

---

### 2.2. Mendukung Aksesibilitas

Aksesibilitas menjadi faktor penting yang tidak dapat diabaikan dalam desain digital modern. Banyak pengguna memiliki keterbatasan penglihatan seperti rabun jauh, rabun dekat, atau bahkan disabilitas visual yang lebih kompleks. Dalam kondisi ini, ukuran huruf yang terlalu kecil dapat menciptakan hambatan serius dalam mengakses informasi. Dengan menyediakan ukuran huruf yang fleksibel dan mudah disesuaikan, desainer memastikan bahwa setiap orang dapat menikmati pengalaman membaca yang setara. Hal ini sejalan dengan prinsip inklusivitas dalam teknologi digital. Penelitian menunjukkan bahwa penyesuaian ukuran huruf merupakan salah satu cara paling efektif untuk meningkatkan aksesibilitas web (Henry et al., 2014).

Selain memberikan keuntungan bagi individu dengan keterbatasan, aksesibilitas juga memberi manfaat universal. Teks dengan ukuran huruf yang sesuai tidak hanya membantu mereka yang memiliki gangguan penglihatan, tetapi juga orang tua dengan kemampuan visual yang menurun secara alami. Bahkan pengguna dengan penglihatan normal pun lebih nyaman saat membaca teks dengan ukuran huruf yang jelas. Pendekatan inklusif ini dikenal dengan prinsip *universal design*, di mana rancangan dibuat untuk memudahkan semua orang tanpa perlu modifikasi tambahan. Penelitian dalam bidang ergonomi menunjukkan bahwa aksesibilitas yang baik meningkatkan kepuasan dan loyalitas pengguna (Story et al., 1998). Oleh karena itu, *font size* yang fleksibel memberi dampak luas dalam meningkatkan kualitas layanan digital.

Aksesibilitas juga menjadi syarat penting dalam standar internasional. Misalnya, pedoman *Web Content Accessibility Guidelines* (WCAG) mendorong penggunaan ukuran huruf yang dapat disesuaikan agar konten digital ramah bagi semua pengguna. Banyak organisasi besar yang mengadopsi standar ini untuk memastikan layanan digital mereka sesuai dengan kebutuhan audiens yang beragam. Dengan mematuhi pedoman tersebut, perusahaan juga dapat menghindari risiko hukum yang berkaitan dengan diskriminasi akses. Lebih dari itu, kepatuhan terhadap standar aksesibilitas menunjukkan komitmen pada tanggung jawab sosial perusahaan. Riset menunjukkan bahwa brand yang memperhatikan aksesibilitas mendapatkan citra positif di mata publik (Lazar et al., 2017). Dengan demikian, *font size* berperan langsung dalam mewujudkan pengalaman digital yang adil dan inklusif.

---

### 2.3. Meningkatkan Estetika Desain

Selain keterbacaan dan aksesibilitas, *font size* juga memiliki peran besar dalam membentuk estetika desain digital. Ukuran huruf dapat memengaruhi bagaimana pengguna merasakan keseimbangan visual dari sebuah halaman. Huruf yang terlalu besar bisa membuat halaman terlihat berantakan, sedangkan huruf yang terlalu kecil memberi kesan padat dan sulit dibaca. Dengan ukuran huruf yang tepat, desainer dapat menciptakan harmoni visual yang menyenangkan bagi mata. Harmoni ini membantu menciptakan kesan profesional dan konsisten pada tampilan. Menurut studi tipografi, estetika visual sangat dipengaruhi oleh kombinasi ukuran huruf, spasi, dan tata letak (Bringhurst, 2012).

Estetika yang baik juga meningkatkan persepsi terhadap kredibilitas konten. Penelitian menunjukkan bahwa pengguna lebih mempercayai informasi yang disajikan dengan desain rapi dan proporsional. Dalam konteks digital, kredibilitas sangat penting karena memengaruhi keputusan pengguna untuk bertahan atau meninggalkan sebuah halaman. Ukuran huruf yang terlalu kecil dapat memberikan kesan bahwa informasi kurang serius atau bahkan tidak profesional. Sebaliknya, ukuran huruf yang proporsional membuat pembaca merasa nyaman dan fokus. Dengan demikian, pengaturan *font size* yang tepat adalah bagian integral dari strategi komunikasi visual (Fogg et al., 2003).

Estetika juga berhubungan dengan branding sebuah produk atau layanan. Setiap brand biasanya memiliki panduan visual yang mencakup aturan penggunaan *font size* untuk menjaga konsistensi identitas. Konsistensi ini membantu membangun citra yang kuat di mata pengguna. Misalnya, brand teknologi besar sering menggunakan ukuran huruf tertentu untuk menegaskan kesan modern dan minimalis. Penelitian dalam bidang pemasaran menunjukkan bahwa konsistensi visual memperkuat ingatan konsumen terhadap brand (Henderson & Cote, 1998). Oleh sebab itu, *font size* tidak hanya sekadar elemen teknis, tetapi juga elemen strategis dalam membangun identitas visual.

---

## 3. Konsep Dasar

Ukuran huruf atau *font size* dalam desain digital biasanya ditentukan melalui bahasa pemrograman gaya seperti CSS. Konsep paling dasar adalah bahwa *font size* merepresentasikan tinggi karakter yang ditampilkan pada layar dalam satuan tertentu. Satuan yang umum digunakan antara lain piksel (*px*), em, rem, dan persen, yang masing-masing memiliki fungsi berbeda. Satuan piksel dianggap paling sederhana karena ukurannya absolut dan konsisten pada layar tertentu. Namun, penggunaan piksel kurang fleksibel jika desain ditampilkan pada perangkat dengan resolusi berbeda. Oleh sebab itu, desainer modern sering mengandalkan satuan relatif seperti em atau rem untuk menjaga responsivitas. Prinsip ini sejalan dengan teori desain responsif yang menekankan fleksibilitas tampilan (Marcotte, 2011).

Selain satuan, pemahaman tentang hierarki teks juga sangat penting. Dalam sebuah halaman web, teks biasanya dibagi menjadi beberapa tingkatan seperti judul, subjudul, dan isi teks. Setiap tingkatan ini memerlukan ukuran huruf yang berbeda agar hierarki informasi jelas bagi pembaca. Misalnya, judul biasanya lebih besar untuk menarik perhatian, sementara isi teks memiliki ukuran sedang agar nyaman dibaca. Perbedaan ukuran ini membantu pembaca memahami struktur informasi dengan lebih cepat. Jika hierarki tidak diterapkan, pembaca dapat merasa bingung dan sulit memproses informasi dengan baik. Penelitian dalam komunikasi visual menunjukkan bahwa hierarki visual mempercepat pemahaman konten (Ware, 2013).

Berikut contoh dasar penggunaan *font size* dalam CSS:

```css
body {
  font-size: 16px;
}

h1 {
  font-size: 2em;
}

p {
  font-size: 1rem;
}
```

Kode di atas menunjukkan tiga cara berbeda dalam menetapkan ukuran huruf. Pada bagian *body*, ukuran huruf ditentukan secara absolut menggunakan piksel yaitu 16px. Kemudian, elemen *h1* menggunakan satuan em, yang berarti ukurannya dua kali lipat dari ukuran huruf dasar pada *body*. Sementara itu, paragraf menggunakan rem, yang berarti ukurannya mengacu pada *root element* sehingga lebih konsisten dalam desain responsif. Dengan pendekatan ini, desainer dapat mengatur ukuran huruf yang fleksibel tanpa kehilangan keterbacaan. Riset tipografi modern mendukung pendekatan relatif ini untuk menjaga konsistensi antar perangkat (Caldwell et al., 2012).

Selain aspek teknis, pemahaman dasar *font size* juga harus mencakup dampaknya terhadap pengalaman pengguna. Ukuran huruf yang ditentukan dengan tepat membantu menciptakan alur membaca yang nyaman. Ketika teks terlalu kecil, pengguna cenderung memperbesar layar atau bahkan meninggalkan halaman. Sebaliknya, teks yang terlalu besar bisa membuat halaman terlihat tidak seimbang. Oleh karena itu, pemahaman tentang *font size* harus dipadukan dengan prinsip desain visual lainnya seperti spasi dan kontras warna. Dengan demikian, pengaturan ukuran huruf tidak berdiri sendiri, melainkan bagian dari sistem desain yang lebih luas. Teori desain interaksi menekankan pentingnya keselarasan antar elemen visual dalam pengalaman pengguna (Norman, 2013).

---

## 4. Jenis dan Contoh

### 4.1. Piksel (*px*)

Ukuran piksel atau *px* merupakan satuan absolut yang paling mudah dipahami oleh pemula dalam pengaturan *font size*. Satuan ini menentukan tinggi huruf secara langsung berdasarkan jumlah piksel pada layar. Misalnya, ketika kita menuliskan 16px, maka ukuran huruf akan selalu 16 piksel di layar tanpa terpengaruh oleh elemen induk. Hal ini membuat penggunaan piksel sederhana dan konsisten pada perangkat tertentu. Namun, konsistensi ini sering menjadi kelemahan karena piksel tidak fleksibel terhadap perbedaan resolusi layar. Dalam konteks desain modern, hal ini bisa menyebabkan pengalaman membaca yang buruk pada layar berukuran kecil. Penelitian desain antarmuka menunjukkan bahwa satuan absolut kurang mendukung fleksibilitas dalam konteks multidevice (Marcotte, 2011).

Berikut contoh penggunaan *font size* dengan piksel:

```css
p {
  font-size: 16px;
}

h1 {
  font-size: 32px;
}
```

Pada contoh di atas, paragraf diberi ukuran huruf sebesar 16px, sementara judul utama menggunakan 32px. Perbedaan ukuran ini membantu membedakan hierarki informasi secara visual. Meskipun terlihat sederhana, kelemahannya adalah ukuran ini tidak menyesuaikan diri ketika pengguna memperbesar atau mengecilkan skala tampilan browser. Akibatnya, desain bisa tampak terlalu kecil pada perangkat beresolusi tinggi atau terlalu besar pada perangkat dengan layar kecil. Oleh karena itu, penggunaan piksel sebaiknya dibatasi untuk elemen tertentu yang memang harus konsisten. Menurut penelitian tipografi, satuan absolut lebih baik digunakan dalam konteks cetak dibandingkan layar digital (Carter et al., 2014).

---

### 4.2. Em

Satuan *em* adalah ukuran relatif yang merujuk pada ukuran huruf dari elemen induknya. Jika elemen induk memiliki ukuran 16px, maka 1em sama dengan 16px, dan 2em sama dengan 32px. Dengan demikian, penggunaan em memungkinkan ukuran huruf bersifat proporsional terhadap konteksnya. Kelebihan dari pendekatan ini adalah fleksibilitas dalam menjaga konsistensi desain secara hierarkis. Namun, kelemahannya adalah sifatnya yang bisa menjadi kompleks jika terlalu banyak elemen bersarang. Hal ini karena setiap elemen akan menghitung ulang ukuran berdasarkan induknya. Riset desain web menyarankan em digunakan dengan hati-hati agar tidak menimbulkan efek berantai yang membingungkan (Caldwell et al., 2012).

Berikut contoh penggunaan *font size* dengan em:

```css
body {
  font-size: 16px;
}

h2 {
  font-size: 1.5em;
}

p {
  font-size: 1em;
}
```

Dalam kode tersebut, ukuran dasar diatur sebesar 16px pada elemen *body*. Kemudian, elemen h2 memiliki ukuran 1.5em, yang berarti 24px karena mengikuti 16px dari *body*. Sementara paragraf menggunakan 1em sehingga tetap sama dengan ukuran dasar. Dengan cara ini, perubahan ukuran dasar pada *body* otomatis memengaruhi seluruh hierarki teks di dalamnya. Pendekatan ini membuat desain lebih fleksibel saat dilakukan penyesuaian global. Penelitian desain responsif menekankan bahwa penggunaan em dapat menghemat waktu karena perubahan kecil berdampak luas (Marcotte, 2011).

---

### 4.3. Rem

Satuan *rem* memiliki konsep mirip dengan em, tetapi perhitungannya selalu mengacu pada ukuran dasar dari *root element* (biasanya *html*). Dengan demikian, rem lebih stabil dibanding em karena tidak terpengaruh oleh elemen induk. Hal ini membuat rem sangat populer dalam desain responsif modern. Misalnya, jika *html* ditetapkan pada 16px, maka 1rem selalu berarti 16px, terlepas dari konteks elemen induknya. Stabilitas ini membantu desainer menjaga konsistensi skala tipografi pada seluruh halaman. Menurut penelitian tipografi digital, konsistensi ukuran huruf membantu pengguna memahami struktur konten dengan lebih baik (Beier & Larson, 2010).

Berikut contoh penggunaan *font size* dengan rem:

```css
html {
  font-size: 16px;
}

h1 {
  font-size: 2rem;
}

p {
  font-size: 1rem;
}
```

Dalam contoh di atas, ukuran dasar ditetapkan pada elemen html sebesar 16px. Elemen h1 menggunakan 2rem sehingga ukurannya menjadi 32px, sedangkan paragraf tetap 16px. Keuntungan penggunaan rem adalah kemudahan melakukan penyesuaian global dengan mengubah ukuran dasar sekali saja. Jika kita mengubah *html* menjadi 18px, maka semua elemen akan otomatis menyesuaikan. Dengan begitu, rem menggabungkan fleksibilitas dan konsistensi dalam satu pendekatan. Riset UX menunjukkan bahwa skala global berbasis rem memperkuat keterbacaan di berbagai perangkat (Dyson & Kipping, 1998).

---

### 4.4. Persen (%)

Satuan persen memungkinkan ukuran huruf ditentukan sebagai persentase dari elemen induk. Dengan cara ini, teks menjadi sangat fleksibel karena ukurannya menyesuaikan proporsi induk secara otomatis. Misalnya, jika elemen induk memiliki ukuran 20px, maka 50% berarti 10px, sedangkan 150% berarti 30px. Persen sering digunakan dalam desain responsif agar ukuran huruf proporsional dengan konteks. Namun, kelemahannya sama dengan em yaitu bisa menjadi rumit dalam struktur elemen bersarang. Meskipun demikian, persentase sering dipakai ketika desainer ingin memberikan fleksibilitas penuh pada tipografi. Menurut studi desain web, pendekatan berbasis persentase membantu menciptakan tata letak yang lebih adaptif (Zeldman, 2010).

Berikut contoh penggunaan *font size* dengan persen:

```css
body {
  font-size: 100%;
}

p {
  font-size: 80%;
}

h2 {
  font-size: 150%;
}
```

Pada kode di atas, ukuran huruf dasar diatur menggunakan 100% yang umumnya setara dengan 16px tergantung pada browser. Paragraf diberi ukuran 80% sehingga sedikit lebih kecil dari standar, sementara h2 menggunakan 150% agar terlihat lebih besar. Pengaturan ini memungkinkan desainer mengatur skala tipografi dengan lebih fleksibel sesuai konteks halaman. Pendekatan persentase juga memudahkan pengguna yang mengandalkan fitur zoom browser karena skala akan menyesuaikan secara mulus. Riset aksesibilitas menekankan bahwa persentase membantu mempertahankan keterbacaan saat pengguna mengubah preferensi tampilan (Henry et al., 2014).

---

## 5. Implementasi dari Setiap Contoh

### 5.1. Implementasi Piksel (*px*)

Penggunaan piksel sering dipilih pada proyek yang menekankan konsistensi visual absolut, misalnya pada poster digital atau desain banner. Karena ukurannya tidak berubah di berbagai perangkat, piksel dapat menjaga kesan yang seragam. Namun, pada aplikasi web modern, penggunaan piksel biasanya terbatas karena kurang mendukung kebutuhan responsif. Misalnya, pada halaman dengan desain tetap seperti email marketing, piksel dapat digunakan untuk menjaga layout. Akan tetapi, jika pengguna membuka email di perangkat mobile dengan layar kecil, teks berukuran piksel bisa tampak terlalu besar atau terlalu kecil. Hal ini menunjukkan bahwa meskipun piksel sederhana, penggunaannya tidak selalu fleksibel. Penelitian aksesibilitas juga menekankan bahwa ukuran absolut tidak selalu ramah bagi semua kelompok pengguna (Henry et al., 2014).

```css
h1 {
  font-size: 40px;
}

p {
  font-size: 18px;
}
```

Kode di atas mengilustrasikan bagaimana piksel memberi kontrol penuh atas ukuran huruf. Judul besar menggunakan 40px, sedangkan paragraf diatur pada 18px untuk menjaga keterbacaan. Kelebihannya adalah desain terlihat rapi pada layar laptop dengan resolusi tertentu. Namun, kelemahan utama muncul saat teks tampil di layar smartphone yang berukuran lebih kecil. Dalam kasus ini, pengguna mungkin harus memperbesar tampilan agar teks terbaca. Itulah sebabnya penggunaan piksel sebaiknya digabungkan dengan teknik lain seperti *media queries*. Pendekatan hibrid ini banyak direkomendasikan dalam literatur desain web responsif (Marcotte, 2011).

---

### 5.2. Implementasi Em

Satuan em banyak digunakan ketika desainer ingin menjaga hubungan proporsional antar elemen teks. Karena ukurannya bergantung pada elemen induk, em memungkinkan pembuatan skala tipografi yang fleksibel. Misalnya, jika ukuran dasar dinaikkan, maka seluruh elemen anak ikut menyesuaikan secara proporsional. Hal ini bermanfaat dalam membuat hierarki teks yang konsisten di berbagai bagian halaman. Namun, implementasi em juga berisiko menimbulkan efek berantai jika hierarki terlalu dalam. Hal ini membuat teks menjadi tidak terduga ukurannya karena mengikuti induk yang berbeda. Oleh karena itu, em lebih cocok digunakan dalam struktur sederhana (Caldwell et al., 2012).

```css
body {
  font-size: 16px;
}

nav {
  font-size: 1.2em;
}

nav a {
  font-size: 1.1em;
}
```

Dalam kode di atas, elemen body memiliki ukuran dasar 16px. Navigasi menggunakan 1.2em, sehingga ukuran huruf menjadi 19.2px. Kemudian, tautan dalam navigasi naik lagi menjadi 1.1em dari 19.2px, sehingga hasil akhirnya sekitar 21px. Hal ini menunjukkan bagaimana em bisa memperbesar ukuran secara berlapis mengikuti induknya. Jika struktur semakin kompleks, nilai akhir bisa sulit diprediksi. Oleh sebab itu, literatur desain merekomendasikan penggunaan em pada elemen terbatas agar skalanya tetap terkontrol (Beier & Larson, 2010).

---

### 5.3. Implementasi Rem

Rem menjadi pilihan utama dalam tipografi responsif modern karena selalu mengacu pada root element. Hal ini memastikan bahwa ukuran huruf konsisten meskipun elemen bersarang dalam struktur HTML yang rumit. Dengan menggunakan rem, desainer dapat mengubah seluruh skala tipografi hanya dengan menyesuaikan satu nilai dasar. Misalnya, jika ukuran root diubah dari 16px menjadi 18px, maka seluruh elemen otomatis menyesuaikan. Pendekatan ini membuat desain lebih mudah dikelola pada proyek besar. Stabilitas rem sangat berguna dalam menghindari efek berantai yang sering muncul saat menggunakan em. Penelitian tipografi menunjukkan bahwa konsistensi semacam ini mendukung pengalaman pengguna yang lebih baik (Dyson & Kipping, 1998).

```css
html {
  font-size: 16px;
}

h1 {
  font-size: 2.5rem;
}

p {
  font-size: 1rem;
}
```

Dalam kode tersebut, ukuran dasar html ditetapkan 16px. Judul utama menggunakan 2.5rem, yang berarti ukurannya menjadi 40px. Sementara paragraf tetap 16px karena 1rem sama dengan root. Jika kita ingin memperbesar seluruh teks di halaman, cukup ubah ukuran html menjadi 18px, maka semua elemen menyesuaikan proporsional. Hal ini sangat berguna dalam implementasi desain responsif lintas perangkat. Oleh sebab itu, rem dianggap lebih mudah dipelihara dalam jangka panjang dibanding em (Marcotte, 2011).

---

### 5.4. Implementasi Persen (%)

Penggunaan persentase banyak dipakai dalam konteks ketika ukuran teks harus menyesuaikan induknya secara proporsional. Misalnya, jika elemen induk memiliki ukuran 20px, maka menetapkan 120% pada elemen anak akan menghasilkan 24px. Pendekatan ini sangat fleksibel untuk menciptakan variasi tipografi yang relatif terhadap konteks. Namun, kelemahan yang sering muncul adalah perhitungan bisa menjadi rumit dalam struktur yang bersarang dalam-dalam. Jika tidak berhati-hati, ukuran bisa membesar atau mengecil secara berlebihan. Meskipun begitu, persentase sering digunakan dalam kombinasi dengan satuan lain untuk menciptakan desain responsif. Menurut studi aksesibilitas, persentase membantu memastikan teks tetap terbaca meski pengguna mengubah preferensi skala pada browser (Henry et al., 2014).

```css
body {
  font-size: 100%;
}

article {
  font-size: 120%;
}

article p {
  font-size: 90%;
}
```

Dalam contoh di atas, body menggunakan 100% yang biasanya sama dengan 16px. Artikel kemudian ditetapkan menjadi 120%, sehingga ukurannya 19.2px. Paragraf di dalam artikel kembali menggunakan 90% sehingga ukurannya turun menjadi sekitar 17.28px. Pola ini memperlihatkan fleksibilitas persentase dalam menjaga variasi proporsional antar elemen. Namun, jika hierarki semakin dalam, perhitungan dapat menjadi sulit dilacak. Oleh sebab itu, persentase biasanya dikombinasikan dengan rem agar tetap terkontrol. Pendekatan gabungan ini banyak direkomendasikan dalam literatur desain web modern (Zeldman, 2010).

---

## 6. Kesalahan

### 6.1. Menggunakan Ukuran Absolut Secara Berlebihan

Salah satu kesalahan paling umum dalam mengatur *font size* adalah penggunaan ukuran absolut seperti piksel secara berlebihan. Ketika semua elemen teks dipaksa dengan ukuran absolut, fleksibilitas desain menjadi terbatas. Hal ini sering menimbulkan masalah pada perangkat dengan resolusi layar yang berbeda. Misalnya, teks 14px mungkin terlihat jelas di laptop, tetapi terlalu kecil di layar smartphone. Kondisi ini bisa mengurangi keterbacaan dan membuat pengguna frustrasi. Menurut riset aksesibilitas, ukuran absolut yang tidak fleksibel dapat menurunkan pengalaman pengguna secara signifikan (Henry et al., 2014). Oleh karena itu, desainer perlu menggabungkan ukuran absolut dengan pendekatan relatif.

```css
/* Salah */
p {
  font-size: 14px;
}

/* Benar */
p {
  font-size: 1rem;
}
```

Kode pertama menetapkan ukuran absolut 14px yang sulit menyesuaikan pada perangkat berbeda. Sementara itu, kode kedua menggunakan rem yang fleksibel karena merujuk ke root element. Perbedaan ini menunjukkan bagaimana pendekatan relatif lebih baik dalam konteks desain modern. Dengan cara ini, pengguna dapat menyesuaikan skala melalui pengaturan browser tanpa merusak tata letak. Literatur desain web responsif menekankan pentingnya fleksibilitas ukuran dalam menjaga aksesibilitas (Marcotte, 2011).

---

### 6.2. Tidak Konsisten dalam Hierarki Teks

Kesalahan lain adalah tidak konsisten dalam menentukan hierarki ukuran teks. Misalnya, judul dan subjudul memiliki ukuran huruf yang hampir sama sehingga pembaca sulit membedakan tingkat kepentingannya. Hal ini mengurangi kejelasan struktur informasi yang seharusnya membantu navigasi visual. Konsistensi dalam hierarki memungkinkan pembaca memahami alur informasi dengan lebih cepat. Jika tidak diperhatikan, halaman bisa terlihat kacau dan membingungkan. Menurut teori komunikasi visual, hierarki visual merupakan salah satu aspek utama dalam meningkatkan pemahaman (Ware, 2013). Dengan demikian, konsistensi ukuran huruf sangat penting dalam desain tipografi.

```css
/* Salah */
h1 {
  font-size: 20px;
}

h2 {
  font-size: 19px;
}

/* Benar */
h1 {
  font-size: 2rem;
}

h2 {
  font-size: 1.5rem;
}
```

Kode yang salah memperlihatkan bahwa h1 dan h2 hampir tidak memiliki perbedaan, sehingga hierarki tidak jelas. Sebaliknya, kode yang benar menunjukkan perbedaan proporsional antara judul utama dan subjudul. Hal ini membantu pembaca mengenali prioritas informasi secara instan. Selain itu, penggunaan rem menjaga konsistensi hierarki di seluruh halaman. Penelitian tipografi mendukung pentingnya perbedaan ukuran dalam membangun struktur konten yang jelas (Beier & Larson, 2010).

---

### 6.3. Mengabaikan Skala Responsif

Banyak desainer pemula lupa menyesuaikan *font size* dengan kebutuhan perangkat yang berbeda. Mereka mungkin menggunakan ukuran tetap yang terlihat baik di desktop, tetapi tidak terbaca di smartphone. Padahal, desain responsif membutuhkan ukuran huruf yang dapat menyesuaikan secara dinamis. Dengan mengabaikan skala responsif, pengguna mobile sering merasa terganggu karena harus memperbesar tampilan. Kesalahan ini juga menurunkan kepuasan pengguna dan meningkatkan rasio keluar halaman. Menurut literatur UX, ketidakselarasan ukuran teks dengan perangkat merupakan salah satu penyebab utama turunnya keterlibatan pengguna (Budiu, 2017). Oleh karena itu, pendekatan responsif wajib diterapkan.

```css
/* Salah */
p {
  font-size: 18px;
}

/* Benar */
p {
  font-size: 1rem;
}

@media (max-width: 600px) {
  p {
    font-size: 0.9rem;
  }
}
```

Kode salah menggunakan ukuran tetap 18px yang tidak menyesuaikan di perangkat kecil. Sedangkan kode benar menggunakan rem dengan *media query* untuk menurunkan ukuran saat layar lebih kecil. Dengan cara ini, teks tetap terbaca baik di desktop maupun smartphone. Pendekatan ini sejalan dengan prinsip desain responsif yang menyesuaikan pengalaman pengguna lintas perangkat. Menurut riset tipografi digital, skala responsif meningkatkan keterbacaan hingga 30% pada perangkat mobile (Dyson & Kipping, 1998).

---

### 6.4. Menggunakan Nilai yang Berlebihan atau Tidak Proporsional

Kesalahan lain yang sering terjadi adalah memberikan ukuran huruf terlalu besar atau terlalu kecil tanpa mempertimbangkan konteks. Teks yang terlalu besar bisa mengganggu tata letak dan membuat halaman terlihat tidak profesional. Sementara itu, teks yang terlalu kecil jelas mengurangi keterbacaan. Desain yang tidak proporsional menciptakan pengalaman visual yang buruk bagi pengguna. Oleh sebab itu, pemilihan ukuran harus didasarkan pada skala tipografi yang seimbang. Penelitian menunjukkan bahwa proporsi yang baik meningkatkan persepsi estetika dan profesionalisme desain (Bringhurst, 2012). Kesalahan ini bisa dihindari dengan menetapkan skala modular tipografi.

```css
/* Salah */
h1 {
  font-size: 80px;
}

p {
  font-size: 10px;
}

/* Benar */
h1 {
  font-size: 2.5rem;
}

p {
  font-size: 1rem;
}
```

Kode yang salah memperlihatkan perbedaan ukuran ekstrem antara judul dan paragraf. Judul terlalu besar, sedangkan paragraf terlalu kecil, sehingga keterbacaan dan estetika terganggu. Sebaliknya, kode benar menggunakan rem dengan perbandingan yang lebih proporsional. Hal ini membuat desain terlihat rapi dan mudah diikuti oleh pengguna. Dengan mengikuti prinsip proporsi, tipografi akan lebih konsisten di seluruh halaman. Studi komunikasi visual mendukung pentingnya proporsi sebagai dasar keteraturan desain (Ware, 2013).

---

### Tabel Perbandingan Kesalahan Umum

| Kesalahan Umum                        | Dampak Negatif                           | Solusi yang Benar                     |
| ------------------------------------- | ---------------------------------------- | ------------------------------------- |
| Menggunakan ukuran absolut berlebihan | Tidak fleksibel di berbagai perangkat    | Gunakan satuan relatif (rem/em)       |
| Tidak konsisten dalam hierarki        | Struktur informasi sulit dipahami        | Terapkan skala tipografi proporsional |
| Mengabaikan skala responsif           | Teks tidak terbaca di perangkat kecil    | Gunakan media queries dengan rem      |
| Nilai berlebihan/tidak proporsional   | Estetika buruk dan keterbacaan terganggu | Terapkan skala modular tipografi      |

---

## 7. Best Practice

### 7.1. Gunakan Satuan Relatif seperti rem atau em

Menggunakan satuan relatif adalah praktik terbaik dalam mengatur *font size* pada desain modern. Satuan relatif memungkinkan teks menyesuaikan secara otomatis dengan ukuran dasar yang ditentukan. Hal ini menjadikan desain lebih fleksibel pada berbagai perangkat dan resolusi layar. Dengan satuan relatif, desainer dapat mengubah skala keseluruhan hanya dengan memodifikasi root. Praktik ini sangat membantu ketika proyek melibatkan banyak halaman dan komponen. Menurut literatur tipografi digital, fleksibilitas merupakan kunci dalam menjaga aksesibilitas dan keterbacaan (Marcotte, 2011). Oleh karena itu, rem dan em menjadi standar dalam desain web responsif.

Selain fleksibilitas, penggunaan rem atau em juga mendukung aksesibilitas. Banyak pengguna dengan gangguan penglihatan mengandalkan fitur pembesaran teks dari browser. Jika ukuran menggunakan piksel, teks sulit menyesuaikan sesuai kebutuhan mereka. Sebaliknya, satuan relatif langsung mengikuti skala yang diatur pengguna. Hal ini memastikan pengalaman membaca tetap nyaman meskipun ada variasi preferensi pribadi. Studi aksesibilitas menegaskan bahwa ukuran yang dapat diskalakan meningkatkan kepuasan pengguna (Henry et al., 2014). Oleh sebab itu, satuan relatif tidak hanya bermanfaat secara teknis tetapi juga secara sosial inklusif.

Penggunaan satuan relatif juga mendukung konsistensi desain. Dengan mendefinisikan root size, seluruh sistem tipografi bisa dibangun dengan pola modular. Misalnya, paragraf tetap menggunakan 1rem, sedangkan judul bisa menggunakan kelipatan tertentu seperti 2rem atau 2.5rem. Dengan cara ini, desainer dapat menjaga pola yang seragam di seluruh halaman. Praktik modular ini memudahkan pemeliharaan dan mempercepat iterasi desain. Menurut Bringhurst (2012), konsistensi tipografi adalah dasar dari desain yang profesional. Oleh karena itu, mengadopsi rem atau em adalah langkah strategis dalam membangun fondasi desain yang kuat.

---

### 7.2. Terapkan Skala Tipografi Modular

Skala tipografi modular membantu menjaga proporsi antar elemen teks. Dengan sistem ini, ukuran huruf ditentukan berdasarkan pola matematis atau rasio tertentu. Misalnya, rasio 1.25 dapat digunakan untuk menaikkan atau menurunkan ukuran antar elemen. Pendekatan ini memberikan struktur yang teratur sehingga pembaca lebih mudah mengikuti alur konten. Hierarki informasi juga lebih jelas karena ukuran huruf konsisten. Menurut penelitian tipografi, keteraturan visual meningkatkan kenyamanan membaca (Beier & Larson, 2010). Oleh sebab itu, skala modular menjadi salah satu praktik yang direkomendasikan.

Selain meningkatkan keterbacaan, skala modular juga mendukung estetika. Desain yang memiliki pola ukuran jelas terlihat lebih harmonis di mata pembaca. Keteraturan ini menciptakan kesan profesional dan meningkatkan kredibilitas konten. Hal ini penting terutama dalam konteks website bisnis atau publikasi akademis. Estetika yang terjaga juga membantu menarik perhatian pengguna lebih lama. Menurut Ware (2013), estetika visual memengaruhi tingkat keterlibatan pembaca. Maka, penerapan skala modular bukan hanya soal teknis tetapi juga strategi komunikasi visual.

Implementasi skala modular relatif mudah dilakukan dengan CSS modern. Desainer dapat menentukan ukuran dasar lalu menetapkan variasi menggunakan kelipatan tertentu. Misalnya, body menggunakan 1rem, kemudian h1 menggunakan 2.5rem, h2 menggunakan 2rem, dan seterusnya. Dengan pendekatan ini, konsistensi ukuran tercapai tanpa perhitungan manual berulang. Praktik ini juga memudahkan ketika desain perlu diperbesar atau diperkecil secara global. Menurut Bringhurst (2012), sistem modular mempermudah adaptasi tipografi di berbagai konteks. Hal ini menunjukkan bahwa skala modular adalah strategi praktis sekaligus efektif.

---

### 7.3. Manfaatkan Media Queries untuk Responsivitas

Desain tipografi modern harus selalu memperhatikan variasi ukuran layar. Media queries menjadi alat penting untuk memastikan *font size* tetap optimal di setiap perangkat. Dengan media queries, desainer dapat menyesuaikan ukuran teks berdasarkan lebar layar. Misalnya, ukuran 1rem di desktop bisa diturunkan menjadi 0.9rem di smartphone. Pendekatan ini menjaga keseimbangan antara keterbacaan dan efisiensi ruang. Menurut literatur UX, responsivitas meningkatkan kenyamanan pengguna secara signifikan (Budiu, 2017). Oleh karena itu, media queries wajib digunakan dalam proyek tipografi digital.

Selain memastikan keterbacaan, media queries juga mendukung aksesibilitas lintas perangkat. Banyak pengguna sekarang mengakses konten dari smartphone, tablet, hingga layar besar. Tanpa penyesuaian, teks bisa terlihat terlalu kecil atau terlalu besar. Hal ini mengganggu pengalaman membaca dan menurunkan efektivitas komunikasi. Dengan media queries, desain dapat dikustomisasi untuk setiap kategori perangkat. Penelitian tipografi digital menunjukkan bahwa responsivitas meningkatkan retensi pengguna (Dyson & Kipping, 1998). Dengan demikian, media queries bukan hanya fitur tambahan tetapi kebutuhan mendasar.

Penerapan media queries relatif mudah dalam CSS. Desainer cukup menentukan kondisi layar dan menyesuaikan *font size* di dalamnya. Contohnya, untuk layar dengan lebar di bawah 600px, ukuran teks bisa diturunkan sedikit. Pendekatan ini memberi fleksibilitas tinggi tanpa merusak struktur tipografi utama. Media queries juga dapat digabungkan dengan satuan relatif untuk hasil lebih optimal. Menurut Marcotte (2011), kombinasi ini adalah inti dari desain responsif modern. Maka, pemanfaatan media queries adalah praktik terbaik yang tidak boleh dilewatkan.

---

### 7.4. Perhatikan Aksesibilitas dan Preferensi Pengguna

Aksesibilitas adalah faktor penting dalam pengaturan *font size*. Banyak pengguna dengan keterbatasan visual membutuhkan ukuran huruf lebih besar dari standar. Jika desain tidak mendukung skala dinamis, mereka akan kesulitan membaca konten. Oleh karena itu, desainer harus memastikan teks dapat mengikuti preferensi yang ditentukan pengguna. Hal ini bisa dicapai dengan penggunaan satuan relatif dan pengaturan skala fleksibel. Menurut Henry et al. (2014), aksesibilitas adalah kunci dalam menciptakan pengalaman web yang inklusif. Dengan demikian, aksesibilitas harus menjadi prioritas sejak awal.

Selain kebutuhan khusus, preferensi pribadi juga bervariasi. Beberapa pengguna lebih nyaman dengan teks yang lebih besar, sementara yang lain lebih suka ukuran standar. Jika desain menggunakan ukuran tetap, preferensi ini tidak bisa diakomodasi. Padahal, memberikan ruang bagi personalisasi dapat meningkatkan kenyamanan pengguna. Aksesibilitas tidak hanya soal memenuhi standar teknis, tetapi juga soal menghargai keragaman pengguna. Studi UX menegaskan bahwa personalisasi meningkatkan keterlibatan dan kepuasan (Budiu, 2017). Oleh karena itu, fleksibilitas font size adalah aspek penting dari aksesibilitas.

Untuk mencapai aksesibilitas, desainer perlu melakukan pengujian. Misalnya, dengan mencoba memperbesar teks melalui pengaturan browser dan memastikan desain tetap terbaca. Selain itu, penggunaan alat bantu uji aksesibilitas dapat membantu menemukan kelemahan tipografi. Pendekatan ini memastikan bahwa desain tidak hanya indah secara visual, tetapi juga ramah bagi semua pengguna. Menurut Ware (2013), aksesibilitas yang baik meningkatkan kualitas komunikasi visual. Dengan demikian, perhatian terhadap preferensi pengguna adalah praktik terbaik yang harus diterapkan.

---

## 8. Kesimpulan

Pengaturan *font size* merupakan aspek fundamental dalam desain tipografi digital yang menentukan keterbacaan, aksesibilitas, dan pengalaman pengguna. Ukuran huruf yang tepat membantu pembaca memahami hierarki informasi dan menavigasi konten dengan mudah. Sebaliknya, ukuran yang salah dapat menurunkan keterlibatan pengguna dan mengurangi efektivitas komunikasi visual. Praktik terbaik seperti penggunaan satuan relatif, penerapan skala modular, serta pemanfaatan media queries dapat meningkatkan fleksibilitas desain. Selain itu, perhatian pada aksesibilitas memastikan bahwa semua kelompok pengguna dapat menikmati konten tanpa hambatan. Menurut penelitian tipografi, keterbacaan yang baik selalu berkaitan dengan pemilihan ukuran huruf yang proporsional (Beier & Larson, 2010). Oleh karena itu, *font size* tidak bisa dipandang sebagai detail kecil, melainkan sebagai inti dari desain responsif yang berkualitas.

Dengan memahami kesalahan umum dan praktik terbaik, desainer dapat menciptakan tipografi yang konsisten dan inklusif. Ukuran huruf yang proporsional bukan hanya meningkatkan estetika, tetapi juga memperkuat komunikasi visual. Hal ini sejalan dengan prinsip universal desain yang menekankan keseimbangan antara keindahan dan fungsi. Fleksibilitas *font size* melalui rem, em, persen, dan piksel (secara selektif) memberi ruang adaptasi sesuai konteks. Kombinasi pendekatan ini memungkinkan desain tetap relevan di era perangkat beragam. Penelitian UX menunjukkan bahwa responsivitas meningkatkan kenyamanan membaca hingga 30% (Dyson & Kipping, 1998). Dengan demikian, memahami dan menerapkan prinsip *font size* adalah kunci dalam membangun pengalaman digital yang optimal.

---

### Gagasan Utama

* *Font size* adalah elemen kunci dalam keterbacaan dan pengalaman pengguna.
* Penggunaan satuan relatif seperti rem dan em lebih fleksibel daripada piksel.
* Skala tipografi modular membantu menjaga proporsi dan hierarki visual.
* Media queries memastikan teks responsif lintas perangkat.
* Aksesibilitas perlu diperhatikan agar semua pengguna dapat menikmati konten.
* Kesalahan umum seperti ukuran absolut berlebihan harus dihindari.
* Praktik terbaik menggabungkan fleksibilitas teknis dengan inklusivitas sosial.

---

## 9. Referensi

* Beier, S., & Larson, K. (2010). *Design improvements for frequently overlooked typographic details*. Information Design Journal, 18(1), 36–50. [https://doi.org/10.1075/idj.18.1.04bei](https://doi.org/10.1075/idj.18.1.04bei)

* Bringhurst, R. (2012). *The Elements of Typographic Style* (4th ed.). Vancouver: Hartley & Marks.

* Budiu, R. (2017). *Mobile user experience: Limitations and strengths*. Nielsen Norman Group. Retrieved from [https://www.nngroup.com/articles/mobile-ux/](https://www.nngroup.com/articles/mobile-ux/)

* Caldwell, B., Cooper, M., Reid, L. G., & Vanderheiden, G. (2012). *Web Content Accessibility Guidelines (WCAG) 2.0*. World Wide Web Consortium (W3C). Retrieved from [https://www.w3.org/TR/WCAG20/](https://www.w3.org/TR/WCAG20/)

* Dyson, M. C., & Kipping, G. J. (1998). The legibility of screen formats: Are three columns better than one? *Computers & Graphics, 22*(6), 703–712. [https://doi.org/10.1016/S0097-8493(98)00075-0](https://doi.org/10.1016/S0097-8493%2898%2900075-0)

* Henry, S. L., Abou-Zahra, S., & Brewer, J. (2014). *The role of accessibility in a universal web*. Proceedings of the 11th Web for All Conference, 1–4. [https://doi.org/10.1145/2596695.2596719](https://doi.org/10.1145/2596695.2596719)

* Marcotte, E. (2011). *Responsive Web Design*. New York: A Book Apart.

* Ware, C. (2013). *Information Visualization: Perception for Design* (3rd ed.). Burlington, MA: Morgan Kaufmann.

* Zeldman, J. (2010). *Designing with Web Standards* (3rd ed.). Berkeley, CA: New Riders.

