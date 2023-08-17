---
author: Ibrahim Fadhil
title: "Merakit Rangkaian, Mengarungi Lautan"
description: "Menjelajahi dunia elektroteknik dan perkapalan"
date: "2023-05-10"
tags: 
  - "indonesian"
thumbnail: "/blog/kuliah-online-adaptasi-atau-mati.jpg"
draft: false
---

<!-- Foto LOA keterima di Maritime Engineering Soton -->

*I know what you're (probably) thinking*. Kenapa seorang Ibrahim Fadhil Djauhari, yang kuliah S1 *Electrical Engineering* dan kerja di bidang *Software Engineering*, malah lanjut kuliah S2 di bidang *Maritime Engineering?*?

Jika kalian ingin jawaban yang singkat, jawabannya adalah karena aku ingin mendalami bidang *underwater robotics*.

Jika kalian masih membaca kalimat ini setelah sudah membaca jawaban singkat diatas, aku anggap kalian masih penasaran; kalian ingin tau kisah lengkap bagaimana seorang Ibra bisa memutuskan untuk kuliah S2 di bidang yang cukup jauh dari latar belakangnya.

*Well you're in luck, because that's exactly why I wrote this post.*

Sebagai penerima beasiswa [LPDP](https://lpdp.kemenkeu.go.id/en/), aku pun merasa penjelasan tentang tujuan pendidikanku adalah salah satu bentuk pertanggungjawaban dari uang negara yang akan membiayai kuliah S2 ku.

Terlepas dari itu, aku harap tulisanku ini bisa memberikan wawasan dan inspirasi untuk teman-teman yang sedang memikirkan tujuan pendidikan kuliahnya, memikirkan untuk melakukan pergantian karir dari satu bidang ke bidang lain yang berjauhan, dan/atau penasaran dengan bidang yang akan kutekuni ini.

# Menemukan Panggilan
## Underwater Robots

Eksplorasi bawah laut adalah kegiatan yang sangat sulit untuk dilakukan manusia. Semakin dalam kita menyelam ke bawah laut; semakin banyak oksigen yang perlu kita simpan, semakin sedikit pencahayaan dari permukaan, dan semakin kuat tekanan yang harus kita lawan. 
<!-- Sampai sebagian orang pun berargumen bahwa eksplorasi luar angkasa itu jauh lebih mudah dibanding eksplorasi bawah laut. -->

Oleh karena itulah *underwater robots* dibuat sebagai solusi penjelajahan bawah laut tanpa perlu membahayakan manusia. (???)

<!-- Saat pertama kali diperkenalkan dengan dunia *underwater robotics* melalui riset ITB-HUG, alasanku merasa sangat tertarik dengan bidang ini adalah potensi pemanfaatannya yang besar untuk Indonesia. -->

## ITB *Hybrid Underwater Glider*

Aku pertama kali mengenal dunia *underwater robotics* saat tingkat akhir kuliahku di Teknik Elektro ITB. Untuk lulus dari jurusanku, aku wajib mengerjakan Tugas Akhir (TA) berupa sebuah *Capstone Design Project* bersama kelompok yang berisi 2-3 orang. Dalam TA ini, kami wajib membuat suatu alat untuk menyelesaikan suatu masalah. Setiap kelompok dapat memilih topik untuk TA-nya dari *list* topik yang diajukan oleh para calon dosen pembimbing.

<!-- Gambar Model 3D ITB-HUG -->

Diantara puluhan topik TA yang tersedia, topik yang paling menarik perhatianku adalah topik tentang ITB *Hybrid Underwater Glider* (ITB-HUG). HUG adalah suatu jenis *Autonomous Underwater Vehicle* (AUV), yaitu wahana yang dapat bergerak dalam air tanpa awak untuk melakukan pemetaan bawah laut. Riset AUV, termasuk riset ITB-HUG, sendiri telah dimulai di ITB sejak sekitar tahun 2017. Riset ini dikerjakan oleh gabungan tim mahasiswa S1, S2, dan S3 dengan bimbingan dari Prof. Bambang Riyanto Trilaksono.

Dari membaca deskripsi topik ini saja, aku tau topik ini akan sangat sulit. Membuat robot saja sudah kompleks, apalagi robot yang bisa bergerak di bawah air?

Tapi... Kapan lagi bisa ngoprek kapal selam robot, kan?

Berbekal keyakinan penuh atas kemampuan kami, pengerjaan TA ITB-HUG kami dimulai. Saat kami pertama bergabung dengan tim riset ITB-HUG, seluruh komponen elektronik dan mekanik dari ITB-HUG sudah selesai dirangkai menjadi suatu wahana utuh. Lalu, apa yang sebenarnya perlu kami kerjakan sebagai TA kami?

Walaupun secara komponen sudah lengkap, wahana ITB-HUG belum memiliki kemampuan untuk bergerak secara otonom (Tanpa kendali manusia). Target TA kami adalah untuk membuat sistem yang dapat menggerakkan ITB-HUG secara otonom mengikuti urutan *waypoint* yang diberikan oleh pengguna.

Untuk bisa mencapai tujuan ini, terdapat tiga sistem yang perlu diimplementasikan di ITB-HUG: 
- Sistem *Navigation* yang berfungsi untuk mengetahu posisi, orientasi, dan akselerasi wahana berdasarkan pembacaan data-data sensor 
- Sistem *Guidance* yang berfungsi untuk memandu atau "menyetir" arah gerak wahana untuk menuju suatu *waypoint*
- Sistem *Control* yang berfungsi untuk menggerakkan wahana sesuai arah gerak yang ditentukan sistem *guidance*

Setelah melalui proses yang sulit selama satu tahun mengerjakan TA ini, kami [berhasil](https://digilib.itb.ac.id/gdl/download/214151) mendesain dan mengimplementasi sistem *Navigation*, *Guidance*, dan *Control* dalam *software* dan *hardware* di wahana ITB-HUG. Namun karena kondisi pandemi COVID-19, implementasi kami terbatas dengan pengujian [Hardware-in-the-loop Simulation (HILS)](https://www.hil-simulation.com/images/stories/Documents/Introduction%20to%20Hardware-in-the-Loop%20Simulation.pdf), bukan pengujian langsung di laut. 

Sebelum aku lulus dari ITB, dosen pembimbing TA-ku menawarkan aku untuk tetap aktif membantu riset ITB-HUG. Karena ketertarikan aku terhadap bidang *underwater robotics* ini, sejak saat itu aku memutuskan untuk terus menjadi asisten riset dalam proyek ITB-HUG.
 
## Merintis Karir

Dalam hari-hari menjelang wisuda, berbagai ide tentang rencana karirku kedepannya telah berkumpul di dalam kepalaku. Diantaranya adalah rencana untuk bekerja di bidang robotika, *Internet of Things*, *software engineering*, telekomunikasi, konsultan; atau langsung melanjutkan kuliah S2.

Karena pada saat itu aku belum menemukan alasan kuat untuk kuliah S2, aku pun mencoba melamar pekerjaan dalam berbagai bidang dan posisi. Tujuanku adalah untuk bekerja sambil mengeksplor berbagai bidang baru sebelum menentukan jalur karir jangka panjangku. Selain  itu, tentu aku juga melakukannya karena ingin "tebar jalar" agar tidak menjadi pengangguran (Alasan tipikal *job-seeker fresh graduate*).

Pada akhirnya, *demand* yang tinggi ditambah gaji yang besar dibanding profesi lain berhasil merayuku untuk bekerja *full-time* sebagai *software engineer*. Walaupun berkarir di bidang ini cukup nyaman dan sangat mungkin untuk diperdalam, pada akhirnya aku belum merasa "terpanggil" disini. Aku tidak menemukan masalah spesifik yang ingin aku selesaikan atau keahlian tertentu yang ingin aku kuasai sebagai *software engineer*. Dari sinilah aku sadar bahwa karirku di bidang ini hanyalah sementara, hanya bagian dari proses ekplorasiku untuk menemukan pekerjaan sebenernya yang ingin aku tekuni.

Selama bekerja menjadi *software engineer*, aku tetap berkecimpung di dunia *underwater robotics* sebagai *part-time research assistant* di riset ITB-HUG. Pada saat itu, ide untuk memfokuskan karirku spesifik ke bidang *underwater robotics* memang sempat melintas di pikiran. Namun, keyakinanku untuk menyelam di bidang *underwater robotics* baru memuncak karena suatu kejadian pada awal tahun 2021...

## Tragedi di Laut Bali
<!-- Berita Insiden KRI Nanggala 402 -->

Pada tanggal 24 April 2021, 838 meter di bawah perairan laut Bali, kapal selam KRI Nanggala 402 bertemu dengan tempat peristirahatan terakhirnya. Seluruh Indonesia berduka cita atas hilangnya sang kapal selam beserta 53 awaknya. Tanpa peralatan yang memadai untuk melakukan pencarian dalam kedalaman lebih dari 800 meter di bawah air, Indonesia harus bergantung dengan peralatan pinjaman dari para negara tetangga.

Salah satu aset kunci dalam pencarian KRI Nanggala 402 adalah kapal [MV Swift Rescue](https://katadata.co.id/sortatobing/berita/6083c1b7f0536/mv-swift-rescue-kapal-milik-singapura-yang-ikut-mencari-kri-nanggala) milik Angkatan Laut Singapura. Kapal ini merupakan satu-satunya *Submarine Rescue Vessel* di Asia Tenggara yang dilengkapi oleh sebuah *Remotely Operated Vehicle* (ROV) untuk pencarian kapal selam. Dengan bantuan ROV tersebut, tim pencarian berhasil mendapatkan foto dan video pertama di lokasi tenggelamnya KRI Nanggala 402.

{{<img caption="Kronologi Penemuan KRI Nanggala 402"
source="[TEMPO](https://grafis.tempo.co/read/2658/kronologi-kri-rigel-dan-mv-swift-rescue-temukan-kri-nanggala-402)"
src="https://cdn.tmpo.co/flash/data/flashgrafis/2658/20210426kronologi-nanggala-ditemukan.jpg" >}}

Dengan insiden ini, aku tersadar bahwa keterbatasan *underwater robots* di Indonesia sudah menjadi isu keamanan nasional. Dan aku, sebagai seseorang yang telah berkecimpung di bidang ini, tidak bisa tinggal diam.

Saat seluruh penjuru tanah air berduka, aku membulatkan tekadku untuk mendalami bidang *underwater robotics* dengan melanjutkan pendidikanku ke jenjang yang lebih tinggi (S2).

# Meyakinkan Pilihan

Untuk meyakinkan diri bahwa tujuan hidupku adalah menjadi *underwater robotics engineer*, aku mengimplementasikan [Ikigai](https://positivepsychology.com/ikigai/) sebagai caraku untuk merefleksikan diri.

## *Ikigai*

{{<img caption="Kronologi Penemuan KRI Nanggala 402"
source="[TheMindFool](https://themindfool.com/ikigai/)"
src="https://themindfool.com/wp-content/uploads/2020/09/Ikigai_doagram-15-15-1024x1024.jpg" >}}

*Ikigai* adalah sebuah konsep dari Jepang yang dapat digunakan untuk menentukan **tujuan hidup**. Tujuan hidup dalam *Ikigai* merupakan irisan dari empat aspek:

1. *What you love*
2. *What you are good at*
3. *What you can be paid for*
4. *What the world needs*

Dengan mencari irisan dari empat aspek tersebut, kita dapat menemukan tujuan hidup yang kita sukai, kita kuasai, dapat menghasilkan uang, dan dapat membantu orang lain. Berikut adalah caraku dalam menemukan *Ikigai*-ku:

### 1. *What you love*

Aku telah dikenalkan dengan teknologi seperti komputer dan *video game console* sejak kecil. Sebagai anak kecil, kemampuan untuk bermain beragam *video game* dengan teknologi ini sangat menarik perhatianku. Seiring aku tumbuh, rasa keingintahuanku tentang bagaimana cara teknologi bekerja, khususnya komputer, terus meningkat. Aku pun berandai-andai untuk suatu saat bisa membuat teknologi canggih seperti senjata laser dan mesin waktu. Keinginan inilah yang pada akhirnya akan membawaku kuliah di Teknik Elektro ITB.

Puncak aktualiasi diri bagi seorang pecinta teknologi adalah membuat teknologi baru. Di sisi lain, permasalahan di dunia tidak ada habisnya. Oleh karena itu, aku yakin bahwa tujuan hidupku adalah membuat teknologi sebagai solusi dari sebagian permasalahan dunia.

### 2. *What you are good at*

Karena ketertarikanku dengan teknologi dan keterpaparanku dengan film *science-fiction*, aku telah minat dengan ilmu Fisika dan Matematika sejak kecil. Minat membantuku mendapatkan nilai yang cukup baik dalam dua mata pelajaran ini selama sekolah dan mendorongku untuk mempelajari bidang *Engineering* saat kuliah.

Walaupun aku tidak menguasai pelajaran Fisika & Matematika, aku yakin dua bidang ini adalah bidang yang paling aku pahami diantara semua bidang keilmuan lainnya. Kedua bidang ini adalah pondasi dari segala ilmu *Engineering* yang telah dan akan aku pelajari, baik itu ilmu Teknik Elektro, Informatika, maupun Perkapalan.

### 3. *What you can be paid for*

Secara umum, bidang STEM (*Science, Technology, Engineering, and Mathematics*) adalah salah satu bidang keilmuan dengan [gaji paling tinggi](https://cew.georgetown.edu/cew-reports/valueofcollegemajors/) di dunia. Dengan aku bekerja di bidang ini; baik itu sebagai *Electrical*, *Software*, atau *Maritime Engineer*; seharusnya aku tidak akan kesulitan secara finansial (aminnn).

### 4. *What the world needs*

Sebagian besar topografi bawah laut Indonesia belum dipetakan (???). Sebagian besar dasar laut di dunia juga belum terpetakan.
Penguasaan terhadap *underwater robotics* berperan penting untuk pertahanan dan keamanan negara (???)

Saat ini, hanya ada satu perusahaan yang bergerak di bidang *underwater robotics* di Indonesia: Robo Marine Indonesia. Sedangkan dari sisi akademik, hanya ada 4 universitas yang melakukan riset *underwater robotics*, khususnya tentang AUV (Termasuk riset ITB-HUG).

Aku, sebagai orang yang ber-*privilege* mendapatkan kesempatan melakukan riset penting dalam bidang yang sangat langka ini (ITB-HUG), mengemban tanggung jawab untuk terus mengembangkan bidang *underwater robotics* Indonesia.

Hasilnya, aku membuat diagram *Ikigai* sebagai berikut (Disederhanakan):

<!-- Gambar Ikigai Ibra -->

Proses refleksi dalam mencari *Ikigai* ini meyakinkanku bahwa menjadi *underwater robotics engineer* adalah tujuan hidup paling cocok untukku.

# Membangun Impian
## Mimpi

Sejak kecil, aku sering membaca kisah tentang orang-orang sukses dunia. Dua orang diantara mereka meninggalkan kisah yang paling berkesan bagiku: Bill Gates & Steve Jobs. Kedua pengusaha muda yang "seangkatan" ini terkenal dengan kesuksesannya membangun Microsoft dan Apple, dua nama besar dari *Silicon Valley* yang masih disegani dunia sampai hari ini. Terlepas dari beragam kontroversi mereka, kemampuan mereka untuk membuat suatu **inovasi teknologi** kemudian mengembangkan inovasi tersebut menjadi **perusahaan penghasil teknologi** telah menginspirasiku sejak dulu untuk mengikuti jalan mereka.

Aku melihat kewirausahaan sebagai metode paling *sustainable* untuk mengembangkan teknologi seperti *underwater robots*. Karena masalah yang dapat diselesaikan teknologi ini sangatlah rumit dan pengembangannya membutuhkan dukungan kapital yang besar. Menjual suatu teknologi untuk mereka yang membutuhkannya (dengan harga yang sesuai) adalah metode yang dapat menjamin proses pengumpulan kapital sekaligus pengembangan teknologi tersebut.

Melihat kondisi industri *underwater robotics* yang masih sangat kecil di Indonesia, aku melihat ada potensi besar untuk pengembangan perusahaan-perusahaan baru di bidang ini. Oleh karena itu, visiku adalah untuk membangun perusahaan desain dan manufaktur *underwater robots* di Indonesia. Dalam perusahaan ini aku ingin berperan sebagai *Chief Technology Officer* (CTO), *Vice President of Engineering*, atau peran strategis lainnya dimana aku dapat memimpin proses desain dan manufaktur *underwater robots*.

Jika memang tidak memungkinkan untuk membangun perusahaan baru, aku tetap berambisi menjadi CTO / VP Engineering dari perusahaan *underwater robotics* eksisting agar dapat mengembangkannya lebih jauh. 

Aku sadar industri ini memiliki *barrier of entry* yang sangat tinggi. Akan diperlukan usaha dan waktu yang tidak sedikit untuk bisa merealisasikan mimpi tersebut. Oleh karena itu, langkah pertamaku adalah untuk menempuh pendidikan S2 untuk mendalami keahlianku di bidang *underwater robotics*. Setelah lulus, aku akan bekerja di industri ini sambil melanjutkan riset ITB-HUG. Harapanku adalah aku dapat mulai menginisiasi perusahaan baru ku dalam 10 tahun setelah aku lulus S2.

Karena bidang *underwater robotics* adalah keilmuan yang multidisiplin, aku perlu menentukan disiplin apa yang akan kuperdalam dari bidang ini. Spesifiknya, pilihan ini dapat menentukan jurusan apa yang akan kupelajari di S2 ku. Untuk menentukan pilihan ini, aku memanfaatkan konsep *M-Shaped Person*.

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

Maka pilihanku ada dua: Belajar ilmu teknik robotika atau perkapalan. Kedua keilmuan ini telah melekat dengan bidang *underwater robotics* itu sendiri. Karena aku sudah mempelajari ilmu robotika selama S1 Teknik Elektro ITB, aku memutuskan untuk mendalami ilmu teknik perkapalan atau *maritime engineering*.

Sebagai *engineer* yang akan bergerak dalam bidang *underwater robotics*, teknik perkapalan adalah keilmuan yang harus kupelajari *sooner or later*. Pilihanku mempelajari *maritime engineering* ini juga merupakan suatu langkah pragmatis. Dengan kondisi industri *underwater robotics* di Indonesia yang masih sangat kecil, aku tetap harus siap untuk bekerja dalam posisi manapun.

Oleh karena itu, aku berharap setelah aku lulus S2 dan bekerja di bidang *underwater robotics* aku akan memiliki keahlian seperti berikut:

<!-- Gambar M-Shaped Ibra -->

Seseorang dengan keahlian mendalam di tiga bidang inilah yang disebut sebagai *M-Shaped person*. Inilah gambaran keahlian diriku yang menjadi pedomanku untuk merealisasikan impianku.


# Meratapi Masa Depan

Di banyak kisah fiksi, terdapat sebuah *trope* umum bernama ***The Chosen One***. Seringkali, kisah fiksi menceritakan satu orang terpilih yang ditakdirkan untuk melakukan suatu tugas penting.

Baik itu **Harry Potter** yang ditakdirkan mengalahkan Voldemort karena ia selamat dari serangannya saat kecil; **Frodo Baggins** yang ditakdirkan mengalahkan Sauron karena menemukan *The One Ring* milik pamannya; maupun **Luke Skywalker** yang ditakdirkan mengalahkan *The Emperor* karena kesaktiannya sebagai anak rahasia Anakin Skywalker; semua karakter tersebut menjadi ***The Chosen One*** karena mereka berada di suatu tempat, waktu, dan kondisi yang tepat.

*Not to be narcisstic*, tapi saat ini aku merasa aku juga telah menjadi ***The Chosen One***. *It's as if everything I have achieved has led to this moment*. 

Aku memiliki *privilege* untuk melakukan riset di bidang yang sangat langka dan dibutuhkan oleh Indonesia. 

Aku telah mendapatkan kesempatan untuk melanjutkan kuliah S2 di bidang yang sesusai dengan tujuanku. 

Aku mendapatkan dukungan beasiswa dari negara untuk meraih tujuan pendidikanku. 

Aku yang bermimpi sejak kecil untuk menjadi pengusaha, sebuah mimpi yang dapat direalisaikan dengan membangun perusahaan *underwater robotics* nanti.

Maka kalau bukan aku, siapa lagi? 

<!-- Gambar Zelda bawa Master Sword sambil ngomong "I know why I am here. It is something only I can do." -->

Ibrahim Fadhil Djauhari

(Future) Underwater Robotics Engineer