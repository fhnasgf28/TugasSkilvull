# Command Line Interface

## _The Last Markdown Editor, Ever_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


## HTML & CSS
### Sejarah singkat HTML
 - HTML pertama kali dikembangkan oleh Tim Berners-Lee dari organisasi European Organization for Nuclear Research (CERN) tahun 1990. Markup language atau HTML ini diciptakan oleh suatu perusahaan penjual perangkat keras dan lunak yakni IBM atau International Bussiness Machines.

 - Sekitar era 1980an, IBM menciptakan sebuah bahasa yang menggabungkan tag atau simbol dengan teks dalam sebuah dokumen. Bahasa yang diciptakan oleh IBM ini dikenal dengan sebutan markup language atau Generalized markup language (GML).
 - Kemudian rilis versi pertama HTML ditulis oleh Tim Berners-Lee pada 1993. Dikutip dari Washington.edu, sejak itu, mulai banyak versi HTML yang berbeda. Versi yang paling banyak digunakan sepanjang tahun 2000-an adalah HTML 4.01, yang menjadi standar resmi sejak bulan Desember 1999.

- Versi lain, XHTML, adalah penulisan ulang HTML sebagai bahasa XML. XML adalah bahasa markup standar yang digunakan untuk membuat bahasa markup lainnya. Ratusan bahasa XML masih digunakan saat ini, termasuk GML (Geography Markup Language), MathML, MusicML, dan RSS (Really Simple Syndication).

- HTML menjadi standar resmi pada tahun 2000, dan diperbarui pada tahun 2002. XHTML sangat mirip dengan HTML, tetapi memiliki aturan yang lebih ketat. Aturan yang ketat diperlukan untuk semua bahasa XML, karena tanpanya, interoperabilitas antar aplikasi tidak mungkin dilakukan.

- Sebagian besar halaman di Web saat ini dibuat menggunakan HTML 4.01 atau XHTML 1.0. Namun, dalam beberapa tahun terakhir, W3C bekerja sama dengan organisasi lain, WHATWG. Mereka telah mengerjakan versi baru dari HTML, yakni HTML5. Sejak 2011, HTML5 masih berupa spesifikasi draf dan belum menjadi standar resmi.

 - HTML adalah bahasa standar pemrogaman yang digunakan untuk membuat halaman website, yang diakses melalui internet. Singkatan dari "Hypertext Markup Language" atau "bahasa markup".
 - Dilansir Techterms, "Hypertext" mengacu pada hyperlink yang mungkin terdapat dalam halaman HTML.
 - HTML disusun berdasar kode dan simbol tertentu, yang dimasukkan dalam sebuah file atau dokumen.
 - HTML tidak memiliki fitur pemrograman, seperti variabel, perulangan, dan fungsi.
 ### Fungsi HTML
 - HTML digunakan untuk membuat dokumen elektronik (disebut halaman) yang ditampilkan di World Wide Web (www).
 - Setiap halaman berisi serangkaian koneksi ke halaman lain yang disebut hyperlink
 - Kode HTML memastikan format teks dan gambar yang tepat untuk browser Internet. Tanpa HTML, browser tidak akan tahu bagaimana menampilkan teks sebagai elemen atau memuat gambar atau elemen lainnya.
 - HTML juga menyediakan struktur dasar halaman, di mana Cascading Style Sheets dihamparkan untuk mengubah tampilannya.
 * fungsinya adalah
 1. Fungsi utama HTML, untuk membuat suatu halaman website yang bisa dibaca dan dipahami dengan lebih mudah. Seluruh laman website yang ada di internet, dibuat dengan HTML dan tak ada pengecualian.
 2. Menandai teks pada suatu laman. HTML ditulis pada suatu halaman dokumen dengan tag atau simbol tertentu. Simbol dan tag tersebut akan membuat tampilan teks menjadi tebal, miring, bergaris tebal dan sebagainya.
 3. Sebagai dasar website. Website yang dibuat tentu memiliki beberapa fitur. Dibuat menggunakan java script untuk mengatur perilaku web, implemetasi bahasa pemrograman server PHP, dan mendesain web menggunakan CSS.
 4. Menampilkan tabel, gambar, video dan lainnya. Umumnya di halaman website atau blog kita tidak bisa langsung meletakkan tabel, gambar maupun video.
 5. Menandai elemen dan membuat online form. HTML berfungsi menandai bagian-bagian dalam website di antaranya header, footer, main, navigation dan sebagainya.

