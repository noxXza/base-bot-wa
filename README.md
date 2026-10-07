<div align="center">

# 🌙 Luna-MD

### **Lebih dari sekadar bot.**

Bot WhatsApp Multi-Device dengan berbagai fitur otomasi, hiburan, utilitas,
dan pengalaman interaktif dalam satu sistem.

<br>

<img src="media/Luna.jpg" width="280" alt="Luna-MD">

<br><br>

<img src="https://img.shields.io/badge/WhatsApp-Multi--Device-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-20%2B-339933?style=for-the-badge&logo=node.js&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-CommonJS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111111">
<img src="https://img.shields.io/badge/Source-Open%20Source-8A2BE2?style=for-the-badge">

</div>

---

# 🌙 Tentang Luna-MD

**Luna-MD** adalah bot WhatsApp Multi-Device yang dibuat dengan sistem **case**
dan dikembangkan untuk menangani berbagai kebutuhan, mulai dari grup,
downloader, AI, permainan, tools, pembayaran, sampai pengelolaan bot tambahan.

Luna-MD menggunakan **noxleyss** sebagai library WhatsApp dan memiliki struktur
yang memisahkan bagian utama bot, sistem pesan, database, jadibot, library,
serta daftar menu.

> **Konsep Luna-MD:** satu bot, banyak kebutuhan, tetapi tetap dibuat agar
> mudah dikembangkan dan dipelihara.

---

# ✨ Yang Menjadi Andalan

<table>
<tr>
<td width="50%">

### 🎮 Game Rich HTML
Bukan hanya game berbasis teks. Luna-MD memiliki beberapa game interaktif
dengan konsep Rich HTML seperti:

- 🧠 Memory Match
- 🀄 Mahjong
- 🧩 Puzzle
- 🏎️ Racing
- 🐦 Angry Birds
- 🕹️ Geometry
- 🧱 Tetris
- ♟️ Chess

</td>
<td width="50%">

### 🤖 Sistem Jadibot
Luna-MD memiliki sistem untuk menjalankan bot tambahan melalui pairing code.

Beberapa bagian yang tersedia:

- Pairing code
- Pengelolaan sesi
- Pemulihan sesi
- Pembersihan sesi
- Batas maksimal **20 jadibot**
- Pemisahan sesi bot utama dan bot tambahan

</td>
</tr>

<tr>
<td>

### 🧠 CRM & Relay Message
Tersedia sistem untuk kebutuhan pesan tingkat lanjut, termasuk konsep
**Create Relay Message**, pemeriksaan struktur pesan, dan proses relay.

</td>
<td>

### 💳 Sistem Pembayaran
Menu pembayaran menyediakan tampilan khusus untuk:

- Dana
- OVO
- GoPay
- ShopeePay
- QRIS

Beberapa pembayaran juga menggunakan tombol **salin nomor** agar lebih praktis.

</td>
</tr>
</table>

---

# 📦 Fitur Utama

Tidak semua command ditampilkan di README ini. Berikut hanya beberapa
fitur yang mewakili kemampuan utama Luna-MD.

| Kategori | Contoh Fitur |
|:---|:---|
| 🤖 **AI** | GPT, Claude, Gemini, DeepSeek, Meta AI |
| 📥 **Downloader** | TikTok, Instagram, YouTube, Facebook, Pinterest |
| 👥 **Grup** | Anti-link, welcome, tagall, hidetag, open/close grup |
| 🎨 **Maker** | Brat, quote image, fake chat, meme, berbagai generator |
| 🖼️ **Sticker & Media** | Sticker, watermark, enhance, upscale, remove background |
| 🔎 **Stalker & Info** | Instagram, TikTok, Telegram, GitHub, Play Store |
| 🎮 **Game** | Racing, Tetris, Geometry, Chess, Puzzle, Memory Match |
| 🛠️ **Utility** | Kalender, total chat, readmore, informasi fitur |
| 👑 **Owner** | Kontrol bot, evaluasi, broadcast, database, pengaturan |
| 🔗 **Jadibot** | Pairing, sesi child bot, restore, cleanup |

---

# 🎮 Game

Salah satu bagian yang menjadi pembeda Luna-MD adalah kumpulan game yang
lebih beragam dibanding game chat biasa.

Beberapa contoh:

```text
.tebakbom
.tebakangka
.ttt
.memory-match
.mahjong
.puzzle
.racing
.angrybirds
.flappy
.snake
.geometry
.tetris
.sonic
.chess
```

Beberapa game dirancang sebagai **Rich HTML**, sehingga pengalaman bermain
tidak hanya berupa balasan teks WhatsApp.

---

# 📥 Downloader

Luna-MD menyediakan beberapa utilitas media dan downloader.

Contoh:

```text
.tt
.ig
.fb
.yt
.play
.play2
.playsf
.pindown
.pin
.mediafire
```

Selain download, terdapat juga beberapa fitur pemrosesan dan konversi media.

---

# 👥 Grup & Moderasi

Untuk kebutuhan grup, Luna-MD menyediakan beberapa fungsi administrasi,
misalnya:

```text
.open
.closetime
.antilink
.antilink2
.welcome
.tagall
.ht
.add
.kick
.delete
.idgc
```

Fitur tersebut dapat digunakan untuk membantu pengelolaan grup dan
otomatisasi tugas admin.

---

# 🎨 Maker & Pengolahan Media

Bagian maker digunakan untuk membuat atau memproses berbagai jenis media.

Contoh fitur yang tersedia di source:

