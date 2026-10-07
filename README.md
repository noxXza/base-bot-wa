# 🌙 Luna-MD

> **More Than Just A Bot.**

::: {align="center"}
`<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0A0A0F,50:111118,100:00A2FF&text=Luna-MD&fontColor=FFFFFF&fontSize=58&fontAlignY=38&desc=More%20Than%20Just%20A%20Bot&descAlignY=60&descSize=20&animation=fadeIn" width="100%">`{=html}
:::

```{=html}
<p align="center">
```
`<img src="https://img.shields.io/badge/Node.js-18%2B-00A2FF?style=for-the-badge&logo=node.js&logoColor=white">`{=html}
`<img src="https://img.shields.io/badge/JavaScript-ES2020%2B-00A2FF?style=for-the-badge&logo=javascript&logoColor=white">`{=html}
`<img src="https://img.shields.io/badge/WhatsApp-Multi--Device-00A2FF?style=for-the-badge&logo=whatsapp&logoColor=white">`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<img src="https://skillicons.dev/icons?i=nodejs,js,mongodb,git,github&theme=dark" alt="Tech Stack">`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## ✨ Tentang Luna-MD

**Luna-MD** adalah source code WhatsApp bot berbasis **Node.js** yang
menggabungkan command bot, utility, downloader, AI, game, group
management, payment, tools developer, dan fitur interaktif dalam satu
project.

Konsep utama:

> **More Than Just A Bot.**

Luna-MD tidak hanya mengandalkan pesan teks. Project ini juga memiliki
**Rich HTML / interactive response**, game, jadibot, pairing code, menu
dinamis, dan berbagai utility.

------------------------------------------------------------------------

## 🖼️ Preview

::: {align="center"}
`<img src="https://capsule-render.vercel.app/api?type=rounded&height=180&color=0:111118,100:0A0A0F&text=LUNA%20CALCULATOR&fontColor=00A2FF&fontSize=36&desc=Rich%20HTML%20Interactive%20Experience&descColor=FFFFFF&descSize=16" width="90%">`{=html}
:::

> Untuk screenshot asli, tambahkan file seperti `assets/menu.jpg`,
> `assets/gamemenu.jpg`, dan `assets/rich-html.jpg`, lalu gunakan:
>
> ``` md
> <img src="./assets/menu.jpg" width="300">
> ```

------------------------------------------------------------------------

# 🚀 Fitur Unggulan

## 🎮 Rich HTML Game

Dilengkapi berbagai game, termasuk:

-   💣 Tebak Bom
-   🔢 Tebak Angka
-   🎰 Togel
-   ❌⭕ Tic Tac Toe
-   🕹️ Stickman
-   ⚔️ Mortal
-   🧠 Memory Match
-   🀄 Mahjong
-   🧩 Puzzle
-   🏹 Arrow
-   🏎️ Racing
-   🐦 Angry Birds
-   🐤 Flappy
-   🐍 Snake
-   🌲 Snake Rimba
-   📐 Geometry
-   🧱 Tetris
-   🦔 Sonic
-   ♟️ Chess

Beberapa game menggunakan konsep **Rich HTML / interactive experience**,
sehingga pengalaman pengguna lebih interaktif daripada command teks
biasa.

## 🌐 Rich HTML & Interactive Response

Mendukung konsep:

-   🧮 HTML Calculator
-   🎮 HTML Game
-   🖥️ Custom UI
-   🎨 HTML/CSS
-   ⚡ JavaScript interaction
-   📱 Mobile-friendly layout

## 🤖 Jadibot / Multi-Bot

-   🔗 Pairing Code
-   📱 Connect menggunakan nomor WhatsApp
-   👥 Multiple child bot
-   🔄 Reconnect handling
-   🧹 Session cleanup
-   🛡️ Perlindungan session bot utama
-   ❌ Cancel / stop jadibot

## 👑 Owner & Bot Control

Contoh command:

``` text
.self
.public
.menu
.allmenu
.owner
.listowner
```

Mode `PUBLIC` memungkinkan command digunakan sesuai permission yang
tersedia, sedangkan `SELF` membatasi penggunaan bot untuk owner.

## 📋 Smart Menu System

Menu dipisahkan melalui `listfitur.js`, dengan kategori seperti:

-   👑 Owner
-   🤖 Jadibot
-   💳 Payment
-   🖥️ Pterodactyl
-   🤖 AI
-   📥 Download
-   🧷 Sticker
-   🖼️ Image
-   🛠️ Maker
-   🔧 Tools
-   👥 Group
-   📢 JPM
-   🔎 Stalk
-   🔍 Search
-   🎲 Random
-   🎮 Game
-   🎉 Fun
-   🏪 Store
-   🧰 Utility

### 🔢 Automatic Feature Counter

Jumlah fitur dapat dihitung otomatis:

``` js
description: `total ${getFeatureCount("gamemenu")} fitur🎮`
```

Menambah item ke menu dapat membuat jumlah fitur ikut berubah tanpa
mengedit angka secara manual.

## 💳 Payment System

-   💰 DANA
-   🟣 OVO
-   🔵 GoPay
-   🛍️ ShopeePay
-   📱 QRIS
-   🖼️ Payment image
-   📋 Copy-number button
-   ⚙️ Global configuration

## 🧰 Downloader & Media Tools

Kategori media dan utility mencakup downloader, Pinterest, MediaFire,
image processing, sticker converter, uploader, dan berbagai tool media
lainnya.

## 👥 Group Tools

-   👑 Promote / demote
-   🚪 Kick
-   🔗 Group link
-   📝 Group settings
-   🛡️ Anti-link
-   👋 Welcome
-   📢 Mention tools
-   👥 Admin tools

## 🧠 AI Tools

Tersedia kategori AI yang terpisah agar command lebih mudah digunakan
dan dikembangkan.

------------------------------------------------------------------------

# ⚙️ Spesifikasi

  Komponen         Detail
  ---------------- ---------------------------------
  Runtime          Node.js
  Bahasa           JavaScript
  Platform         WhatsApp Multi-Device
  Architecture     Event-driven
  Database         MongoDB + local data
  Menu             Dynamic feature list
  Game             Text + Rich HTML
  UI               HTML / CSS / JavaScript
  Authentication   QR / Pairing Code
  Bot System       Main Bot + Jadibot
  Media            Image / Video / Audio / Sticker
  Configuration    `settings.js`

Luna-MD menggunakan pendekatan socket-based untuk koneksi WhatsApp.
Baileys sendiri mendokumentasikan koneksi ke WhatsApp Web melalui
WebSocket tanpa Selenium/Chromium.

------------------------------------------------------------------------

# 📦 Installation

### 1. Clone repository

``` bash
git clone https://github.com/USERNAME/Luna-MD.git
cd Luna-MD
```

### 2. Install dependency

``` bash
npm install
```

### 3. Configure

Buka:

``` text
settings.js
```

Sesuaikan konfigurasi seperti owner, nama bot, prefix, dan konfigurasi
lain yang tersedia.

### 4. Start

``` bash
node index.js
```

Jika `package.json` memiliki script `start`:

``` bash
npm start
```

------------------------------------------------------------------------

# 🔐 Security

Jangan upload credential/session ke repository public.

Tambahkan ke `.gitignore`:

``` gitignore
node_modules/
session/
sessions/
auth/
creds.json
*.log
.env
```

------------------------------------------------------------------------

# 📁 Struktur Project

``` text
Luna-MD/
│
├── index.js
├── Luna.js
├── settings.js
├── listfitur.js
├── package.json
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
│   ├── converter.js
│   ├── exif.js
│   └── database/
│
├── media/
│   ├── payment/
│   └── ...
│
└── README.md
```

------------------------------------------------------------------------

# 🛡️ Stability Focus

Luna-MD dikembangkan dengan perhatian pada:

-   ⚡ Response time
-   🧠 Memory usage
-   🔄 Reconnection
-   🛡️ Session safety
-   🧹 Session cleanup
-   🧩 Feature organization
-   🚫 Mengurangi proses blocking yang tidak diperlukan

> Performa tetap bergantung pada VPS/device, koneksi internet, jumlah
> session, dependency, dan beban command.

------------------------------------------------------------------------

# ⚠️ Disclaimer

Luna-MD dibuat untuk pembelajaran, eksperimen, automation pribadi, dan
pengembangan bot.

Jangan gunakan untuk spam, phishing, penipuan, penyalahgunaan akun,
pengiriman massal yang mengganggu, atau aktivitas yang melanggar aturan
WhatsApp.

Baileys adalah library tidak resmi dan tidak berafiliasi dengan
WhatsApp. Gunakan secara bertanggung jawab.

------------------------------------------------------------------------

# 💙 Credits

### Luna-MD

**More Than Just A Bot.**

Terima kasih kepada komunitas open-source dan para developer yang
membuat ekosistem WhatsApp automation dan Node.js terus berkembang.

::: {align="center"}
`<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:00A2FF,50:111118,100:0A0A0F" width="100%">`{=html}
:::
