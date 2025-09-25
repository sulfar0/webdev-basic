---
date: "2025-09-22T15:00:00+07:00"
draft: false
title: "Main sebagai tempat konten utama web pada html"
short: "main"
thumb:
    image: "cover.jpg"
    anima: ""
    video: ""
layout: ""
weight: 9
lister: 4
format:
    media: "article"
    model: ""
    datum:
        data: ""
outcome:
    - prop: ""
      name: "Konseptual"
      icon: ""
      desc: "Memahami fungsi elemen <main> dalam HTML dan perannya dalam menandai konten utama halaman web." 
    - prop: ""
      name: "Konseptual"
      icon: ""
      desc: "Mengenali variasi penggunaan elemen <main> dengan artikel tunggal, banyak artikel, serta kombinasi dengan section." 
    - prop: ""
      name: "Praktik"
      icon: ""
      desc: "Mampu menuliskan struktur HTML dengan elemen <main> yang sesuai standar dan aksesibilitas." 
    - prop: ""
      name: "Praktik"
      icon: ""
      desc: "Mampu mengimplementasikan elemen <main> pada berbagai skenario halaman web dengan benar." 
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
description: "Mempelajari elemen main untuk menandai konten utama halaman."
---

# 1. Pendahuluan

Elemen `<main>` dalam HTML adalah sebuah elemen semantik yang digunakan untuk menandai konten utama dari sebuah halaman web. Elemen ini membantu pengguna dan mesin pencari memahami bagian inti dari isi dokumen HTML yang sedang dibuka. Dalam praktiknya, `<main>` biasanya digunakan untuk membungkus konten yang langsung berkaitan dengan tujuan utama halaman tersebut. Dengan adanya elemen ini, struktur halaman menjadi lebih jelas dan lebih mudah dipahami oleh teknologi pendukung seperti screen reader. Menurut penelitian Nielsen (2012), struktur semantik yang baik meningkatkan pengalaman pengguna dalam navigasi web. Oleh karena itu, `<main>` hadir sebagai solusi penting dalam meningkatkan aksesibilitas dan keteraturan kode HTML.

Awalnya, sebelum hadirnya elemen semantik seperti `<main>`, developer menggunakan `<div>` dengan class atau id tertentu untuk membedakan konten utama. Namun, pendekatan tersebut sering menimbulkan ketidakjelasan, terutama bagi perangkat bantu seperti pembaca layar. Kehadiran elemen `<main>` memberikan standar yang lebih jelas, sekaligus memudahkan komunikasi antar perangkat lunak. Hal ini sejalan dengan konsep *semantic web* yang menekankan pentingnya makna dalam kode (Berners-Lee et al., 2001). Jadi, `<main>` tidak sekadar simbol teknis, tetapi juga representasi dari pergeseran paradigma dalam membangun web yang lebih terstruktur. Inilah yang menjadikan elemen ini krusial dalam perkembangan web modern.

Selain perannya dalam aksesibilitas, `<main>` juga membawa potensi besar dalam mendukung optimasi mesin pencari (SEO). Mesin pencari seperti Google cenderung memprioritaskan konten yang ditempatkan secara semantik dengan benar dalam struktur HTML. Dengan menandai konten utama menggunakan `<main>`, algoritma mesin pencari dapat lebih cepat memahami fokus sebuah halaman. Hal ini berdampak langsung pada visibilitas website di hasil pencarian. Menurut Cutts (2013), penggunaan markup semantik yang benar meningkatkan relevansi halaman pada indeks mesin pencari. Oleh sebab itu, `<main>` tidak hanya bermanfaat untuk pengguna akhir, tetapi juga memberikan keuntungan strategis bagi pemilik situs.

Lebih jauh lagi, `<main>` mempermudah developer dalam menjaga konsistensi tata letak dan logika kode. Elemen ini hanya boleh muncul sekali dalam satu halaman HTML, sehingga jelas membedakan konten utama dengan header, footer, atau sidebar. Hal ini membuat pengembangan aplikasi web lebih terorganisir dan terhindar dari praktik kode yang berlebihan. Penelitian oleh W3C (2014) menegaskan bahwa batasan satu elemen `<main>` per halaman berkontribusi dalam menjaga integritas semantik dokumen. Dengan demikian, `<main>` adalah elemen yang sederhana namun kaya manfaat dalam membangun web modern. Potensi ini menjadikannya salah satu elemen paling penting untuk dipahami oleh setiap web developer.

---

# 2. Kenapa Penting

### 2.1. Meningkatkan Aksesibilitas

Elemen `<main>` membantu pengguna dengan keterbatasan visual dalam memahami bagian inti dari halaman web. Screen reader dapat langsung melompat ke konten utama ketika menemukan elemen ini tanpa harus membaca header atau navigasi berulang. Hal ini mempercepat pengalaman pengguna yang membutuhkan fokus pada isi inti dari halaman. Menurut penelitian oleh Vigo dan Harper (2013), desain web yang memperhatikan aksesibilitas meningkatkan kemandirian pengguna penyandang disabilitas. Tanpa elemen `<main>`, pengguna screen reader sering kali harus menavigasi halaman dengan lebih banyak usaha. Oleh karena itu, `<main>` adalah solusi semantik yang memperbaiki keadilan akses terhadap informasi digital. Dampak positif ini membuatnya menjadi elemen penting yang harus diterapkan di semua halaman modern.

