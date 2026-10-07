<div align="center">

# 🌙 Luna-MD

### **More Than Just A Bot.**

A modern WhatsApp Multi-Device bot built for automation, entertainment, utilities, and interactive experiences.

<br>

<img src="https://img.shields.io/badge/WhatsApp-Multi--Device-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-20%2B-339933?style=for-the-badge&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-ES2020-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111111" />

<br><br>

<img src="https://skillicons.dev/icons?i=nodejs,js,mongodb,git,github&theme=dark" />

</div>

---

## 🌙 What is Luna-MD?

**Luna-MD** is a feature-rich WhatsApp bot designed to combine everyday automation with a more interactive experience.

Instead of focusing on only one category, Luna-MD brings together:

- 🤖 AI & smart utilities
- 📥 Download & media tools
- 👥 Group management
- 🎮 Rich HTML games
- 🧩 Interactive responses
- 💳 Payment utilities
- 🛠️ Developer & owner tools
- 🔗 Jadibot / child-bot system
- 🧠 CRM / relay message utilities
- 🎨 Sticker, maker, and image tools

The project is structured so features can be maintained and expanded without turning the main command handler into an unnecessarily complicated system.

---

## ✦ Luna-MD at a Glance

| Area | What Luna-MD brings |
|:---|:---|
| 🤖 **AI** | AI chat, intelligent utilities, and automation tools |
| 📥 **Downloader** | Media downloading and conversion utilities |
| 👥 **Group** | Group administration, moderation, tagging, and protection |
| 🎮 **Games** | Interactive games, including Rich HTML experiences |
| 🎨 **Maker & Sticker** | Sticker, image, text, and creative utilities |
| 🛠️ **Tools** | Utility, converter, URL, media, and helper tools |
| 👑 **Owner** | Owner controls, evaluation, broadcast, backup, and bot management |
| 💳 **Payment** | Dana, OVO, GoPay, ShopeePay, QRIS, and payment display |
| 🔗 **Jadibot** | Child-bot / additional WhatsApp session management |
| 🧠 **CRM** | Create Relay Message and message/relay utilities |

---

# ✨ Why Luna-MD?

### 🎮 Rich HTML Game Experience

Luna-MD is not limited to text-based games.

The game collection includes interactive experiences such as:

`tebakbom` · `tebakangka` · `togel` · `ttt` · `stickman` · `mortal`

`memory-match` · `mahjong` · `puzzle` · `arrow` · `racing` · `angrybirds`

`flappy` · `snake-rimba` · `snake` · `geometry` · `tetris` · `sonic` · `chess`

The goal is to make the bot feel more like an interactive application rather than a collection of simple commands.

---

### 🔗 Jadibot / Child Bot

Run additional WhatsApp bot sessions through the Luna-MD system.

The system is designed around:

- Pairing-code based connection
- Child-bot session handling
- Session restoration
- Session cleanup
- Separate child-bot lifecycle
- Protection of the main bot session

> **Important:** child-bot handling should remain isolated from the primary bot session so an unused or cancelled pairing process does not unnecessarily affect the main connection.

---

### 🧠 CRM & Relay Message

Luna-MD also includes advanced message-oriented utilities inspired by the CRM workflow.

The system can be used for:

- Create Relay Message
- Message inspection
- Relay-oriented utilities
- Protocol/message handling
- Message structure generation
- Advanced WhatsApp message workflows

This part is intended for developers who want more control over how WhatsApp messages are processed and reconstructed.

---

### 💳 Payment System

Payment commands can display dedicated payment images and account information.

Supported payment categories include:

- 💙 Dana
- 🟣 OVO
- 🔵 GoPay
- 🟠 ShopeePay
- 📱 QRIS

The payment interface can also use an interactive **Copy Number** action so the payment number can be copied directly instead of manually typing it.

---

## 🧭 Command Architecture

Luna-MD keeps the command side organized around a central command handler while menu content is separated into `listfitur.js`.

Example concept:

```js
case 'menu':
    await menu(sock, m, smsg, store, args)
    break
```

This keeps `Luna.js` focused on command routing while menu presentation can be maintained independently.

---

## 📊 Smart Menu System

The menu system contains separate sections for different feature groups, including:

