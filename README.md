<p align="center">
	<img src="https://media.giphy.com/media/Xr2km20NNBNqSN6iwu/giphy.gif" width="200" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="center">SHIRAORI BOT MD</h1>





[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ilmanhdyt/ShiraoriBOT)

[![Grup WhatsApp](https://img.shields.io/badge/GroupWhatsapp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/D7TmQm7UcfIBELBux19kIA)

[![Contact Me](https://img.shields.io/badge/ContactMe-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/6281351047727)


## UNTUK PENGGUNA WINDOWS/VPS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/ilmanhdyt/ShiraoriBOT
cd ShiraoriBOT
npm install
npm update
npm index
```

---------

## UNTUK PENGGUNA TERMUX
```bash
git clone https://github.com/ilmanhdyt/ShiraoriBOT
cd ShiraoriBOT
npm i
npm update
pkg install bash
bash install.sh
node .
```

## UNTUK PENGGUNA HEROKU

### Instal Buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git


## Edit file
- Ganti Nomor Owner [disini](https://github.com/ilmanhdyt/ShiraoriBOT/blob/main/config.js)
- Ganti Tampilan Menu [disini](https://github.com/ilmanhdyt/blob/main/plugins/menu.js)

- Kalian bisa menambah fitur dengan cara pull request


---------

## Arguments `node . [--options] [<session name>]`



#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--restrict`

Mengaktifkan plugin terbatas (yang dapat menyebabkan nomor Anda **diblokir** jika digunakan terlalu sering)

* Administrasi Grup `add, kick, promote, demote`, `kickall`

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--autoread`

Jika diaktifkan, semua pesan masuk akan ditandai sebagai telah dibaca

### `--nyimak`

Tidak ada bot, cukup cetak pesan yang diterima dan tambahkan pengguna ke database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

 [![Nurutomo](https://github.com/Nurutomo.png?size=150)](https://github.com/Nurutomo) | [![Ilman](https://github.com/ilmanhdyt.png?size=150)](https://github.com/ilmanhdyt)
----|----
[Nurutomo](https://github.com/Nurutomo) | [Ilman](https://github.com/ilmanhdyt) 
 Author | Recode 


### Donated

[`Saweria`](https://saweria.co/ilmanhdyt)