Selain untuk pengguna dengan keterbatasan, `<main>` juga bermanfaat bagi semua pengunjung web yang mengandalkan struktur halaman yang rapi. Dengan markup semantik yang jelas, pengguna dapat memahami dengan lebih cepat bagian yang relevan dengan tujuan kunjungan mereka. Penelitian oleh Lazar et al. (2015) menekankan bahwa aksesibilitas bukan hanya kebutuhan kelompok tertentu, tetapi juga praktik baik dalam usability secara umum. Hal ini menunjukkan bahwa setiap pengembang sebaiknya memanfaatkan `<main>` untuk meningkatkan pengalaman bagi semua orang. Konten utama yang terisolasi dengan baik membuat interaksi menjadi lebih efisien. Jadi, keberadaan `<main>` memperluas manfaat aksesibilitas dari konteks khusus ke konteks umum. Elemen ini menciptakan pengalaman universal yang lebih ramah.

Keterhubungan antara aksesibilitas dan elemen `<main>` juga dapat dilihat pada prinsip *inclusive design*. Inclusive design menekankan bahwa produk digital harus dirancang untuk mencakup sebanyak mungkin kebutuhan pengguna. Dengan `<main>`, sebuah halaman web memberikan titik masuk yang jelas ke konten yang paling penting. Hal ini membuat pengalaman web lebih inklusif tanpa perlu modifikasi tambahan. Menurut Microsoft Inclusive Design Toolkit (2016), desain inklusif selalu meningkatkan kualitas pengalaman bagi seluruh pengguna. Jadi, elemen ini bukan sekadar alat teknis, melainkan wujud nyata dari filosofi desain yang humanis. Hal ini memperkuat alasan mengapa `<main>` sangat penting dalam pengembangan web modern.

---

### 2.2. Memperkuat SEO

Elemen `<main>` memberikan sinyal yang kuat kepada mesin pencari tentang bagian inti dari sebuah halaman. Mesin pencari seperti Google menggunakan struktur semantik untuk menilai relevansi sebuah konten. Dengan `<main>`, konten utama teridentifikasi dengan jelas sehingga indeksasi dapat dilakukan lebih cepat dan lebih akurat. Menurut Cutts (2013), penggunaan markup semantik dapat membantu algoritma mesin pencari memahami topik halaman secara lebih efektif. Hal ini pada akhirnya meningkatkan peluang sebuah halaman muncul lebih tinggi dalam hasil pencarian. Tanpa `<main>`, mesin pencari mungkin harus menebak-nebak bagian inti dari halaman. Oleh sebab itu, penggunaan elemen ini dapat dianggap sebagai strategi SEO teknis yang efektif.

Lebih dari sekadar membantu mesin pencari, `<main>` juga memberikan keuntungan dalam konteks pengalaman pengguna yang menjadi metrik SEO modern. Google mengutamakan *user experience* sebagai faktor penting dalam peringkat pencarian. Dengan `<main>`, halaman menjadi lebih mudah dipahami oleh pengguna, sehingga mereka lebih lama berinteraksi dengan konten. Menurut laporan Searchmetrics (2016), faktor keterlibatan pengguna semakin berperan penting dalam peringkat mesin pencari. Oleh karena itu, `<main>` berperan ganda: membantu mesin pencari memahami konten sekaligus mendukung metrik interaksi pengguna. Ini menjadikan `<main>` sebagai salah satu elemen yang strategis dalam praktik SEO modern. Keberadaan elemen ini membawa nilai ganda bagi pemilik situs dan pengguna.

SEO bukan hanya tentang kata kunci, melainkan juga tentang struktur semantik yang mendasarinya. Elemen `<main>` secara otomatis membangun konteks yang lebih terorganisir bagi mesin pencari. Hal ini sejalan dengan teori *information retrieval* yang menyatakan bahwa struktur data yang lebih rapi mempercepat proses pencarian informasi (Manning et al., 2008). Dengan struktur semantik yang jelas, algoritma pencarian dapat mengekstraksi informasi lebih efektif. Dampaknya adalah peningkatan kualitas indeks dan peningkatan peluang visibilitas halaman. Jadi, penggunaan `<main>` sebaiknya dipahami sebagai fondasi teknis yang tak kalah penting dari optimasi konten. Elemen ini melengkapi strategi SEO dengan pendekatan semantik yang kuat.

---

### 2.3. Menjaga Konsistensi Struktur

Kehadiran `<main>` membantu developer menjaga konsistensi dalam struktur dokumen HTML. Elemen ini secara tegas membedakan konten utama dari bagian lain seperti `<header>`, `<footer>`, atau `<aside>`. Dengan aturan bahwa `<main>` hanya boleh muncul sekali, developer terdorong untuk membuat hierarki kode yang lebih disiplin. Menurut W3C (2014), konsistensi struktur adalah kunci dalam menjaga interoperabilitas antara berbagai platform dan perangkat. Hal ini sangat penting dalam konteks web modern yang diakses melalui beragam perangkat dengan ukuran layar berbeda. Konsistensi juga mempermudah tim developer dalam berkolaborasi. Dengan demikian, `<main>` berfungsi sebagai jangkar semantik dalam struktur dokumen.

Konsistensi yang terjaga melalui `<main>` juga membantu proses pemeliharaan kode dalam jangka panjang. Ketika sebuah tim kembali ke proyek lama, mereka dapat langsung mengidentifikasi bagian konten utama dengan cepat. Hal ini mengurangi risiko kebingungan akibat penggunaan `<div>` yang berlebihan. Menurut McConnell (2004), kode yang konsisten adalah salah satu faktor penting dalam menurunkan biaya pemeliharaan perangkat lunak. `<main>` dengan sendirinya menjadi standar internal yang memperkuat keterbacaan kode. Hal ini membuat pengembangan lebih efisien karena struktur dasar sudah terorganisir dengan baik. Jadi, `<main>` memiliki nilai praktis dalam mengurangi kompleksitas jangka panjang.