```text
Owner
Jadibot
Payment
AI
Downloader
Sticker
Image
Maker
Tools
Group
JPM
Stalk
Search
Random
NoKos
Store
Fun
Game
Quote
Utility
```

The project also supports an automatic feature-count concept so menu information can stay synchronized with the commands contained in each menu section.

---

## 🖼️ Interactive & Rich Response

Luna-MD is designed to support more than plain text responses.

Depending on the feature, the bot can work with:

- Interactive buttons
- Copy actions
- Media messages
- Images
- Stickers
- Rich HTML experiences
- Relay messages
- Quoted/replied messages
- Location-style menu presentation

This gives different parts of the bot their own presentation instead of forcing every feature into the same text-only format.

---

## 🧰 Main Toolkit

### 📥 Media & Downloader
- YouTube utilities
- TikTok utilities
- Pinterest utilities
- MediaFire utilities
- URL/media processing
- Media conversion

### 🎨 Creative Tools
- Sticker maker
- Image maker
- Text generators
- Brat-style generators
- Media enhancement utilities

### 👥 Group Tools
- Welcome / goodbye
- Anti-link
- Tagging
- Hidetag
- Admin utilities
- Group information
- Moderation helpers

### 👑 Owner Tools
- Evaluation
- Broadcast
- Bot controls
- Database utilities
- Session controls
- Developer utilities

### 🤖 AI & Utilities
- AI chat
- AI utilities
- Search tools
- Random utilities
- Converter tools
- General helper commands

---

# ⚙️ Requirements

| Requirement | Recommended |
|:---|:---|
| Node.js | **20+** |
| Runtime | Node.js |
| Connection | WhatsApp Multi-Device |
| Database | MongoDB where required by the configuration |
| OS | Linux / Windows / VPS |
| Package Manager | npm |

> Dependency requirements can vary with the version of the project and its installed packages.

---

# 🚀 Installation

```bash
git clone <YOUR-REPOSITORY-URL>
cd Luna-MD
npm install
node index.js
```

If your `package.json` contains a start script:

```bash
npm start
```

---

# 🛠️ Configuration

Before starting the bot, configure the project settings according to your own environment.

Typical configuration areas include:

```text
settings.js
source/
library/
media/
database/
```

Keep private credentials, session files, API keys, and database information out of a public repository.

---

# 📁 Project Layout

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
│   └── database.js
│
├── library/
│   ├── function.js
│   ├── scraper.js
│   ├── uploader.js
│   └── database/
│
├── media/
│   └── payment/
│
├── database/
│
├── package.json
└── README.md
```

---

# 🛡️ Stability First

Luna-MD is designed with a strong focus on keeping the bot usable during long-running sessions.

The project pays attention to:

- Connection recovery
- Child-session isolation
- Session cleanup
- Message serialization
- Avoiding unnecessary repeated work
- Memory-conscious feature handling
- Safe command routing

The goal is simple:

> **A bot should keep working instead of becoming heavier every time it receives a message.**

---

# 🔐 Security

Do **not** upload sensitive files to a public repository.

Recommended `.gitignore` entries:

```gitignore
node_modules/
*.log
.env
session/
sessions/
auth/
creds.json
```

Also avoid publishing:

- API keys
- Database credentials
- Private session credentials
- Personal phone numbers
- Private configuration files

---

# 📝 Developer Notes

Luna-MD is intended to remain easy to customize.

When adding a feature, prefer keeping:

```text
Command logic
      ↓
Command handler
      ↓
Utility/helper
      ↓
External service
```

separated where practical.

For menu-related changes, keep presentation inside:

```text
listfitur.js
```

instead of unnecessarily increasing the size of the main command handler.

---

# 📌 Disclaimer

Luna-MD is intended for **educational, development, and automation purposes**.

Use the bot responsibly and follow WhatsApp's rules and the terms of any third-party service used by the project.

The developer is not responsible for misuse, spam, account restrictions, or damage caused by modified versions of the source.

---

<div align="center">

### 🌙 Luna-MD

**More Than Just A Bot.**

Built to automate.  
Designed to interact.  
Made to be expanded.

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:0B1020,50:1B1B3A,100:5B3FA8&section=footer" width="100%" />

</div>
