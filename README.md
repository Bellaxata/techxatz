🚀 WBails

<p align="center">
  <img src="https://files.catbox.moe/8izozc.png" width="160">
</p><p align="center">
  <b>High Performance WhatsApp Library powered by Rust WASM</b><br>
  Enhanced Baileys fork with Anti-Ban, Meta AI, MEX GraphQL, Interop, and WA-Web Protocol support.
</p><p align="center">
  <img src="https://img.shields.io/npm/v/@bellaxchuu/wbails?style=for-the-badge">
  <img src="https://img.shields.io/npm/dt/@bellaxchuu/wbails?style=for-the-badge">
  <img src="https://img.shields.io/badge/Node.js-23+-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge">
</p>---

📦 Package Information

Property| Value
📦 Package| "@bellaxchuu/overBugs"
🏷️ Version| "0.1.8"
💬 Telegram| https://t.me/Xatanicvxii
⚡ Runtime| Node.js 23+
🦀 Engine| Rust WASM Bridge
🔗 Base| Baileys Fork

---

📚 Table of Contents

Getting Started

- Installation
- Running on Termux / Android
- Running on Pterodactyl

Authentication

- QR Code Login
- Pairing Code Login
- Full History Sync

Core Features

- Socket Configuration
- Session Management
- Event Handling
- Message Routing

Anti-Ban Suite

- RateLimiter
- WarmUp
- HealthMonitor
- TimelockGuard
- PresenceChoreographer
- wrapSocket

Messaging

- Text Messages
- Interactive Messages
- Media Messages
- Meta AI Messages
- Status & Stories

Advanced Features

- Group Management
- Privacy Controls
- User Queries
- Profile Management
- Chat Modifiers

Internal Protocols

- MEX GraphQL
- USync
- HTTPS GraphQL
- WA-Web Port

Utilities

- Sticker Maker
- View Once Cache
- Command Loader
- Multi Session Pool
- Store Encryption

Rust WASM Bridge

---

✨ What's Different?

🦀 Rust WASM Performance

Component| Upstream Baileys| WBails
Binary Decode| JavaScript| Rust WASM
Noise Handshake| JavaScript| Rust WASM
AES / HMAC / HKDF| Node Crypto| Rust WASM
Signal Protocol| libsignal-node| Rust WASM

Benefits

- ⚡ Faster packet processing
- ⚡ Reduced CPU usage
- ⚡ Better memory efficiency
- ⚡ Consistent performance across platforms
- ⚡ Works on Termux without Rust toolchain

---

🔥 Feature Highlights

Feature| Description
🤖 Meta AI| Full Meta AI integration and message handling
🔐 MEX GraphQL| Direct access to WhatsApp internal GraphQL APIs
🛡️ Anti-Ban Suite| Multiple protection layers for account safety
🌐 Interoperability| Facebook & Instagram messaging support
📦 Album Messages| Send multiple media in one message
🎨 Sticker Packs| Native sticker pack support
📢 Newsletters| Newsletter invite & follower messages
🏘️ Communities| Community and subgroup management
📞 Call Signalling| Advanced call event support
🌍 WA-Web Port| Mobile and Web protocol parity

---

📥 Installation

npm install npm:@bellaxchuu/wbails

Requirements

Node.js >= 23
npm >= 10

Optional Dependencies

Package| Purpose
sharp| Image processing
jimp| Fallback image processing
audio-decode| Voice metadata extraction
link-preview-js| Link preview generation

npm install sharp jimp audio-decode link-preview-js

---

🦀 Rust WASM Bridge

WBails uses whatsapp-rust-bridge compiled to WebAssembly (WASM).

Unlike native ".node" addons, WASM runs on:

- Android (Termux)
- Linux
- Windows
- macOS
- ARM Devices
- x86 Devices

No Rust compiler is required for normal installations.

The package ships with a prebuilt ".wasm" binary, allowing it to run immediately after installation.

---

🔬 MEX — WhatsApp Internal GraphQL

MEX powers many modern WhatsApp features:

- Privacy Settings
- Usernames
- Passkeys
- Profiles
- Integrity Checks
- Account Management

Example:

await sock.setPrivacySetting('LAST_SEEN', 'CONTACTS')

const user = await sock.findUserByUsername('@Xatanicvxii')

const abouts = await sock.getTextStatusList([
  '1@s.whatsapp.net'
])

📖 Full documentation: "documentation/MEX.md"

---

📖 Documentation

Topic| Documentation
MEX GraphQL| "documentation/MEX.md"
USync| "documentation/USYNC.md"
HTTPS GraphQL| "documentation/GRAPHQL.md"
Privacy & Profile| "documentation/PRIVACY.md"
Registration| "documentation/REGISTRATION.md"
Managed Accounts| "documentation/MANAGED-ACCOUNT.md"
Communities| "documentation/COMMUNITIES.md"
Interoperability| "documentation/INTEROP.md"
Username System| "documentation/USERNAME.md"
Anti-Ban| "documentation/ANTIBAN.md"
Ban System| "documentation/BAN-SYSTEM.md"
Protocol Reference| "documentation/PROTOCOLS.md"
WA-Web Port| "documentation/WA-WEB-PORT.md"

---

<p align="center">
  Made with ❤️ by BellaXxata
</p>