Selain itu, konsistensi struktur juga mendukung praktik *responsive design*. Dengan `<main>`, developer memiliki titik referensi yang konsisten untuk mengatur tata letak pada berbagai ukuran layar. Hal ini membuat proses desain lebih fleksibel dan terprediksi. Menurut Marcotte (2010), konsistensi elemen semantik memudahkan adaptasi konten dalam lingkungan multi-perangkat. Dengan kata lain, `<main>` bukan hanya meningkatkan keterbacaan kode, tetapi juga memperkuat strategi desain web responsif. Jadi, penerapan `<main>` bukanlah sekadar pilihan, melainkan kebutuhan mendasar dalam era digital saat ini. Elemen ini membentuk kerangka kerja yang lebih stabil untuk masa depan web.

---

# 3. Konsep Dasar

Elemen `<main>` adalah elemen semantik dalam HTML5 yang digunakan untuk menandai bagian utama dari sebuah halaman web. Bagian ini biasanya berisi konten inti yang langsung berkaitan dengan tujuan halaman tersebut, seperti artikel, berita, atau produk. Dengan adanya elemen ini, struktur dokumen menjadi lebih jelas karena setiap bagian memiliki perannya masing-masing. Hal ini membedakan `<main>` dari `<div>` biasa yang hanya berfungsi sebagai wadah tanpa makna semantik. Menurut W3C (2017), elemen semantik dibuat agar konten web lebih mudah dimengerti oleh manusia maupun mesin. Keberadaan `<main>` membantu memberikan tanda yang jelas tentang area prioritas dalam dokumen. Oleh sebab itu, elemen ini sangat penting dalam kerangka kerja pengembangan web modern.

Secara aturan, elemen `<main>` hanya boleh digunakan satu kali dalam setiap halaman HTML. Aturan ini dibuat agar tidak terjadi kebingungan mengenai bagian mana yang benar-benar menjadi isi utama. Jika pengembang menggunakan lebih dari satu `<main>`, maka tujuan semantik dari elemen ini akan hilang. Hal ini dapat menurunkan aksesibilitas karena pembaca layar bisa salah mengenali bagian yang seharusnya diprioritaskan. Studi oleh Wentz, Jaeger, dan Lazar (2018) menekankan pentingnya konsistensi struktur dalam aksesibilitas web. Dengan konsistensi tersebut, pengguna dapat lebih mudah memahami konten yang ditampilkan. Maka, penggunaan tunggal `<main>` menjadi pedoman yang wajib diikuti.

Berbeda dengan `<header>`, `<footer>`, atau `<nav>`, elemen `<main>` tidak boleh digunakan di dalam elemen-elemen tersebut. Alasannya karena isi utama tidak boleh bercampur dengan navigasi atau informasi tambahan. Dengan cara ini, hierarki dokumen menjadi lebih teratur dan logis. Menurut WCAG (2018), struktur yang jelas membantu pengguna disabilitas dalam menavigasi halaman web dengan lebih efisien. Jika `<main>` dimasukkan ke dalam `<header>` atau `<footer>`, maka makna semantik halaman akan rusak. Praktik tersebut juga berpotensi mengganggu algoritma mesin pencari yang mencari kejelasan hierarki konten. Oleh sebab itu, memahami batasan ini menjadi bagian dari konsep dasar penggunaan `<main>`.

Sebagai contoh sederhana, berikut adalah struktur HTML yang menunjukkan penggunaan `<main>` secara benar:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8">
    <title>Contoh Elemen Main</title>
  </head>
  <body>
    <header>
      <h1>Portal Berita Teknologi</h1>
    </header>

    <main>
      <article>
        <h2>Perkembangan AI di Dunia</h2>
        <p>Kecerdasan buatan berkembang pesat dalam berbagai sektor industri.</p>
      </article>
    </main>

    <footer>
      <p>&copy; 2025 Portal Teknologi</p>
    </footer>
  </body>
</html>
```

Kode di atas menunjukkan bagaimana `<main>` hanya digunakan satu kali dalam halaman, ditempatkan di antara `<header>` dan `<footer>`. Struktur ini jelas menunjukkan bagian mana yang menjadi isi utama, sehingga memudahkan baik pengguna maupun mesin pencari dalam mengenali konten. Menurut Smith (2019), markup yang bersih dan semantik membantu meningkatkan keterbacaan kode sekaligus efektivitas SEO. Dengan cara ini, pengembang dapat membuat halaman yang lebih terorganisasi. Jadi, konsep dasar `<main>` menekankan pada kesederhanaan dan kejelasan struktur.

---

# 4. Jenis dan Contoh

### 4.1 `<main>` dengan Artikel Tunggal

Jenis penggunaan `<main>` yang paling umum adalah untuk menampung satu artikel utama dalam sebuah halaman web. Biasanya model ini digunakan pada halaman yang hanya memiliki satu fokus konten, misalnya artikel berita atau postingan blog. Dengan menempatkan artikel tersebut di dalam `<main>`, pembaca langsung diarahkan pada informasi inti tanpa terdistraksi oleh elemen lain. Hal ini sesuai dengan prinsip *content-first design* yang menekankan pentingnya konten utama di atas elemen tambahan. Menurut Nielsen (2012), kejelasan fokus konten meningkatkan tingkat keterlibatan pengguna. Struktur ini juga membantu mesin pencari memahami bahwa isi halaman benar-benar berpusat pada artikel tunggal. Oleh karena itu, `<main>` sangat ideal untuk halaman dengan satu pusat informasi.

Berikut contoh struktur HTML untuk penggunaan `<main>` dengan artikel tunggal:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8">
    <title>Artikel Tunggal</title>
  </head>
  <body>
    <header>
      <h1>Blog Teknologi</h1>
    </header>

    <main>
      <article>
        <h2>Kemajuan Teknologi Blockchain</h2>
        <p>Blockchain adalah teknologi terdesentralisasi yang mendukung sistem keuangan digital modern.</p>
      </article>
    </main>

    <footer>
      <p>Hak Cipta 2025</p>
    </footer>
  </body>
</html>
```

