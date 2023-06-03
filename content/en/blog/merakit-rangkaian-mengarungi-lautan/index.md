---
author: Ibrahim Fadhil
title: "Merakit Rangkaian, Mengarungi Lautan"
description: "Menjelajahi dunia elektroteknik dan perkapalan"
date: "2023-05-10"
tags: 
  - "indonesian"
thumbnail: "/blog/kuliah-online-adaptasi-atau-mati.jpg"
draft: true
---

# Menjawab Pertanyaan

<!-- Foto LOA keterima di Maritime Engineering Soton -->

*I know what you're (probably) thinking*. Kenapa seorang Ibrahim Fadhil Djauhari, yang kuliah S1 *Electrical Engineering* dan kerja di bidang *Software Engineering*, malah lanjut kuliah S2 di bidang *Maritime Engineering?*?

Jika kalian ingin jawaban yang singkat, jawabannya adalah karena aku ingin mendalami bidang *underwater robotics*.

Jika kalian masih membaca kalimat ini setelah sudah membaca jawaban singkat diatas, berarti kalian masih penasaran. Kalian ingin tau bagaimana kisah seorang Ibra bisa memutuskan untuk kuliah S2 di bidang yang cukup jauh dari latar belakangnya.

*Well you're in luck*, karena tujuanku menulis tulisan ini adalah:
- Menceritakan bagaimana aku memilih untuk S2 di bidang *Maritime Engineering*
- Menjelaskan konsep dan metode yang membantuku dalam menentukan pilihan ini

