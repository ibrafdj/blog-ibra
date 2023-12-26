---
author: Ibrahim Fadhil Djauhari
title: "Merakit Rangkaian, Mengarungi Lautan"
description: "Perjalanan menyelam ke dunia baru"
date: "2023-09-07"
keywords: ["kuliah", "s2","maritime robotics","underwater robotics","kuliah luar negeri","contoh ikigai","ikigai","motivasi"]
tags: 
  - "indonesian"
thumbnail: "/blog/merakit-rangkaian-mengarungi-lautan.jpg"
---

{{<img caption="<i>Umm, I can explain.</i>"
src="images/LOA.jpg" >}}

*I know what you're (probably) thinking*.

Kenapa seorang Ibrahim Fadhil Djauhari, yang kuliah S1 ***Electrical Engineering*** dan kerja di bidang ***Software Engineering***, malah lanjut kuliah S2 di bidang ***Maritime Engineering?***?

Jika kalian ingin jawaban yang singkat, jawabannya adalah karena aku ingin mendalami bidang ***underwater robotics***.

Kalau jawaban panjangnya? *Well, I'm glad you asked because that's precisely why I wrote this post.*

Selain untuk menjawab pertanyaan yang sering ditanyakan orang lain, harapanku tulisan ini bisa memberikan wawasan dan inspirasi untuk teman-teman yang sedang **merencanakan tujuan kuliahnya** (Terutama merencanakan kuliah S2/S3 namun jurusan S1-nya berbeda jauh), **merencanakan pergantian karir** antara dua bidang yang berbeda, dan/atau **penasaran dengan bidang *underwater robotics*** yang akan kutekuni ini.