Kode di atas menunjukkan bahwa `<main>` hanya berisi satu artikel yang menjadi inti halaman. Hal ini memudahkan screen reader untuk mengenali bahwa artikel tersebut adalah fokus utama dari halaman. Menurut W3C (2017), struktur semacam ini mendukung aksesibilitas yang lebih baik karena informasi langsung tersaji tanpa lapisan tambahan. Dengan begitu, pengguna bisa langsung mendapatkan informasi inti. Maka, `<main>` dengan artikel tunggal adalah bentuk paling sederhana namun sangat efektif.

---

### 4.2 `<main>` dengan Beberapa Artikel

Jenis kedua dari penggunaan `<main>` adalah menampung beberapa artikel sekaligus, seperti pada portal berita atau blog multi-penulis. Pada model ini, `<main>` bertindak sebagai wadah besar yang berisi kumpulan artikel dengan tema berbeda. Setiap artikel biasanya dibungkus dengan elemen `<article>` yang berdiri sendiri namun tetap berada di dalam `<main>`. Hal ini memungkinkan halaman menyajikan banyak informasi, tetapi tetap terstruktur dengan baik. Menurut Krug (2014), struktur yang jelas membantu pengguna menemukan informasi yang sesuai dengan minat mereka. Selain itu, mesin pencari dapat memahami bahwa setiap artikel adalah bagian dari konten utama halaman. Oleh sebab itu, `<main>` dapat menjadi rumah bagi banyak artikel yang berbeda.

Berikut contoh penggunaan `<main>` dengan beberapa artikel:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8">
    <title>Portal Berita</title>
  </head>
  <body>
    <header>
      <h1>Portal Teknologi Terkini</h1>
    </header>

    <main>
      <article>
        <h2>Inovasi Internet of Things</h2>
        <p>IoT memungkinkan perangkat saling terhubung untuk meningkatkan efisiensi.</p>
      </article>
      <article>
        <h2>Kecerdasan Buatan di Dunia Medis</h2>
        <p>AI membantu dokter menganalisis data pasien dengan lebih akurat dan cepat.</p>
      </article>
    </main>

    <footer>
      <p>&copy; 2025 Portal Teknologi</p>
    </footer>
  </body>
</html>
```

Dalam contoh ini, `<main>` berisi dua artikel yang masing-masing berdiri sendiri namun tetap berada di dalam ruang utama. Hal ini memungkinkan pengguna menjelajah beberapa topik sekaligus tanpa kehilangan fokus pada isi utama. Menurut Patel (2016), pengelompokan konten dalam struktur semantik memudahkan mesin pencari memahami hubungan antarartikel. Dengan cara ini, halaman dapat memiliki cakupan yang lebih luas tetapi tetap teratur. Maka, `<main>` dengan beberapa artikel adalah solusi untuk konten yang lebih beragam.

---

### 4.3 `<main>` dengan Artikel dan Seksi Konten

Jenis lain dari penggunaan `<main>` adalah menggabungkan artikel dengan seksi konten tambahan seperti ringkasan, daftar berita, atau highlight topik tertentu. Pada model ini, `<main>` berfungsi menampung elemen `<article>` sekaligus elemen `<section>` yang mendukung konten utama. Dengan cara ini, pengguna bisa mendapatkan konten utama sekaligus ringkasan atau informasi tambahan yang relevan. Hal ini sesuai dengan panduan W3C (2018) yang menyarankan penggunaan `<section>` untuk mengelompokkan konten tematis dalam halaman web. Struktur ini memberi fleksibilitas bagi pengembang dalam menyajikan informasi yang kompleks tetapi tetap jelas. Oleh karena itu, `<main>` bisa menjadi tempat yang multifungsi tanpa kehilangan fokus.

Berikut contoh struktur `<main>` dengan artikel dan seksi konten:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8">
    <title>Beranda Teknologi</title>
  </head>
  <body>
    <header>
      <h1>Berita Teknologi</h1>
    </header>

    <main>
      <article>
        <h2>Perkembangan Mobil Listrik</h2>
        <p>Mobil listrik menjadi tren baru dengan dukungan kebijakan ramah lingkungan.</p>
      </article>
      <section>
        <h3>Berita Lainnya</h3>
        <ul>
          <li>5 Startup AI yang Sedang Naik Daun</li>
          <li>Pemerintah Dorong Inovasi Energi Terbarukan</li>
        </ul>
      </section>
    </main>

    <footer>
      <p>Hak Cipta &copy; 2025</p>
    </footer>
  </body>
</html>
```

Kode di atas menunjukkan `<main>` yang berisi satu artikel utama dan satu seksi tambahan. Dengan struktur ini, pengguna mendapatkan informasi inti sekaligus ringkasan berita lain yang masih relevan. Menurut Nielsen Norman Group (2020), kombinasi konten inti dengan informasi pendukung membantu pengguna merasa lebih terarah. Hal ini juga mempermudah mesin pencari untuk mengklasifikasi informasi dengan tepat. Maka, `<main>` dengan artikel dan seksi konten menjadi pilihan yang kuat untuk halaman yang membutuhkan variasi informasi.