Sebagai penerima beasiswa [LPDP](https://lpdp.kemenkeu.go.id/en/), aku pun merasa penjelasan tentang tujuan pendidikanku adalah salah satu bentuk pertanggungjawaban dari uang negara yang akan membiayai kuliah S2 ku.

Terlepas dari itu, aku harap tulisanku ini bisa memberikan wawasan dan inspirasi untuk teman-teman yang sedang memikirkan tujuan pendidikan kuliahnya, memikirkan untuk melakukan pergantian karir dari satu bidang ke bidang lain yang berjauhan, dan/atau penasaran dengan bidang yang akan kutekuni.

# Menemukan Panggilan
## ITB *Hybrid Underwater Glider*

Aku pertama kali mengenal dunia *underwater robotics* saat tingkat akhir kuliahku di Teknik Elektro ITB. Untuk lulus dari jurusanku, aku wajib mengerjakan Tugas Akhir (TA) berupa sebuah *Capstone Design Project* bersama kelompok yang berisi 2-3 orang. Dalam TA ini, kami wajib membuat suatu alat untuk menyelesaikan suatu masalah. Setiap kelompok dapat memilih topik untuk TA-nya dari *list* topik yang diajukan oleh para calon dosen pembimbing.

<!-- Gambar Model 3D ITB-HUG -->

Diantara puluhan topik TA yang tersedia, topik yang paling menarik perhatianku adalah topik tentang ITB *Hybrid Underwater Glider* (ITB-HUG). HUG adalah suatu jenis *Autonomous Underwater Vehicle* (AUV), yaitu wahana yang dapat bergerak dalam air tanpa awak untuk melakukan pemetaan bawah laut. Riset AUV, termasuk riset ITB-HUG, sendiri telah dimulai di ITB sejak sekitar tahun 2017. Riset ini dikerjakan oleh gabungan tim mahasiswa S1, S2, dan S3 dengan bimbingan dari Prof. Bambang Riyanto Trilaksono.

Dari membaca deskripsi topik ini saja, aku tau proyek ini sangatlah sulit. Membuat robot biasa saja sudah kompleks, bagaimana dengan robot yang bisa bergerak di bawah air?

Tapi... Kapan lagi bisa ngoprek kapal selam robot, kan?

Terlepas dari keunikan bidang *underwater robotics* ini, aku tertarik dengan topik ini karena aku melihat potensi manfaatnya untuk Indonesia. Sebagai negara kepulauan terbesar di dunia, wilayah lautan Indonesia sangatlah luas. Disinilah *Underwater robots* hadir untuk membantu Indonesia menjelajahi dan menjaga lautan kita yang luas.  

Berbekal dengan keyakinan penuh atas kemampuan kami, kami memilih topik ITB-HUG sebagai topik TA kami.  Saat kami pertama bergabung dengan tim riset ITB-HUG, seluruh komponen elektronik dan mekanik dari ITB-HUG sudah selesai dirangkai menjadi suatu wahana utuh. Lalu, apa yang sebenarnya perlu kami kerjakan sebagai TA kami?

Walaupun secara *hardware* sudah lengkap, wahana ITB-HUG belum memiliki sistem *software* untuk bergerak secara otonom. Tujuan TA kami adalah untuk membuat sistem yang dapat menggerakkan ITB-HUG secara otonom mengikuti urutan *waypoint* yang diberikan oleh pengguna.

Untuk bisa mencapai tujuan ini, terdapat tiga sistem yang perlu diimplementasikan di ITB-HUG: 
- Sistem *Navigation* yang berfungsi untuk mengetahu posisi, orientasi, dan akselerasi wahana berdasarkan pembacaan data-data sensor 
- Sistem *Guidance* yang berfungsi untuk memandu atau "menyetir" arah gerak wahana untuk menuju suatu *waypoint*
- Sistem *Control* yang berfungsi untuk menggerakkan wahana sesuai arah gerak yang ditentukan sistem *guidance*

Setelah hampir satu tahun mengerjakan TA ini, kami berhasil mendesain dan mengimplementasi sistem *Navigation*, *Guidance*, dan *Control* dalam *software* dan *hardware* dari wahana ITB-HUG. Namun karena kondisi pandemi COVID-19, implementasi kami terbatas dengan pengujian [*Hardware-in-the-loop Simulation* (HILS)](https://www.hil-simulation.com/images/stories/Documents/Introduction%20to%20Hardware-in-the-Loop%20Simulation.pdf). 

Sebelum aku lulus dari ITB, dosen pembimbing TA-ku menawarkan aku untuk tetap aktif membantu riset ITB-HUG. Karena ketertarikan aku terhadap bidang *underwater robotics* ini, aku memutuskan untuk terus menjadi asisten riset ITB-HUG sejak lulus sampai sekarang.

## Merintis Karir

Menjelang wisudaku dari ITB, berbagai ide tentang rencanaku pasca-kampus berkumpul di pikiranku. Dimulai dari bekerja di bidang robotika, *Internet of Things*, *software engineering*, telekomunikasi, konsultan, *finance* atau langsung lanjut kuliah S2.

Karena pada saat itu aku belum menemukan alasan kuat untuk kuliah S2, aku pun melamar pekerjaan dalam berbagai bidang yang telah kusebutkan. Kenapa tidak melamar ke satu bidang tertentu? Ya sebagian karena ingin mengeksplor berbagai bidang baru, sebagian karena ingin "tebar jalar" dan berharap akan segera dapat pekerjaan (Alasan tipikal *job-seeker fresh graduate*).

Walaupun pada akhirnya aku bekerja *full-time* menjadi seorang *software engineer*, aku tetap berkecimpung di dunia *underwater robotics* dengan melanjutkan riset ITB-HUG. Pada saat itu, ide untuk memfokuskan karirku spesifik ke bidang *underwater robotics* memang sempat melintas di pikiran. Namun, keyakinanku untuk menyelam di bidang *underwater robotics* baru memuncak karena suatu kejadian pada awal tahun 2021.

## Tragedi di Laut Bali
<!-- Berita Insiden KRI Nanggala 402 -->

Pada tanggal 24 April 2021, 838 meter di bawah perairan laut Bali, kapal selam KRI Nanggala 402 bertemu dengan tempat peristirahatan terakhirnya. Seluruh Indonesia berduka cita atas hilangnya sang kapal selam beserta 53 awaknya. Tanpa peralatan yang memadai untuk melakukan pencarian dalam kedalaman lebih dari 800 meter di bawah air, Indonesia harus bergantung dengan peralatan pinjaman dari para negara tetangga.

Salah satu aset kunci dalam pencarian KRI Nanggala 402 adalah kapal MV Swift Rescue milik Angkatan Laut Singapura. Kapal ini merupakan satu-satunya Submarine Rescue Vessel di Asian Tenggara yang dilengkapi oleh Remotely Operated Vehicle (ROV) untuk pencarian kapal selam. Dengan bantuan ROV tersebut, tim pencarian berhasil mendapatkan foto dan video pertama di lokasi tenggelamnya KRI Nanggala 402.

Dengan insiden ini, aku tersadar bahwa keterbatasan *underwater robots* di Indonesia sudah menjadi isu keamanan nasional. Dan aku, sebagai seseorang yang telah berkecimpung di bidang ini, tidak bisa tinggal diam.

Maka saat seluruh penjuru tanah air berduka, aku membulatkan tekadku untuk mendalami bidang *underwater robotics*.

# Meyakinkan Pilihan

Dalam proses meyakinkan diri bahwa tujuan hidupku adalah menjadi *underwater robotics engineer*, aku menggunakan konsep *Ikigai* sebagai salah satu metodeku untuk merefleksikan diri.

## *Ikigai*

<!-- Gambar Diagram Ikigai -->

Ikigai adalah konsep dari Jepang yang menjelaskan makna kehidupan. Ikigai dapat digunakan untuk menentukan **tujuan hidup**. Tujuan hidup dakam Ikigai merupakan irisan dari empat aspek:

- *What you love*
- *What you are good at*
- *What you can be paid for*
- *What the world needs*

Dengan mencari irisan dari empat aspek tersebut, kita dapat menemukan tujuan hidup yang kita sukai, kita kuasai, dapat menghasilkan uang, dan dapat membantu orang lain. Berikut adalah caraku dalam menemukan *Ikigai*-ku:

### *1. What you love*

Sejak kecil tertarik sama komputer dan teknologi. Pengen suatu saat bisa membuat invensi teknologi baru yang bermanfaat untuk banyak orang di dunia.

### *2. What you are good at*

Suka belajar matematika dan fisika.

### *3. What you can be paid for*

Kerjaan engineering itu dibayar paling mahal di dunia (Cari sumber).

### *4. What the world needs*

Indonesia dan dunia butuh banget eksplorasi bawah laut deh pokoknya.

<!-- Sampai detik ini, hanya ada satu perusahaan manufaktur *underwater robot* di Indonesia: Robo Marine Indonesia. Dari sisi riset, hanya ada 4 universitas yang melakukan riset di bidang *underwater robotics*. Diantara 4 tersebut, riset ITB-HUG di ITB merupakan riset yang paling maju diantara proyek lainnya.

Aku, yang telah mendapatkan kesempatan -->

Hasilnya, aku membuat diagram *Ikigai* sebagai berikut (Disederhanakan):

<!-- Gambar Ikigai Ibra -->

Proses refleksi dalam mencari *Ikigai* ini meyakinkanku bahwa menjadi *underwater robotics engineer* adalah tujuan hidup paling cocok untukku.


# Membangun Impian
## Mimpi
Sejak kecil, aku memiliki cita-cita untuk menjadi seorang pengusaha. Terinspirasi dari kisah Bill Gates & Steve Jobs yang kubaca saat kecil, aku percaya bahwa membuat suatu **inovasi teknologi baru** kemudian **menjualnya kepada orang yang membutuhkan** adalah jalanku untuk bisa meninggalkan dampak positif yang besar untuk dunia.

Aku melihat kewirausahaan sebagai metode paling *sustainable* untuk mengembangkan teknologi seperti *underwater robots*, karena pengembangan produk akan didorong oleh kapital yang didapatkan dari mereka yang membutuhkan teknologi tersebut.

Dengan kondisi industri *underwater robotics* yang masih sangat kecil di Indonesia, aku melihat ada potensi besar untuk pengembangan perusahaan-perusahaan baru di bidang ini.

Oleh karena itu, visiku adalah untuk membangun perusahaan desain dan manufaktur *underwater robots* di Indonesia. Dalam perusahaan ini aku akan berperan sebagai *Chief Technology Officer* (CTO) yang memimpin desain dan produksi dari produk robot kami.

Jika tidak memungkinkan untuk membangun perusahaan baru, aku tetap bertujuan untuk menjadi CTO dari perusahaan *underwater robotics* eksisting dan mengembangkannya lebih jauh. 

Aku sadar industri ini memiliki *barrier of entry* yang sangat tinggi. Akan diperlukan usaha dan waktu yang tidak sedikit untuk bisa merealisasikan mimpi tersebut. Oleh karena itu, langkah pertamaku adalah untuk menempuh pendidikan S2 untuk mendalami keahlianku di bidang *underwater robotics*. Setelah lulus, aku akan bekerja di industri ini sambil melanjutkan riset ITB-HUG. Harapanku adalah aku dapat mulai menginisiasi perusahaan baru ku dalam 10 tahun setelah aku lulus S2.

Untuk menentukan keahlian mana yang perlu kuperdalam dan spesifiknya jurusan apa yang perlu kuambil untuk pendidikan S2-ku, aku memanfaatkan konsep *M-Shaped Person*.


## *M-Shaped Person*
Konsep *T-shaped person* beserta turunannya seperti *M-shaped person* sering digunakan untuk mendeskripsikan tingkat keahlian seseorang. Garis horizontal dalam "T" menggambarkan bidang-bidang keahlian yang berbeda, sedangkan garis vertikal menggambarkan kedalaman pemahaman seseorang di salah satu bidang tersebut.

Seseorang disebut *T-shaped* saat ia memiliki keahlian dasar dalam banyak bidang, namun juga memiliki keahlian mendalam di salah satu bidang tersebut. Sebagai contoh, inilah gambaran keahlianku sebagai *T-shaped person* saat aku lulus kuliah S1 Teknik Elektro ITB:

<!-- Gambar T-shaped Ibra di Teknik Elektro -->

Saat aku baru lulus S1, aku memiliki dasar keahlian matematika dan fisika yang dimiliki mahasiswa teknik secara umum, ditambah keahlian mendalam di bidang teknik elektro yang kupelajari dari jurusanku.

Saat aku mulai berkarir sebagai *Software Engineer*, bidang keahlian yang kudalami bertambah. Keahlianku sekarang dapat digambarkan seperti berikut:

<!-- Gambar π-shaped Ibra -->

Seseorang dengan bentuk keahlian seperti diatas sering disebut sebagai *π-shaped person* (Karena bentuknya mirip simbol pi atau π).

Saat aku merencanakan jalan hidupku sebagai *underwater robotics engineer*, aku memikirkan keahlian apa yang diperlukan seseorang untuk bekerja dalam posisi ini. Bidang *Robotics* sendiri adalah bidang yang multidisiplin karena membutuhkan keahlian di bidang *Electrical Engineering* (Desain rangkaian listrik robot), *Software Engineering* (Pemrograman logika robot), dan *Mechanical Engineering* (Desain badan dan alat gerak robot). Untuk bidang *Underwater Robotics*, keahlian bidang *Mechanical Engineering* dapat digantikan dengan bidang *Maritime Engineering*. Keahlian ini dibutuhkan untuk desain badan dan alat gerak robot yang spesifik beroperasi dalam air.

Berdasarkan kebutuhan ini, aku memiliki 2 pilihan untuk tujuan pendidikan S2-ku:

1. Memperdalam keahlian Robotika di bidang-bidang yang sudah kupahami: *Electrical Engineering* atau *Software Engineering*. Pilihan ini dapat menjadikanku *expert* dalam bidang Robotika secara umum, namun tidak spesifik ke bidang *Underwater Robotics*.

2. Memperdalam keahlian *Underawter Robotics* dengan mempelajari bidang *Maritime Engineering*. Pilihan ini dapat menjadikanku *expert* yang spesifik untuk bidang *Underwater Robotics*, namun tidak dalam bidang Robotika secara umum.

Karena impianku adalah menjadi CTO yang membangun perusahaan desain dan manufaktur *underwater robotics* baru di Indonesia, aku memilih pilihan kedua. Seorang CTO harus memiliki wawasan menyeluruh tentang proses desain dan manufaktur sebuah *underwater robot*. Aku pun sudah 100% yakin untuk bahwa tujuanku adalah menjadi *underwater robotics engineer*. Daripada belajar robotika secara umum, aku lebih baik fokus di bidang yang lebih spesifik ini.

Oleh karena itu, aku berharap setelah aku lulus S2 dan bekerja di bidang *underwater robotics* aku akan memiliki keahlian seperti berikut:

<!-- Gambar M-Shaped Ibra -->

Seseorang dengan keahlian mendalam di tiga bidang inilah yang disebut sebagai *M-Shaped person*. Inilah gambaran keahlian diriku yang menjadi pedomanku untuk merealisasikan impianku.


# Merakit Rangkaian, Mengarungi Lautan

Di banyak kisah fiksi, terdapat sebuah *trope* umum bernama ***The Chosen One***. Seringkali, kisah fiksi menceritakan satu orang terpilih yang ditakdirkan untuk melakukan suatu tugas penting.

Baik itu **Harry Potter** yang ditakdirkan mengalahkan Voldemort karena ia selamat dari serangannya saat kecil; **Frodo Baggins** yang ditakdirkan mengalahkan Sauron karena menemukan *The One Ring* milik pamannya; maupun **Luke Skywalker** yang ditakdirkan mengalahkan *The Emperor* karena kesaktiannya sebagai anak rahasia Anakin Skywalker; semua karakter tersebut menjadi ***The Chosen One*** karena mereka berada di suatu tempat, waktu, dan kondisi yang tepat.

Tanpa terlihat seperti orang narsis, saat ini akulah yang merasa telah menjadi ***The Chosen One***. 

Aku memiliki *privilege* untuk melakukan riset di bidang yang sangat langka dan dibutuhkan oleh Indonesia. Aku dapat melanjutkan S2 di bidang yang sesusai dengan tujuanku. Dan aku berambisi untuk mengembangkan industri ini yang skalanya masih sangat kecil di Indonesia.

Untuk mengutip Princess Zelda dari *game* favoritku saat ini, *The Legend of Zelda: Tears of The Kingdom*:

<!-- Gambar Zelda bawa Master Sword sambil ngomong "I know why I am here. It is something only I can do." -->


Ibrahim Fadhil Djauhari
(Future) Underwater Robotics Engineer