## CSS
- CSS adalah bahasa Cascading Style Sheet dan biasanya digunakan untuk mengatur tampilan elemen yang tertulis dalam bahasa markup, seperti HTML. CSS berfungsi untuk memisahkan konten dari tampilan visualnya di situs.
- CSS dibuat dan dikembangkan oleh W3C (World Wide Web Consortium) pada tahun 1996 untuk alasan yang sederhana. Dulu HTML tidak dilengkapi dengan tags yang berfungsi untuk memformat halaman. Anda hanya perlu menulis markup untuk situs.
- CSS dibuat untuk dapat bekerja bersama dengan bahasa markup seperti HTML. 
- Biasanya CSS digunakan untuk mengatur tampilan halaman.
- Ada tiga style di CSS, dan untuk menerapkan CSS di banyak halaman pada waktu bersamaan, gunakan External style.
- Saat ini sudah banyak website yang menggunakan CSS. Hal ini dikarenakan CSS adalah salah satu bahasa markup yang diwajibkan ada.
 # CLI
command Line Interface merupakan antar muka berbasis teks yang biasa digunakan untuk menjalankan program, mengelola file komputer dan berinteraksi dengan komputer.

- CLI bisa dikatakan sebagai shell yang berbasis teks, shell ini merupakan program yang menerima perintah, kemudian meneruskan perintah tersebut ke system untuk dieksekusi.
- shell juga ada yang berbasi grafis, kita seringkali menyebutnya dengan GUI(Graphical User Interface).
- ada banyak macam GUI, tapi yang terkenal ada di 3 sistem operasi seperti Mac, windows dan Linux(Ubuntu dkk).

## Navigasi CLI

Navigasi menggunakan CLI, kalau kita perhatikan. sebuah filesystem mengatur bagaimana data disimpan dalam sebuah sistem itu mirip dengan struktur Pohon(Tree).

- ada banyak sekali command Line untuk menavigasi Diantaranya ada , Pwd,ls,cd(directory)
- adapun directory yang paling atas atau paling pertama disebut "root directory"
- "pwd" digunakan untuk melihat direktori kita berada saat ini
- "ls" selanjutnya ada list, list ini digunakan untuk melihat isi dari direktori
- "cd" atau change directory digunakan untuk berpindah ke direktori lain.

## Manipulasi files dan Directory

- "touch" command yang digunakan untuk membuat sebuah file
- "mkdir" command yang digunakan untuk membuat sebuah direktori
- untuk melihat isi files kita bisa menggunakan command head,tail,cat
- "head" digunakan untuk melihat beberapa line awal dari sebuah file text
- "tail" digunakan untuk melihat beberapa line awal dari sebuah file text
- "cat" digunakan untuk melihat isi sebuah file
- untuk menyalin, memindahkan, dan menghapus files & directory kita bisa menggunakan command cp, mv, rm
- "cp" digunakan untuk mengcopy files atau directory
- "mv(move)" digunakan untuk memindahkan files atau directory juga bisa digunakan untuk rename.
- "rm(remove)" digunakan untuk menghapus file atau directory.

## Git & github

- Git merupakan Tools yang sangat berguna untuk para programmer
- git merupakan sebagai Version Contol System(VCS)
  -jadi VCS ini berguna untuk mencatat setiap kali ada perubahan
- pada file(code) yang kita buat baik secar individu maupun tim
- pada git setiap kali file yang disimpan akan terlacak,
- bagaimana perubahannya atau siapa saja yang mengubah file tsb
- dengan menggunakan kedua tools tersebut akan memudahkan kolaborasi pada saat membuat proyek yang bersifat tim dan kompleks.

beberapa kondisi file pada Git

- Modified, Staged & commited
- Modified merupakan suatu kondisi dimana revisi maupun perubahan yang sudah dilakukan tetapi belum ditandai(untracked) dan belum disimpan dalam version control.
- Staged merupakan suatu kondisi dimana revisi yang dilakukan sudah ditandai(modified) namun belum disimpan di version control.
- committed merupakan suatu kondisi dimana revisi sudah disimpan pada version control.

## Algoritma

- Algoritma adalah suatu daftar langkah demi langkah yang terhingga dari instruksi-intruksi yang terdefinisikan sehingga bisa menyelesaikan tugas yang diberikan.
- Fungsi utama algoritma

* untuk memecahkan suatu masalah
* Memudahkan dalam membuat suatu program untuk penyelesaian masalah tertentu
* dapat digunakan berkali kali untuk menyelesaikan suatu permasalahan
* Membuat sebuah program yang rumit dan besar menjadi sederhana
* Mengatasi permasalahan yang ada secara urut
* Memecahkan program yang rumit sehingga memungkinkan adanya perhitungan tingkat tinggi
* menggunakannya secara berulang atau lebih dari satu kali penggunaan

## ciri Algoritma