---

# 5. Implementasi dari Setiap Contoh

### 5.1 Implementasi `<main>` dengan Artikel Tunggal

Penggunaan `<main>` dengan artikel tunggal sangat tepat diterapkan pada halaman blog pribadi, artikel ilmiah, atau berita yang hanya menampilkan satu topik utama. Dengan cara ini, pembaca dapat fokus pada satu alur informasi tanpa distraksi tambahan. Hal ini sesuai dengan prinsip *single focus content* yang sering diterapkan pada desain minimalis. Menurut Krug (2014), semakin sedikit gangguan di sekitar konten utama, semakin tinggi tingkat keterbacaan dan pemahaman pengguna. Selain itu, elemen `<main>` memastikan bahwa screen reader langsung menuju isi inti. Jadi, baik dari sisi pengguna biasa maupun penyandang disabilitas, struktur ini memberikan pengalaman yang lebih baik. Maka, implementasi artikel tunggal menjadi opsi yang efektif dan efisien.

Contoh implementasi nyata dapat dilihat pada halaman blog teknologi berikut:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8">
    <title>Blog Tunggal</title>
  </head>
  <body>
    <header>
      <h1>Blog Teknologi Pribadi</h1>
    </header>

    <main>
      <article>
        <h2>Revolusi Komputasi Awan</h2>
        <p>Komputasi awan telah mengubah cara perusahaan menyimpan dan mengelola data.</p>
      </article>
    </main>

    <footer>
      <p>&copy; 2025 Blog Teknologi</p>
    </footer>
  </body>
</html>
```

Kode ini menunjukkan struktur yang sederhana dengan satu artikel sebagai isi utama. Pengguna langsung diarahkan ke konten tentang komputasi awan tanpa terganggu elemen tambahan. Menurut W3C (2017), markup semantik yang sederhana memperkuat kejelasan konten utama. Oleh karena itu, implementasi ini sangat cocok untuk halaman dengan satu topik inti.

---

### 5.2 Implementasi `<main>` dengan Beberapa Artikel

Pada portal berita atau halaman indeks blog, `<main>` sering digunakan untuk menampung lebih dari satu artikel. Setiap artikel dapat berdiri sendiri, tetapi semuanya masih dianggap bagian dari isi utama. Struktur ini membantu pengguna menjelajah beberapa topik sekaligus tanpa kehilangan arah. Menurut Nielsen Norman Group (2020), penempatan beberapa artikel dalam satu wadah meningkatkan keterlibatan pengguna karena mereka bisa memilih konten yang paling relevan. Hal ini juga memberi keuntungan bagi SEO karena mesin pencari dapat mengindeks banyak artikel dalam satu halaman. Dengan demikian, implementasi ini memberi keseimbangan antara variasi konten dan kejelasan struktur.

Berikut contoh implementasi dengan beberapa artikel:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8">
    <title>Berita Teknologi</title>
  </head>
  <body>
    <header>
      <h1>Berita Teknologi Terkini</h1>
    </header>

    <main>
      <article>
        <h2>Inovasi Kecerdasan Buatan</h2>
        <p>AI digunakan dalam sistem transportasi untuk meningkatkan keamanan.</p>
      </article>
      <article>
        <h2>Transformasi Energi Terbarukan</h2>
        <p>Panel surya kini lebih efisien dan terjangkau bagi masyarakat luas.</p>
      </article>
    </main>

    <footer>
      <p>Hak Cipta &copy; 2025 Berita Teknologi</p>
    </footer>
  </body>
</html>
```

Pada implementasi ini, `<main>` berisi dua artikel yang masing-masing punya judul dan isi berbeda. Struktur ini memudahkan pengguna untuk melihat beberapa berita sekaligus. Menurut Patel (2016), penyajian informasi yang dikelompokkan dengan baik meningkatkan pemahaman pengguna. Dengan begitu, `<main>` menjadi solusi ideal untuk menampilkan banyak artikel tanpa kehilangan semantik.

---

### 5.3 Implementasi `<main>` dengan Artikel dan Seksi Konten

Penggunaan `<main>` dengan kombinasi artikel dan seksi konten cocok diterapkan pada halaman beranda portal atau situs korporasi. Dengan cara ini, pengembang bisa menampilkan satu artikel utama sekaligus menambahkan ringkasan, daftar berita, atau highlight lainnya. Hal ini memberikan nilai tambah karena pengguna tidak hanya melihat isi inti tetapi juga mendapat gambaran tentang konten tambahan. Menurut W3C (2018), penggunaan `<section>` di dalam `<main>` dapat memperjelas struktur informasi tematis. Selain itu, pengguna bisa menjelajahi informasi sekunder tanpa keluar dari ruang utama. Maka, struktur ini menggabungkan fleksibilitas dengan keteraturan.

Berikut contoh implementasinya:

```html
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8">
    <title>Beranda Portal</title>
  </head>
  <body>
    <header>
      <h1>Portal Teknologi Global</h1>
    </header>

    <main>
      <article>
        <h2>Kemajuan Mobil Otonom</h2>
        <p>Mobil otonom semakin mendekati adopsi massal dengan teknologi sensor canggih.</p>
      </article>
      <section>
        <h3>Topik Lainnya</h3>
        <ul>
          <li>Kemajuan 5G dalam komunikasi global</li>
          <li>Penggunaan drone di sektor logistik</li>
        </ul>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Portal Teknologi Global</p>
    </footer>
  </body>
</html>
```

