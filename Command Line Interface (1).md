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

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
