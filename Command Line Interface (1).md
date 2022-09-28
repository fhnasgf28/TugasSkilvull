# Command Line Interface
## _The Last Markdown Editor, Ever_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

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