Sebagai penerima beasiswa [LPDP](https://lpdp.kemenkeu.go.id/en/), aku pun merasa penjelasan tentang tujuan pendidikanku adalah salah satu bentuk pertanggungjawaban dari uang negara yang akan membiayai kuliah S2-ku.

Perjalananku "pindah jurusan" dan *"career switch"* ini dimulai dari kisah bagaimana proses aku **menemukan "panggilan" untuk mendalami bidang *underwater robotics***, kemudian proses refleksi diri yang kulakukan untuk **meyakinkan diri atas tujuan hidup yang telah kupilih**, dilanjut dengan proses aku **membangun impian yang ingin kucapai dan rencana merealisasikannya**, dan ditutup dengan **merefleksikan perjalananku sejauh ini**.

## Menemukan Panggilan

Panggilan untuk mendedikasikan diri ke suatu tujuan bisa datang kapan saja dan dari mana saja. Bagiku, perjalanan menemukan panggilan  hidupku sekarang dimulai saat aku pertama kali mengenal bidang *underwater robotics*.

### Underwater Robots

Eksplorasi bawah laut adalah kegiatan yang sangat sulit untuk dilakukan manusia. Semakin dalam kita menyelam ke bawah laut; semakin banyak oksigen yang perlu kita simpan, semakin sedikit pencahayaan dari permukaan, dan semakin kuat tekanan yang harus kita lawan.

Di banyak bidang lain, isu "Suatu saat robot akan menggantikan pekerjaan manusia!" adalah isu eksistensial yang sangat ditentang. Namun untuk menyelam ke bawah lautan, robot akan diagung-agungkan sebagai pahlawan.

*Underwater robots* dibagi menjadi dua jenis:

- *Remotely Operated Vehicle* (ROV)

  Robot yang dikendalikan secara langsung oleh seorang operator dengan menggunakan *remote control*. Umumnya, ROV dilengkapi dengan kabel yang sangat panjang untuk menerima serta mengirimkan data dari dan ke operator.

  ROV dapat melakukan pergerakan dengan presisi tinggi karena dikendalikan langsung oleh seorang operator. Namun jarak pengoperasiannya terbatas oleh panjang kabel yang dimiliki.

{{<img caption="ROV Hercules"
source="[NOAA Ocean Exploration](https://oceanexplorer.noaa.gov/technology/subs/rovs/rovs.html)"
src="https://oceanexplorer.noaa.gov/technology/subs/rovs/media/hercules2-hires.jpg" >}}

- *Autonomous Underwater Vehicle* (AUV)

  Robot yang dapat bergerak tanpa dikendalikan secara langsung oleh seorang operator. AUV menerima perintah seperti "Bergerak ke koordinat x,y,z" atau "Pertahankan posisi saat ini" kemudian menjalankannya secara otonom. Pergerakan otonom dilakukan AUV berdasarkan pembacaan kondisi diri dan sekitarnya dari sensor-sensor yang dimilikinya.

  AUV dapat menjalankan misi dalam jarak jauh dan jangka panjang. Namun presisi pergerakannya lebih rendah dan proses pembuatannya lebih rumit dibanding dengan ROV.

{{<img caption="REMUS-600 AUV"
source="[Ocean Observatories](https://oceanobservatories.org/marine-technologies/robotic-auvs/)"
src="https://oceanobservatories.org/wp-content/uploads/2015/07/AUV_deployment.jpg" >}}

*Underwater robotics* merupakan bidang yang sangat spesifik dan *niche*. Aku pun tidak akan bisa terekspos ke bidang ini tanpa pengalamanku pada tahun terakhir di Teknik Elektro ITB...

### ITB *Hybrid Underwater Glider*

Aku pertama kali mengenal dunia *underwater robotics* saat aku kuliah tingkat akhir di Teknik Elektro ITB. Untuk lulus dari jurusanku, aku wajib mengerjakan Tugas Akhir (TA) berupa sebuah *Capstone Design Project* bersama kelompok yang berisi 2-3 orang. Dalam TA ini, kami wajib membuat suatu alat untuk menyelesaikan suatu masalah. Setiap kelompok dapat memilih topik untuk TA-nya dari *list* topik yang diajukan oleh para calon dosen pembimbing.

Diantara puluhan topik TA yang tersedia, topik yang paling menarik perhatianku adalah topik tentang ITB *Hybrid Underwater Glider* (ITB-HUG). Riset tentang AUV ini telah dimulai di STEI ITB sejak sekitar tahun 2017. Dibawah bimbingan Prof. Bambang Riyanto Trilaksono, riset ini dijalankan oleh gabungan tim mahasiswa S1, S2, dan S3.

{{<img caption="<i>I'm not allowed to publicly show a photo of the ITB-HUG, so here's an (old) 3D model of it</i> :)"
src="images/ITB_HUG.jpg" >}}

Ketertarikanku ke ITB-HUG berakar dari besarnya potensi pemanfaatan AUV di Indonesia. Sebagai negara maritim dengan lautan yang sangat luas, aku percaya bahwa Indonesia perlu melakukan eksplorasi bawah laut dalam skala besar untuk memanfaatkan, mengamankan, dan melestarikan lautannya.

HUG merupakan AUV yang dapat bergerak dalam dua mode pergerakan: *propulsion* dan *glide*. Dalam mode *propulsion*, HUG bergerak menggunakan dorongan dari *thruster* (Baling-baling) yang kemudian disetir oleh *rudder* (Sirip). Dalam mode *glide*, HUG bergerak secara *gliding* dengan menenggelamkan dan mengapungkan diri berulang kali dalam suatu siklus.

{{<img caption="Contoh gerakan <i>glide</i> yang dapat dilakukan oleh AUV"
source="[SeaGlide](http://seaglide.org/about)"
src="https://images.squarespace-cdn.com/content/v1/52f69916e4b0393d858e6f9f/1391897542872-AHSFKSCSSGJ9WF7VMAZ4/GliderMecnaicsOverview.png?format=2500w" >}}

Dari membaca deskripsi topik ini saja, aku tau topik ini akan sangat sulit. Membuat robot saja sudah kompleks, apalagi robot yang bisa bergerak di bawah air?

Tapi... Kapan lagi bisa ngoprek kapal selam robot, kan?

Berbekal keyakinan penuh atas kemampuan kami, pengerjaan TA ITB-HUG kami dimulai. Saat kami pertama bergabung dengan tim riset ITB-HUG, seluruh komponen elektronik dan mekanik dari ITB-HUG sudah selesai dirangkai menjadi suatu wahana utuh. Lalu, apa yang sebenarnya perlu kami kerjakan sebagai TA kami?

Walaupun komponennya sudah lengkap, wahana ITB-HUG belum memiliki kemampuan untuk bergerak secara otonom (Tanpa kendali manusia). Target TA kami adalah untuk membuat sistem yang dapat menggerakkan ITB-HUG secara otonom mengikuti urutan *waypoint* yang diberikan oleh pengguna.

Untuk bisa mencapai tujuan ini, terdapat tiga sistem yang perlu diimplementasikan di ITB-HUG:

- Sistem *Navigation* yang berfungsi untuk mengetahu posisi, orientasi, dan akselerasi wahana berdasarkan pembacaan data-data sensor
- Sistem *Guidance* yang berfungsi untuk memandu atau "menyetir" arah gerak wahana untuk menuju suatu *waypoint*
- Sistem *Control* yang berfungsi untuk menggerakkan wahana sesuai arah gerak yang ditentukan sistem *guidance*

Setelah melalui proses yang sulit selama satu tahun mengerjakan TA ini, kami [berhasil](https://digilib.itb.ac.id/gdl/download/214151) mendesain dan mengimplementasi sistem *Navigation*, *Guidance*, dan *Control* dalam *software* dan *hardware* di wahana ITB-HUG. Walaupun karena kondisi pandemi COVID-19 implementasi kami terbatas dengan pengujian *Hardware-in-the-loop Simulation*, bukan pengujian langsung di laut.

Sebelum aku lulus dari ITB, dosen pembimbing ku menawarkan aku untuk melanjutkan riset ITB-HUG ini. Walaupun aku belum ada niat untuk mendalami bidang *underwater robotics*, aku sadar bahwa bidang ini sangat menarik dan melakukan riset di bidang ini adalah kesempatan yang sangat langka. Sejak saat itulah aku memutuskan untuk bekerja menjadi asisten riset dalam proyek ITB-HUG.

### Merintis Karir

Dalam hari-hari menjelang wisuda, berbagai ide tentang rencana karirku kedepannya telah berkumpul di dalam kepalaku. Diantaranya adalah rencana untuk bekerja di bidang robotika, *Internet of Things*, *software engineering*, telekomunikasi, konsultan; atau langsung melanjutkan kuliah S2.

Karena pada saat itu aku belum menemukan alasan kuat untuk kuliah S2, aku pun mencoba melamar pekerjaan dalam berbagai bidang dan posisi. Tujuanku adalah untuk bekerja sambil mengeksplor berbagai bidang baru sebelum menentukan jalur karir jangka panjangku. Selain  itu, tentu aku juga melakukannya karena ingin "tebar jala" agar tidak menjadi pengangguran (Alasan tipikal *job-seeker fresh graduate*).

{{<img caption="Hari terakhirku sebagai <i>software engineer</i> di <i>Samsung Research Indonesia</i> (SRIN)"
src="images/SRIN.jpg" >}}

Pada akhirnya, *demand* yang tinggi ditambah gaji yang besar dibanding profesi lain berhasil merayuku untuk bekerja *full-time* sebagai *software engineer*. Walaupun berkarir di bidang ini cukup nyaman dan sangat berpotensi untuk diperdalam, pada akhirnya aku belum merasa "terpanggil" disini. Aku tidak menemukan masalah spesifik yang ingin aku selesaikan atau keahlian tertentu yang ingin aku kuasai sebagai *software engineer*. **Pada saat itulah aku sadar bahwa karirku sebagai *software engineer* ini hanyalah pemberhentian sementara**. Berkarir di bidang ini adalah proses ekplorasiku untuk menemukan pekerjaan sebenernya yang ingin aku tekuni.

Selama bekerja menjadi *software engineer*, aku tetap berkecimpung di dunia *underwater robotics* sebagai *part-time research assistant* di riset ITB-HUG. Pada saat itu, ide untuk memfokuskan karirku spesifik ke bidang *underwater robotics* memang sempat melintas di pikiran. Namun, keyakinanku untuk menyelam di bidang *underwater robotics* baru memuncak karena suatu kejadian pada awal tahun 2021...

### Tragedi di Laut Bali

{{<img caption="KRI Nanggala 402"
source="[AP](https://apnews.com/article/indonesia-missing-submarine-kri-nanggala-402-0f713512d5e53131863a67c99016db64)"
src="https://dims.apnews.com/dims4/default/188aaba/2147483647/strip/true/crop/3000x1992+0+0/resize/1440x956!/format/webp/quality/90/?url=https%3A%2F%2Fstorage.googleapis.com%2Fafs-prod%2Fmedia%2F7609fe7410b84049ac3d03b1c597fc45%2F3000.jpeg" >}}

Pada tanggal 24 April 2021, 838 meter di bawah permukaan laut Bali, kapal selam KRI Nanggala 402 menemukan tempat peristirahatan terakhirnya. Seluruh Indonesia berduka cita atas hilangnya sang kapal selam beserta 53 awaknya. Tanpa peralatan yang memadai untuk melakukan pencarian dalam kedalaman lebih dari 800 meter di bawah air, Indonesia harus bergantung dengan peralatan pinjaman dari para negara tetangga.

Salah satu aset kunci dalam pencarian KRI Nanggala 402 adalah kapal [MV Swift Rescue](https://katadata.co.id/sortatobing/berita/6083c1b7f0536/mv-swift-rescue-kapal-milik-singapura-yang-ikut-mencari-kri-nanggala) milik Angkatan Laut Singapura. Kapal ini merupakan satu-satunya *Submarine Rescue Vessel* di Asia Tenggara yang dilengkapi oleh sebuah ROV untuk pencarian kapal selam. Dengan bantuan ROV tersebut, tim pencarian berhasil mendapatkan foto dan video pertama di lokasi tenggelamnya KRI Nanggala 402.

{{<img caption="Kronologi Penemuan KRI Nanggala 402"
source="[ANTARANEWS](https://www.antaranews.com/infografik/2123446/kronologi-penemuan-kri-nanggala-402)"
src="https://img.antaranews.com/cache/infografis/1140x2100/2021/04/26/20210426kronologi-nanggala-ditemukan.jpg?quality=85" >}}

Insiden ini menyadarkanku bahwa kurangnya keahlian *underwater robotics* di Indonesia sudah menjadi isu keamanan nasional; dan aku, sebagai seseorang yang telah berkecimpung di bidang ini, tidak bisa tinggal diam.

Saat seluruh penjuru tanah air berduka, aku membulatkan tekadku untuk mendalami bidang *underwater robotics*.

## Meyakinkan Pilihan

Saat aku mulai berpikir serius untuk menjadi *underwater robotics engineer*, hati dan pikiranku dipenuhi dengan ketidakyakinan. Bidang *underwater robotics* ini sangat spesifik dan peluang karirnya di Indonesia, bahkan di dunia, sangat sempit. Latar belakang pendidikan dan pekerjaan ku di bidang ini masih sedikit. Terlebih lagi aku harus meninggalkan karir *software engineer*-ku yang peluang kerjanya luas dan gajinya cukup tinggi.

Namun pada akhirnya aku yakin bahwa menjadi *underwater robotics engineer* merupakan puncak dari aktualisasi diriku dan jalanku untuk memberikan dampak besar untuk dunia. Keyakinan diri ini datang dari proses refleksi diri yang mendalam dengan mengimplementasikan konsep [Ikigai](https://positivepsychology.com/ikigai/).

### *Ikigai*

{{<img caption="Diagram <i>Ikigai</i>"
source="[TheMindFool](https://themindfool.com/ikigai/)"
src="https://themindfool.com/wp-content/uploads/2020/09/Ikigai_doagram-15-15-1024x1024.jpg" >}}

*Ikigai* adalah sebuah konsep dari Jepang yang dapat digunakan untuk menentukan **tujuan hidup**. Tujuan hidup dalam *Ikigai* merupakan irisan dari empat aspek:

1. *What you love*
2. *What you are good at*
3. *What you can be paid for*
4. *What the world needs*

Dengan mencari irisan dari empat aspek tersebut, kita dapat menemukan tujuan hidup yang kita sukai, kita kuasai, dapat menghasilkan uang, dan dapat membantu orang lain. Berikut adalah caraku dalam menemukan *Ikigai*-ku:

#### 1. *What you love*

Aku telah dikenalkan dengan **teknologi** seperti komputer dan *video game console* sejak kecil. Sebagai anak kecil, kemampuan untuk bermain beragam *video game* dengan teknologi ini sangat menarik perhatianku. Seiring aku tumbuh, rasa keingintahuanku tentang bagaimana cara teknologi bekerja, khususnya komputer, terus meningkat. Aku pun berandai-andai untuk suatu saat bisa membuat teknologi canggih seperti senjata laser dan mesin waktu. Keinginan inilah yang pada akhirnya akan membawaku kuliah di Teknik Elektro ITB.

Puncak aktualiasi diri bagi seorang pecinta teknologi adalah membuat teknologi baru. Di saat bersamaan, permasalahan di dunia tidak ada habisnya. Oleh karena itu, aku yakin bahwa tujuan hidupku adalah **membuat teknologi untuk menyelesaikan sebagian permasalahan dunia**.

#### 2. *What you are good at*

Karena ketertarikanku dengan teknologi dan keterpaparanku dengan film *science-fiction*, aku telah minat dengan ilmu **Fisika dan Matematika** sejak kecil. Minat ini membantuku mendapatkan nilai yang cukup baik dalam dua mata pelajaran ini selama sekolah dan mendorongku untuk mempelajari bidang *Engineering* saat kuliah.

Walaupun aku tidak menguasai pelajaran Fisika & Matematika, aku yakin dua keilmuan ini adalah bidang yang paling aku pahami diantara bidang keilmuan lainnya. Kedua bidang ini adalah pondasi dari segala ilmu *Engineering* yang telah dan akan aku pelajari, baik itu ilmu Teknik Elektro, Informatika, maupun Perkapalan.

#### 3. *What you can be paid for*

Secara umum, bidang STEM (*Science, Technology, Engineering, and Mathematics*) adalah salah satu bidang keilmuan dengan gaji paling tinggi di dunia[^1]. Maka dengan aku berkarir di bidang **Engineering**; baik itu sebagai *Electrical*, *Software*, atau *Maritime Engineer*; seharusnya aku tidak akan kesulitan secara finansial (*aminnn*).

#### 4. *What the world needs*

Pada tahun 2023, tercatat bahwa baru 24.9% dari dasar laut Bumi telah dipetakan dalam resolusi yang memadai[^2]. Padahal, pemetaan bawah laut atau batimetri memiliki berbagai aplikasi penting seperti pembuatan *nautical chart* untuk navigasi kapal, pengamatan pergeseran tektonik, dan pembangunan infrastruktur *offshore*.

Namun seperti yang telah kutuliskan sebelumnya, eksplorasi bawah laut sangat sulit untuk dilakukan manusia. Inilah mengapa diperlukan solusi untuk **melakukan pemetaan bawah laut secara aman dan efisien**. Disinilah *underwater robots* hadir sebagai salah satu solusinya.

Saat ini ahli dalam bidang ini di Indonesia masih terbatas. Hanya ada satu perusahaan yang bergerak di bidang *underwater robotics* di Indonesia: Robo Marine Indonesia. Sedangkan dari sisi akademik, hanya ada 4 universitas yang melakukan riset *underwater robotics* tentang AUV (Termasuk riset ITB-HUG).

Aku, sebagai orang yang ber-*privilege* mendapatkan kesempatan melakukan riset penting (ITB-HUG) dalam bidang yang sangat langka ini (*Underwater robotics*), mengemban tanggung jawab untuk terus mengembangkan bidang *underwater robotics* Indonesia.

#### Hasil

Dengan menjawab empat pertanyaan di atas, aku membuat diagram *Ikigai* sebagai berikut:

{{<img caption="Ilustrasi <i>Ikigai</i> Ibra"
src="images/Ikigai_Ibra.jpg" >}}

Proses refleksi dalam mencari *Ikigai* ini meyakinkanku bahwa menjadi *underwater robotics engineer* adalah tujuan hidup yang cocok untukku.

Perlu jadi catatan bahwa proses merancang tujuan hidup adalah proses yang akan **berjalan terus seumur hidup**. ***It's completely fine*** untuk merasa belum 100% yakin dengan tujuan hidup yang kita pilih saat ini. Tujuan kita bisa berubah seiring kita merasakan pengalaman baru, memasuki lingkungan baru, bertemu orang baru, atau menyadari hal-hal baru. 

Mengisi diagram *ikigai* di atas pun seperti itu. Dulu diagram *ikigai*-ku belum sedetil dan selengkap diagram di atas. Namun seiring berjalannya waktu, melalui segala kejadian yang kutulis di bagian [Menemukan Panggilan](#menemukan-panggilan), satu per satu lingkaran di diagram *ikigai*-ku semakin terisi. Sampai pada akhirnya aku yakin dengan tujuan hidup yang kupilih.

## Membangun Impian

Aku sudah yakin untuk menjadi seorang *underwater robotics engineer*, tapi sebenarnya mimpi apa sih yang ingin aku capai? Dan bagaimana caraku untuk merealisasikan impianku itu?

Untuk menjawab dua pertanyaan yang menghantuiku ini, aku menerawang kembali ke **cita-cita ku sejak kecil** kemudian menentukan **keilmuan apa yang perlu kupelajari** untuk merealisasikannya.

### Mimpi

{{<img caption="<i>What motivates me to keep pushing forward</i>"
source="[Pinterest](https://www.pinterest.com/pin/488359153320778468/)"
src="https://i.pinimg.com/originals/bf/41/cd/bf41cdcb78d70e939578774053efa147.jpg" >}}

Sejak kecil, aku sering membaca kisah tentang orang-orang sukses dunia. Dua orang diantara mereka meninggalkan kisah yang paling berkesan bagiku: Bill Gates & Steve Jobs. Kedua pengusaha muda yang "seangkatan" ini terkenal dengan kesuksesannya membangun Microsoft dan Apple, dua nama besar dari *Silicon Valley* yang masih disegani dunia sampai hari ini. Terlepas dari beragam kontroversi mereka, kemampuan mereka untuk membuat suatu **inovasi teknologi** kemudian mengembangkan inovasi tersebut menjadi **perusahaan penghasil teknologi** sebagai seorang *technopreneur* telah menginspirasiku untuk mengikuti jalan mereka.

Aku melihat kewirausahaan sebagai metode paling *sustainable* untuk mengembangkan teknologi seperti *underwater robots*. Karena masalah yang dapat diselesaikan teknologi ini sangatlah rumit dan pengembangannya membutuhkan dukungan kapital yang besar. Menjual suatu teknologi untuk mereka yang membutuhkannya (dengan harga yang sesuai) adalah metode yang dapat menjamin proses pengumpulan kapital sekaligus pengembangan teknologi tersebut.

Melihat kondisi industri *underwater robotics* yang masih sangat kecil di Indonesia, aku melihat ada potensi besar untuk pengembangan perusahaan-perusahaan baru di bidang ini. Oleh karena itu, visiku adalah untuk membangun perusahaan desain dan manufaktur *underwater robots* di Indonesia. Dalam perusahaan ini aku ingin berperan sebagai *Chief Technology Officer* (CTO), *Vice President of Engineering*, atau peran strategis lainnya dimana aku dapat memimpin proses desain dan manufaktur *underwater robots*.

Jika memang tidak memungkinkan untuk membangun perusahaan baru, aku tetap berambisi menjadi CTO / VP Engineering dari perusahaan *underwater robotics* eksisting agar dapat mengembangkannya lebih jauh.

Aku sadar industri ini memiliki *barrier of entry* yang sangat tinggi. Akan diperlukan usaha dan waktu yang tidak sedikit untuk bisa merealisasikan mimpi tersebut. Oleh karena itu, langkah pertamaku adalah untuk **menempuh pendidikan S2** untuk mendalami keahlianku di bidang *underwater robotics*. Setelah lulus, aku akan bekerja di industri ini sambil melanjutkan riset ITB-HUG. Harapanku adalah aku dapat mulai menginisiasi perusahaan baru ku dalam 10 tahun setelah aku lulus S2.

Karena bidang *underwater robotics* adalah keilmuan yang multidisiplin, aku perlu menentukan disiplin apa yang akan kuperdalam dari bidang ini. Spesifiknya, pilihan ini dapat menentukan jurusan apa yang akan kupelajari di S2-ku. Untuk menentukan pilihan ini, aku memanfaatkan konsep *M-Shaped Person*.

### *M-Shaped Person*

Konsep *T-shaped person* beserta turunannya seperti *M-shaped person* sering digunakan untuk mendeskripsikan tingkat keahlian seseorang. Garis horizontal dalam "T" menggambarkan bidang-bidang keahlian yang berbeda, sedangkan garis vertikal menggambarkan kedalaman pemahaman seseorang di salah satu bidang tersebut.

{{<img caption="Penjelasan <i>I-shaped</i>, <i>T-shaped</i>, dan <i>M-shaped person</i>"
source="[Mäd](https://www.mad.co/insights/the-mad-m-shaped-person)"
src="https://assets-global.website-files.com/62454cf2c3e61dfda26dfade/624aa4164c04f5a361442550__m-shape-02.png" >}}

Seseorang disebut *T-shaped* saat ia memiliki keahlian dasar dalam banyak bidang, namun juga memiliki keahlian mendalam di salah satu bidang tersebut. Sebagai contoh, inilah gambaran keahlianku sebagai *T-shaped person* saat aku lulus kuliah S1 Teknik Elektro ITB:

{{<img caption="Ilustrasi <i>T-Shaped skills</i> Ibra"
src="images/T.jpg" >}}

Saat aku baru lulus S1, aku memiliki dasar keahlian matematika dan fisika yang dimiliki mahasiswa teknik secara umum, ditambah keahlian mendalam di bidang teknik elektro yang kupelajari dari jurusanku.

Saat aku mulai berkarir sebagai *Software Engineer*, bidang keahlian yang kudalami bertambah. Keahlianku sekarang dapat digambarkan seperti berikut:

{{<img caption="Ilustrasi <i>π-Shaped skills</i> Ibra"
src="images/Pi.jpg" >}}

Seseorang dengan bentuk keahlian seperti diatas sering disebut sebagai *π-shaped person* (Karena bentuknya mirip simbol pi atau π).

Saat aku merencanakan jalan hidupku sebagai *underwater robotics engineer*, aku memikirkan keahlian apa yang diperlukan seseorang untuk bekerja dalam posisi ini. Bidang *Robotics* sendiri adalah bidang yang multidisiplin karena membutuhkan keahlian di bidang *Electrical Engineering* (Desain rangkaian listrik robot), *Software Engineering* (Pemrograman logika robot), dan *Mechanical Engineering* (Desain badan dan alat gerak robot). Untuk bidang *Underwater Robotics*, keahlian bidang *Mechanical Engineering* dapat digantikan dengan bidang *Maritime Engineering*. Keahlian ini dibutuhkan untuk desain badan dan alat gerak robot yang spesifik beroperasi dalam air.

Berdasarkan kebutuhan ini, aku memiliki 2 pilihan untuk tujuan pendidikan S2-ku:

1. Memperdalam keahlian Robotika di bidang-bidang yang sudah kupahami: *Electrical Engineering* atau *Software Engineering*. Pilihan ini dapat menjadikanku *expert* dalam bidang Robotika secara umum, namun tidak spesifik ke bidang *Underwater Robotics*.

2. Memperdalam keahlian *Underawter Robotics* dengan mempelajari bidang *Maritime Engineering*. Pilihan ini dapat menjadikanku *expert* yang spesifik untuk bidang *Underwater Robotics*, namun tidak dalam bidang Robotika secara umum.

Karena impianku adalah menjadi CTO yang membangun perusahaan desain dan manufaktur *underwater robotics* baru di Indonesia, aku memilih pilihan kedua. Seorang CTO harus memiliki wawasan menyeluruh tentang proses desain dan manufaktur sebuah *underwater robot*. Aku pun sudah 100% yakin untuk bahwa tujuanku adalah menjadi *underwater robotics engineer*. Daripada belajar robotika secara umum, aku lebih baik fokus di bidang yang lebih spesifik ini.

Maka pilihanku ada dua: Belajar ilmu teknik robotika atau perkapalan. Kedua keilmuan ini telah melekat dengan bidang *underwater robotics* itu sendiri. Karena aku sudah mempelajari ilmu robotika selama kuliah Teknik Elektro ITB, aku **memutuskan untuk mendalami ilmu teknik perkapalan atau *maritime engineering***.

Sebagai *engineer* yang akan bergerak dalam bidang *underwater robotics*, teknik perkapalan adalah keilmuan yang harus kupelajari *sooner or later*. Maka bukankah alangkah baiknya kalau aku mempelajarinya secara terukur dan terstruktur dengan **berkuliah S2 di bidang tersebut?** 

Pilihanku mempelajari *maritime engineering* ini juga merupakan suatu langkah pragmatis. Dengan kondisi industri *underwater robotics* di Indonesia yang masih sangat kecil, aku tetap harus siap untuk bekerja dalam posisi manapun.

Oleh karena itu, aku berharap setelah aku lulus S2 dan bekerja di bidang *underwater robotics* aku akan memiliki keahlian seperti berikut:

{{<img caption="Ilustrasi <i>M-Shaped skills</i> Ibra"
src="images/M.jpg" >}}

Seseorang dengan keahlian mendalam di tiga bidang inilah yang disebut sebagai *M-Shaped person*. Inilah gambaran keahlian diriku yang menjadi pedomanku untuk merealisasikan impianku menjadi *underwater robotics engineer*.

## Merefleksikan Perjalanan

Sampai saat aku menulis ini, masih terdapat keraguan di hatiku terhadap jalan yang telah kupilih. Mungkin, menulis *post* ini adalah salah satu caraku untuk kembali meyakinkan diriku. Setiap kali aku merasa keraguan pada masa yang akan datang, aku bisa kembali mengingatkan diri kenapa aku memulai semua ini.

Pelajaran paling penting yang kudapat sejauh ini adalah: *Find your Niche!*. Aku sadar sejak awal bidang *underwater robotics* sangat spesifik dan *niche*. Dengan mendalami bidang ini, terutama di Indonesia yang ahli *underwater robotics*-nya masih sedikit, aku dapat menjadi orang dengan keahlian yang **unik** dan **spesial**. Walaupun mayoritas orang tidak akan *relate* dengan keahlianku, mereka yang benar-benar membutuhkan keahlian *underwater robotics* akan tau mereka perlu mencari siapa: **Aku!**

Ya, perjalanan ini menyadariku akan satu hal yang sangat memotivasiku untuk terus berjuang: **Aku ini orang yang terpilih**.

### Sang Terpilih

Seringkali, kisah fiksi menceritakan satu orang terpilih yang ditakdirkan untuk melakukan suatu tugas penting untuk menyelamatkan dunia (atau sejenisnya). *Trope* untuk karakter seperti ini disebut dengan *[The Chosen One](https://tvtropes.org/pmwiki/pmwiki.php/Main/TheChosenOne)*.

Baik itu **Harry Potter** yang ditakdirkan mengalahkan Voldemort karena ia selamat dari serangannya saat kecil; **Frodo Baggins** yang ditakdirkan mengalahkan Sauron karena menemukan *The One Ring* milik pamannya; maupun **Luke Skywalker** yang ditakdirkan mengalahkan *The Emperor* karena kesaktiannya sebagai anak rahasia Anakin Skywalker; semua karakter tersebut menjadi ***The Chosen One*** karena mereka berada di suatu **tempat, waktu, dan kondisi yang tepat**.

*Not to be narcissistic*, tapi aku juga merasa telah menjadi ***The Chosen One***. \
*I feel as if everything I have achieved has led to this moment*.

Aku yang sejak kecil bermimpi untuk menjadi pengusaha bidang teknologi.

Aku yang memiliki *privilege* untuk melakukan riset di bidang *underwater robotics* yang sangat langka dan dibutuhkan oleh Indonesia.

Aku yang telah mendapatkan kesempatan untuk melanjutkan kuliah S2 di bidang yang sesuai dengan impianku.

Aku yang mendapatkan dukungan beasiswa dari negara untuk meraih tujuan pendidikanku.

Dan aku yang memberanikan diri pindah karir dan pindah jurusan baru.

Maka kalau bukan aku, siapa lagi?

{{<img caption="<i>So do I, Zelda. So do I.</i>"
source="<i>The Legend of Zelda: Tears of the Kingdom</i>"
src="images/Zelda.jpg" >}}

[^1]: Carnevale, A. P., Cheah, B., & Hanson, A. (2015). The Economic Value of College Majors. Georgetown University Center on Education and the Workforce. Retrieved August 31, 2023, from https://repository.library.georgetown.edu/handle/10822/1050288

[^2]: Seabed 2030. (2023, June 29). Our Mission - Seabed 2030. Retrieved August 31, 2023, from https://seabed2030.org/our-mission/