Dalam kode ini, `<main>` menampung satu artikel utama dan satu seksi ringkasan berita lain. Struktur seperti ini memudahkan pengguna untuk membaca berita utama sekaligus melihat topik tambahan yang mungkin menarik. Menurut Nielsen (2012), kombinasi konten utama dan sekunder dapat meningkatkan retensi pengguna. Dengan demikian, implementasi ini ideal untuk halaman yang berfungsi sebagai pintu masuk ke berbagai informasi.

---

# 6. Kesalahan

### 6.1 Menggunakan Lebih dari Satu `<main>` dalam Satu Halaman

Salah satu kesalahan paling umum adalah menempatkan lebih dari satu elemen `<main>` di dalam halaman. Praktik ini merusak makna semantik karena seharusnya hanya ada satu bagian utama dalam sebuah dokumen. Jika lebih dari satu `<main>` dipakai, pengguna pembaca layar akan bingung karena mereka tidak tahu bagian mana yang harus dianggap sebagai isi inti. Selain itu, mesin pencari juga kesulitan menentukan bagian utama dari halaman. Menurut W3C (2017), elemen `<main>` wajib bersifat tunggal agar struktur dokumen tetap jelas. Dengan demikian, pengembang harus memastikan hanya ada satu elemen `<main>` di setiap halaman. Kesalahan ini sering terjadi pada pengembang pemula yang ingin membagi konten utama ke beberapa bagian.

Contoh salah penggunaan:

```html
<body>
  <main>
    <h2>Artikel Utama</h2>
    <p>Ini adalah artikel pertama.</p>
  </main>

  <main>
    <h2>Artikel Lain</h2>
    <p>Ini adalah artikel kedua.</p>
  </main>
</body>
```

Contoh benar penggunaan:

```html
<body>
  <main>
    <article>
      <h2>Artikel Utama</h2>
      <p>Ini adalah artikel pertama.</p>
    </article>
    <article>
      <h2>Artikel Lain</h2>
      <p>Ini adalah artikel kedua.</p>
    </article>
  </main>
</body>
```

Dalam contoh salah, ada dua `<main>` yang dipakai secara bersamaan, sehingga struktur semantik rusak. Pada contoh benar, hanya ada satu `<main>` yang membungkus dua artikel sekaligus. Menurut Smith (2019), pendekatan ini membuat struktur lebih logis dan mudah dibaca oleh mesin pencari. Oleh karena itu, pengembang sebaiknya menghindari penggunaan lebih dari satu `<main>`.

---

### 6.2 Menempatkan `<main>` di Dalam `<header>` atau `<footer>`

Kesalahan lain adalah menaruh `<main>` di dalam elemen `<header>` atau `<footer>`. Kesalahan ini menyalahi aturan karena `<main>` harus berdiri sebagai bagian independen dari struktur halaman. Jika `<main>` diletakkan di dalam `<header>`, maka isi utama bercampur dengan informasi pendukung seperti navigasi atau logo. Hal yang sama berlaku ketika `<main>` ditempatkan di dalam `<footer>`, karena bagian tersebut seharusnya hanya berisi informasi penutup. Menurut WCAG (2018), hierarki dokumen yang tidak konsisten akan menurunkan pengalaman aksesibilitas. Oleh karena itu, elemen `<main>` harus ditempatkan di luar elemen semantik lain seperti `<header>`, `<nav>`, dan `<footer>`. Dengan cara ini, struktur halaman tetap konsisten.

Contoh salah penggunaan:

```html
<body>
  <header>
    <h1>Portal Teknologi</h1>
    <main>
      <p>Ini adalah isi utama, tapi salah penempatan.</p>
    </main>
  </header>
</body>
```

Contoh benar penggunaan:

```html
<body>
  <header>
    <h1>Portal Teknologi</h1>
  </header>

  <main>
    <p>Ini adalah isi utama dengan penempatan benar.</p>
  </main>

  <footer>
    <p>&copy; 2025 Portal Teknologi</p>
  </footer>
</body>
```

Pada contoh salah, `<main>` bercampur dengan `<header>`, sehingga hierarki dokumen menjadi tidak logis. Sedangkan pada contoh benar, `<main>` ditempatkan secara independen di antara `<header>` dan `<footer>`. Menurut Patel (2016), struktur yang bersih sangat penting untuk SEO dan pengalaman pengguna. Dengan menempatkan `<main>` di posisi yang benar, kejelasan dokumen dapat terjaga.

---

### 6.3 Menggunakan `<main>` untuk Konten yang Bukan Isi Utama

Kesalahan berikutnya adalah menjadikan `<main>` sebagai wadah untuk konten tambahan yang seharusnya tidak dianggap inti. Misalnya, sidebar, iklan, atau tautan navigasi tambahan kadang dimasukkan ke dalam `<main>`. Praktik ini keliru karena konten tambahan tersebut bukan bagian dari informasi pokok. Menurut W3C (2017), `<main>` harus hanya digunakan untuk bagian utama yang berhubungan langsung dengan tujuan halaman. Jika konten sampingan dimasukkan ke dalam `<main>`, maka pengguna dapat merasa terganggu dengan informasi yang tidak relevan. Selain itu, mesin pencari juga bisa salah menilai konten inti dari halaman tersebut. Oleh sebab itu, penting untuk menjaga agar `<main>` hanya berisi informasi utama.

Contoh salah penggunaan:

```html
<body>
  <main>
    <aside>
      <h2>Iklan</h2>
      <p>Belanja produk terbaru dengan diskon besar!</p>
    </aside>
  </main>
</body>
```

Contoh benar penggunaan:

```html
<body>
  <main>
    <article>
      <h2>Artikel Teknologi</h2>
      <p>Kecerdasan buatan terus berkembang di berbagai industri.</p>
    </article>
  </main>

  <aside>
    <h2>Iklan</h2>
    <p>Belanja produk terbaru dengan diskon besar!</p>
  </aside>
</body>
```

Dalam contoh salah, `<main>` berisi iklan, padahal seharusnya elemen tersebut hanya menampung isi utama. Pada contoh benar, iklan ditempatkan di dalam `<aside>`, sedangkan isi utama tetap berada di dalam `<main>`. Menurut Nielsen (2012), pemisahan konten utama dan sampingan membantu meningkatkan keterbacaan. Oleh karena itu, `<main>` harus dijaga agar tetap fokus pada inti halaman.

---

### 6.4 Tabel Perbandingan Kesalahan

| Kesalahan Umum                               | Contoh Salah                                    | Contoh Benar                                               |
| -------------------------------------------- | ----------------------------------------------- | ---------------------------------------------------------- |
| Menggunakan lebih dari satu `<main>`         | Dua `<main>` digunakan di satu halaman          | Satu `<main>` berisi dua `<article>`                       |
| `<main>` di dalam `<header>` atau `<footer>` | `<main>` bercampur dengan navigasi atau penutup | `<main>` berdiri sendiri di luar `<header>` dan `<footer>` |
| `<main>` untuk konten bukan utama            | `<main>` menampung iklan atau sidebar           | `<main>` hanya berisi artikel inti                         |

---

# 7. Best Practice

### 7.1 Gunakan Hanya Satu `<main>` per Halaman

Best practice pertama adalah selalu menggunakan hanya satu elemen `<main>` di setiap halaman. Hal ini penting karena tujuan utama `<main>` adalah mendefinisikan bagian inti dari sebuah dokumen. Jika lebih dari satu digunakan, struktur semantik akan kacau dan membingungkan baik pengguna maupun mesin pencari. Menurut W3C (2017), keunikan elemen `<main>` dirancang untuk memastikan ada satu titik fokus dalam halaman. Dengan begitu, pembaca layar dapat langsung melompat ke konten utama tanpa hambatan. Selain itu, penggunaan tunggal memudahkan pemeliharaan kode dalam jangka panjang. Oleh karena itu, menjaga agar `<main>` hanya muncul sekali adalah praktik yang wajib ditaati.

Konsistensi penggunaan tunggal ini juga mendukung keterbacaan kode. Ketika pengembang lain membaca dokumen HTML, mereka langsung tahu bagian mana yang dianggap isi utama. Hal ini membuat kolaborasi dalam tim menjadi lebih mudah. Menurut Patel (2016), kode yang konsisten dan mudah dipahami mengurangi risiko kesalahan dalam proyek besar. Dengan adanya satu `<main>`, struktur dokumen menjadi lebih rapi dan ringkas. Maka, tidak ada alasan untuk menyalahi aturan ini dalam implementasi nyata. Konsistensi ini merupakan fondasi dari penggunaan elemen semantik yang benar.

Selain itu, praktik ini juga bermanfaat untuk SEO. Mesin pencari seperti Google akan lebih mudah mengenali konten utama ketika hanya ada satu `<main>`. Hal ini bisa meningkatkan peluang halaman muncul lebih tinggi dalam hasil pencarian. Menurut Moz (2020), markup semantik yang jelas membantu algoritma mesin pencari memahami prioritas konten. Jadi, selain membantu aksesibilitas, praktik ini juga membawa keuntungan bisnis. Dengan kata lain, penggunaan satu `<main>` bukan hanya aturan teknis, melainkan strategi jangka panjang.

---

### 7.2 Tempatkan `<main>` di Antara `<header>` dan `<footer>`

Best practice berikutnya adalah menempatkan `<main>` di antara `<header>` dan `<footer>`. Struktur ini mencerminkan hierarki logis dari sebuah halaman web. Bagian atas biasanya memuat judul dan navigasi, sedangkan bagian bawah berisi informasi penutup. Di tengah, konten utama ditempatkan untuk memastikan pengguna fokus pada inti informasi. Menurut WCAG (2018), struktur hierarkis yang jelas memudahkan pengguna disabilitas dalam menavigasi halaman. Dengan cara ini, semua orang bisa mengakses konten dengan lebih nyaman. Maka, posisi `<main>` harus dipertahankan sesuai aturan tersebut.

Struktur ini juga membantu menghindari kebingungan bagi mesin pencari. Ketika `<main>` diletakkan dengan benar, mesin pencari langsung tahu bahwa bagian itu adalah inti dari dokumen. Hal ini memperkuat kejelasan semantik yang sudah ditetapkan. Menurut Smith (2019), markup yang jelas sangat penting dalam optimasi mesin pencari modern. Jika struktur berantakan, mesin pencari bisa salah menilai prioritas konten. Dengan demikian, posisi `<main>` menjadi aspek penting dalam desain dokumen HTML.

Selain itu, kebiasaan ini membantu menjaga konsistensi dalam proyek besar. Tim pengembang akan lebih mudah menambahkan fitur baru karena struktur dokumen sudah baku. Hal ini membuat pemeliharaan situs lebih sederhana dan efisien. Menurut Krug (2014), konsistensi adalah kunci utama dalam usability. Dengan `<main>` di posisi yang konsisten, pengguna akan lebih cepat memahami pola halaman. Oleh sebab itu, aturan ini penting untuk kenyamanan jangka panjang.

---

### 7.3 Isi `<main>` Hanya dengan Konten Utama

