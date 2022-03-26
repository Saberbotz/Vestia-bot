 <p align="center">
	<img src"https://images.app.goo.gl/fuNGLLpEkWqz6d6p8"
</p>
<h1 align="center">VESTIA BOT</h1>

---
## My Project
> WhatsApp Bot normal [`Vestaia-Bot`](https://github.com/Saberbotz/Vestia-bot)


## UNTUK PENGGUNA WINDOWS/VPS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/Saberbotz/Vestia-bot
cd Vestia-bot
npm install
npm update
npm index
```

---------

## UNTUK PENGGUNA TERMUX
```bash
git clone https://github.com/Saberbotz/Vestia-bot
cd Vestia-bot
npm i
npm update
node .
```

## UNTUK PENGGUNA HEROKU

### Instal Buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git


## Edit file
- Ganti Nomor Owner [disini](https://github.com/ilmanhdyt/ShiraoriBOT/blob/main/config.js)
- Ganti Tampilan Menu [disini](https://github.com/ilmanhdyt/ShiraoriBOT/blob/main/plugins/menu.js)

- Kalian bisa menambah fitur dengan cara pull request


---------

## Arguments `node . [--options] [<session name>]`

#### Contoh: `node . --self --restrict --autoread`

### `--self`

Aktifkan mode self (Mengabaikan yang lain)

### `--prefix <prefixes>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <json-server-url>`

Gunakan db eksternal alih-alih db lokal, 
Contoh Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

Server harus memiliki spesifikasi seperti ini


### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--restrict`

Mengaktifkan plugin terbatas (yang dapat menyebabkan nomor Anda **diblokir** jika digunakan terlalu sering)

* Administrasi Grup `add, kick, promote, demote`, `kickall`


### `--autoread`

Jika diaktifkan, semua pesan masuk akan ditandai sebagai telah dibaca


---------

 [![Nurutomo](https://github.com/Nurutomo.png?size=150)](https://github.com/Nurutomo) | [![Ilman](https://github.com/ilmanhdyt.png?size=150)](https://github.com/ilmanhdyt)
----|----
[Nurutomo](https://github.com/Nurutomo) | [Ilman](https://github.com/ilmanhdyt)
 Author | Recode 


### Donated

[`Saweria`](https://saweria.co/ilmanhdyt)