- Finiteness (keterbatasan)
  Algoritma harus berhenti setelah mengerjakan sejumlah langkah terbatas, dengan kata lain ada tujuan akhir yang dicapai, sehingga suatu program akan berhenti ketika tujuan akhir telah tercapai. Program yang tidak pernah berhenti mengindikasikan bahwa program tersebut berisi algoritma yang salah.
- Definiteness (kepastian)
  Setiap langkah harus didefinisikan dengan tepat dan tidak berarti-dua (ambiguous). Ada intruksi - intruksi yang jelas dan juga tidak ambigu, sehingga tidak terjadi kesalahan di dalam menghasilkan output.
- Input (masukan)
  Input ini merupakan suatu permasalahan yang dihadapi serta akan dicarikan solusinya. Algoritma ini mempunyai nol atau lebih input, yaitu besaran yang diberikan kepada algoritma untuk diproses.
- Output (keluaran)
  Algoritma memiliki nilai nol atau lebih keluaran (output). Output ini tentunya harus berupa solusi atau penyelesaian dari suatu masalah. Output dapat berupa pesan atau besaran yang berhubungan dengan input.
- Effectiveness (efektif)
  Algoritma harus sangkil (effective), setiap urutan atau langkah harus sesederhana mungkin, sehingga dapat dikerjakan dalam sejumlah waktu yang masuk akal.

## Proses Algoritma

- Sequence = instruksi yang dijalankan secara berurutan
- Selection = instruksi yang dijalankan memenuhi suatu kondisi
- Iteration = instruksi yang berulang kali dijalankan selama memenuhi suatu kondisi
- Concurrent = instruksi yang dijalankan secara bersamaan

## Penyajian Algoritma

- Deskriptif
- Flow Chart
- pseudoCode

## Javascript

- Javascript merupakan bahasa pemrograman yang bertujuan untuk memanipulasi website agar lebih interaktif.
- Javascript dikembangkan pertama kali oleh Brendan Eich pada tahun 1995.
- Awalnya, bahasa ini diberi nama “Mocha”, kemudian dirubah lagi menjadi “LiveScript”, dan terakhir ialah “JavaScript”, yang dipakai sampai sekarang.
- Ada 2 cara penulisan javascript yang bisa dipakai, yaitu secara Internal dan External.
- Untuk penulisan secara Internal, kita akan menuliskan kode/syntax JavaScript di dalam HTML secara langsung menggunakan tag <script>
  > cth
  ! [ini adalah contoh penulisan internal javascript](/asset/foto1.jpg)
- Sedangkan untuk penulisan external, kita bisa memisahkan file Javascript, kemudian menghubungkannya ke file HTML
- Hal yang harus kita persiapkan untuk belajar Javascript
  1. Text Editor
    Kita butuh aplikasi Text Editor untuk menulis kode kita. 
  2. Browser
    browser favorit seperti: Google Chrome, Edge, Firefox, dan lain-lain.
  3. Koneksi Internet
    untuk berjaga jaga apabila kita ingin mengetahui dokumentasi dari apa yang kita pelajari.

## Javascript Dasar
  * Scope
  - Scope adalah sebuah tempat dimana sebuah variabel bisa diakses.
  - Scope dalam Javascript terbagi menjadi 2 yaitu Global Scope dan Local Scope.
  - Global Scope adalah variabel yang bisa diakses dimana saja.
  - Local Scope adalah variabel yang hanya bisa diakses di dalam suatu fungsi.
  - Scope di JavaScript biasanya kita buat batasannya menggunakan simbol curly brackets ({}).
  -	Global Scope adalah scope yang paling luar di javascript, global scop berarti variabel yang dibuat bisa diakses dimanapun dalam suatu file, agar menjadi global scope, suatu variabel harus dideklarasikan diluar blocks.
  > cth
  - Local Scope adalah scope yang berada di dalam suatu fungsi, local scope berarti variabel yang dibuat hanya bisa diakses di dalam fungsi tersebut, agar menjadi local scope, suatu variabel harus dideklarasikan di dalam blocks.Local scope juga sering disebut function scope. Variabel yang dideklarasikan dalam local scope hanya bisa di akses dalam scope tersebut dan tidak dapat diakses secara global atau local scope yang lain
  > cth
  - Block Scope, dari pembaharuan ES6 terdapat dua keyword baru untuk mendeklarasikan sebuah variabel, yaitu let dan const. Let dan const ini dapat digunakan untuk mendeklarasikan variabel dalam block scope. Secara umum, block scope adalah ruang lingkup di dalam area kurung kurawal {}, seperti if statement, switch statement, for loop, while loop, dan do while loop. Variabel yang dideklarasikan dalam block scope biasa disebut block level variable. Contoh block scope: contoh 