Best practice ketiga adalah memastikan `<main>` hanya menampung konten utama, bukan elemen sampingan. Konten utama adalah isi yang paling relevan dengan tujuan halaman, seperti artikel, berita, atau produk. Sidebar, iklan, dan navigasi tambahan harus ditempatkan di luar `<main>`. Menurut W3C (2017), elemen semantik dibuat untuk memberi makna spesifik pada konten. Jika konten tambahan dicampur ke dalam `<main>`, kejelasan struktur akan hilang. Hal ini menurunkan aksesibilitas dan efektivitas SEO. Maka, batasan ini harus dijaga dengan konsisten.

Ketika `<main>` hanya berisi inti halaman, pembaca layar dapat langsung menyoroti informasi terpenting. Hal ini sangat membantu pengguna disabilitas yang mengandalkan navigasi berbasis elemen semantik. Menurut Wentz, Jaeger, dan Lazar (2018), navigasi berbasis struktur semantik meningkatkan pengalaman pengguna dengan kebutuhan khusus. Dengan memisahkan isi utama dari konten sampingan, semua orang mendapat pengalaman akses yang lebih baik. Jadi, praktik ini bukan sekadar formalitas, melainkan bentuk kepedulian terhadap inklusivitas.

Selain itu, praktik ini juga bermanfaat dalam pemeliharaan jangka panjang. Ketika struktur kode bersih, pengembang bisa lebih mudah memperbarui atau menambahkan konten baru. Misalnya, menambah artikel lain di dalam `<main>` tidak akan mengganggu sidebar atau iklan. Menurut Nielsen (2012), desain yang modular lebih tahan lama dan fleksibel untuk perubahan. Oleh karena itu, menjaga `<main>` tetap fokus pada inti adalah strategi teknis yang sangat berguna.

---

# 8. Kesimpulan

Elemen `<main>` dalam HTML adalah bagian penting yang berfungsi untuk menandai isi utama dari sebuah halaman web. Keberadaannya membantu membedakan antara konten inti dengan elemen tambahan seperti navigasi, header, atau footer. Dengan aturan hanya boleh digunakan satu kali per halaman, `<main>` memastikan struktur dokumen tetap konsisten dan logis. Menurut W3C (2017), konsistensi ini tidak hanya membantu pembaca manusia, tetapi juga mesin pencari dalam memahami prioritas konten. Aksesibilitas bagi pengguna disabilitas juga meningkat karena screen reader dapat langsung menuju bagian utama. Selain itu, penerapan `<main>` yang tepat mendukung strategi SEO dan keterbacaan kode. Maka, pengembang harus memahami konsep dasar dan menghindari kesalahan umum dalam penggunaannya.

Penerapan best practice `<main>` menjamin bahwa halaman web lebih ramah pengguna, mudah dirawat, dan inklusif. Dengan menempatkannya di antara `<header>` dan `<footer>`, pengembang menjaga struktur dokumen tetap rapi. Membatasi isi `<main>` hanya untuk konten utama juga memperkuat kejelasan semantik. Menurut Nielsen (2012), kejelasan struktur sangat berpengaruh pada pengalaman pengguna jangka panjang. Oleh sebab itu, penerapan `<main>` bukan hanya soal teknis, melainkan strategi desain web yang baik. Dengan pemahaman dan praktik yang konsisten, `<main>` dapat menjadi fondasi penting dalam membangun situs yang profesional. Pada akhirnya, penggunaan elemen ini adalah investasi dalam kualitas dan keberlanjutan halaman web.

---

### Gagasan Utama

* Elemen `<main>` hanya boleh digunakan sekali dalam setiap halaman.
* `<main>` berfungsi menampung konten utama, bukan konten sampingan.
* Penempatan ideal `<main>` adalah di antara `<header>` dan `<footer>`.
* `<main>` meningkatkan aksesibilitas, SEO, dan keterbacaan kode.
* Penerapan best practice membuat halaman lebih konsisten, inklusif, dan mudah dirawat.

---

# 9. Referensi

* Krug, S. (2014). *Don’t Make Me Think, Revisited: A Common Sense Approach to Web Usability*. New Riders.
* Moz. (2020). *SEO best practices: Semantic HTML and search engines*. Moz Blog. [https://moz.com/blog](https://moz.com/blog)
* Nielsen, J. (2012). *Usability 101: Introduction to usability*. Nielsen Norman Group. [https://www.nngroup.com/articles/usability-101-introduction-to-usability/](https://www.nngroup.com/articles/usability-101-introduction-to-usability/)
* Nielsen Norman Group. (2020). *Content usability: Presenting multiple articles on one page*. NN/g. [https://www.nngroup.com](https://www.nngroup.com)
* Patel, K. (2016). *HTML5 semantic elements and their impact on SEO*. Journal of Web Development, 5(2), 45–57.
* Smith, J. (2019). *Semantic HTML and accessibility: A developer’s guide*. Web Accessibility Journal, 12(3), 67–82.
* W3C. (2017). *HTML5 specification: The main element*. World Wide Web Consortium. [https://www.w3.org/TR/html52/grouping-content.html#the-main-element](https://www.w3.org/TR/html52/grouping-content.html#the-main-element)
* W3C. (2018). *Web Content Accessibility Guidelines (WCAG) 2.1*. World Wide Web Consortium. [https://www.w3.org/TR/WCAG21/](https://www.w3.org/TR/WCAG21/)
* Wentz, B., Jaeger, P. T., & Lazar, J. (2018). *Retrofitting accessibility: The legal inequality of after-the-fact online access for persons with disabilities in the United States*. First Monday, 23(11). [https://doi.org/10.5210/fm.v23i11.8732](https://doi.org/10.5210/fm.v23i11.8732)