- Brat Generator
- Quote Maker
- Meme
- Fake Chat
- Fake Profile
- Fake Card
- To Comic
- To Chibi
- To Ghibli
- Remove Background
- Upscale / Enhance
- Watermark

Contoh di atas hanya sebagian dari fitur maker dan pengolahan media yang
tersedia di dalam source.

---

# 🔍 Stalker & Informasi

Luna-MD juga memiliki beberapa fitur pencarian dan pemeriksaan informasi,
antara lain:

```text
.igstalk
.ttstalk
.stalktelegram
.github
.playstore
.cuaca
.cekbio
.cekwa
```

---

# 💳 Pembayaran

Luna-MD menyediakan menu pembayaran dengan media khusus yang berada di:

```text
media/payment/
```

Di dalamnya terdapat aset untuk pembayaran seperti:

```text
dana.jpg
ovo.jpg
gopay.jpg
shoopepay.jpg
qris.jpg
```

Tampilan pembayaran dapat dibuat lebih interaktif dengan tombol salin
nomor pembayaran.

---

# 📋 Sistem Menu

Daftar menu Luna-MD dipisahkan ke dalam:

```text
listfitur.js
```

Beberapa kelompok menu utama:

```text
Owner
Jadibot
Payment
Pterodactyl
AI
Downloader
Sticker
Image
Maker
Tools
Group
JPM
Stalker
Search
Random
Store
Fun
Game
Quote
Utility
```

Dengan pemisahan ini, isi `Luna.js` tidak perlu menampung seluruh tampilan
menu secara langsung.

---

# 📊 Jumlah Fitur

Luna-MD juga memiliki command:

```text
.totalfitur
```

yang digunakan untuk membaca jumlah fitur aktif berdasarkan struktur
`case` pada `Luna.js`.

Selain itu, beberapa menu menggunakan penghitung fitur tersendiri sehingga
jumlah fitur pada kategori menu dapat ditampilkan secara otomatis.

---

# 🧩 Struktur Project

```text
Luna-MD/
│
├── Luna.js
├── index.js
├── settings.js
├── listfitur.js
│
├── source/
│   ├── message.js
│   ├── jadibot.js
│   ├── database.js
│   └── dbState.js
│
├── library/
│   ├── function.js
│   ├── scraper.js
│   ├── uploader.js
│   ├── exif.js
│   └── database/
│
├── media/
│   ├── Luna.jpg
│   ├── Luna.mp3
│   └── payment/
│
└── package.json
```

---

# ⚙️ Spesifikasi

| Bagian | Keterangan |
|:---|:---|
| Bahasa | JavaScript |
| Sistem Modul | CommonJS |
| Platform | WhatsApp Multi-Device |
| Library WhatsApp | noxleyss |
| Runtime | Node.js |
| Database | MongoDB / database lokal sesuai konfigurasi |
| Jadibot | Maksimal 20 sesi |
| Menu | Dipisahkan ke `listfitur.js` |
| Media | Gambar, audio, sticker, video, dokumen |
| Lisensi Source | MIT pada `package.json` |

---

# 🚀 Instalasi

Pastikan Node.js sudah terpasang, lalu jalankan:

```bash
git clone <URL-REPOSITORY-KAMU>
cd Luna-MD
npm install
npm start
```

Atau:

```bash
node index.js
```

Setelah bot berjalan, ikuti metode koneksi yang tersedia pada source.

---

# 🔧 Konfigurasi

Beberapa pengaturan utama berada di:

```text
settings.js
```

Di source saat ini terdapat pengaturan seperti:

```js
global.botname = 'Luna-MD'
global.maxJadibot = 20
global.pair = 'LUNAMDV1'
```

Sesuaikan konfigurasi tersebut dengan kebutuhan sebelum menjalankan bot.

---

# 🛡️ Perhatian

Jangan memasukkan data sensitif ke repository publik, terutama:

```text
session/
creds/
auth/
.env
```

API key, database credential, dan data autentikasi sebaiknya disimpan
secara aman dan tidak ikut diunggah ke GitHub.

---

# 🔓 Open Source

Luna-MD merupakan **script open source** yang dapat dipelajari,
dikembangkan, dan dimodifikasi sesuai kebutuhan.

Kamu bebas melakukan perubahan pada source selama tetap menghormati
**credits, pembuat awal, dan pihak yang berkontribusi pada project**.

> ## ⚠️ PERINGATAN KERAS — JANGAN HAPUS CREDITS
>
> **Dilarang menghapus, mengganti, menyembunyikan, atau mengklaim credits
> project ini sebagai karya pribadi.**
>
> Jika kamu melakukan recode, modifikasi, atau redistribusi source,
> **credits asli WAJIB tetap dicantumkan.**
>
> Mengubah nama bot, tampilan, struktur, atau menambahkan fitur baru
> **tidak berarti credits asli boleh dihapus.**
>
> **Open source bukan berarti bebas menghapus credits. Hormati pembuat
> dan contributor yang sudah mengembangkan source ini.**

---

# 📌 Catatan

Luna-MD dibuat untuk kebutuhan pengembangan, pembelajaran, otomasi, dan
eksperimen fitur WhatsApp.

Gunakan bot secara bertanggung jawab dan jangan melakukan spam atau
penyalahgunaan layanan.

---

<div align="center">

## 🌙 Luna-MD

### **Lebih dari sekadar bot.**

Dibangun untuk digunakan.  
Dikembangkan untuk terus bertambah.

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:0B1020,50:171A3A,100:6C4AB6&section=footer" width="100%">

</div>
