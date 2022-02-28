<p align="center">
	<img src="https://i.ibb.co/dDwRbSp/Whats-App-Image-2022-02-27-at-7-23-34-AM.jpg" width="35%" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="center">hyungbot</h1>


[![Grup WhatsApp](https://img.shields.io/badge/WhatsApp%20Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/IRrJiBsdSUy38vcZfXtZth)

## UNTUK PENGGUNA WINDOWS/VPS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/akmalhax/hyungbot.git
cd hyungbot
npm i
node .
```

---------

## UNTUK PENGGUNA TERMUX
```
$ pkg update && upgrade -y
$ apt update && upgrade -y
$ pkg install ffmpeg
$ pkg install nodejs-lts
$ pkg install git
$ git clone https://github.com/akmalhax/hyungbot.git
$ cd hyungbot
$ npm i
$ node .
```
---------
## UNTUK PENGGUNA HEROKU

### Instal Buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/mcollina/heroku-buildpack-imagemagick.git

---------
