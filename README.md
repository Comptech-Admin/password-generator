# ⚡ Omega | The IT Admin's Password Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Security: Client-Side](https://img.shields.io/badge/Security-Client--Side-success)](https://github.com/Comptech-Admin/password-generator)
[![Ambiguity: Zero](https://img.shields.io/badge/Ambiguity-Zero-blueviolet)](https://github.com/Comptech-Admin/password-generator)

> **A specialized password generator designed for IT Helpdesk workflows, System Admins, and bulk account provisioning.**

[**🚀 Launch Omega Tool**](https://comptech-admin.github.io/password-generator/)

---

## 🎯 Why this tool?

Most password generators are for *personal* use. **Omega** is built for **Admins who have to communicate passwords to others.**

* **📞 The Helpdesk Problem:** You generate a password and have to read it over the phone. *"Is that 'b' as in boy or 'd' as in dog?"*
* **✅ The Omega Solution:** We instantly translate every password into the **NATO Phonetic Alphabet** (Sierra-Tango-Nine...).

---

## 🛠️ Key Features

### 1. 🗣️ Automatic Phonetic Readout
Stop guessing. As soon as a password is generated, the tool provides the NATO phonetic spelling below it. Perfect for reading credentials over the phone or voice chat.

### 2. 📂 Session History & CSV Export
Creating 10 accounts at once?
* Omega keeps a local history of your last **50 generated passwords**.
* **One-Click Export:** Download your session as a `.csv` file to easily import into Excel or your documentation.

### 3. 🛡️ Smart Clipboard
Prevent accidental leaks.
* When you click "Copy", the tool grabs the password.
* **Auto-Wipe:** After **60 seconds**, the clipboard is automatically cleared (replaced with a blank space) to ensure you don't accidentally paste a password into a chat window later.

### 4. 🚫 Zero Ambiguity
We strictly exclude characters that cause confusion in sans-serif fonts:
* **Removed:** `I` (Capital i), `l` (Lowercase L), `1` (One), `O` (Capital o), `0` (Zero).

---

## 🔒 Security Architecture

This tool is designed to be safe for enterprise environments.

* **100% Client-Side:** No data is ever sent to a server. The logic runs entirely in your browser's JavaScript engine.
* **Cryptographically Secure:** Uses `window.crypto.getRandomValues()` for entropy, ensuring passwords cannot be predicted.
* **Ephemeral Memory:** Session history exists only in your browser tab's RAM. Refreshing the page wipes all data instantly.

---

## 🚀 Quick Start

### Online Usage
Access the tool securely via GitHub Pages:
[**https://Comptech-Admin.github.io/password-generator/**](https://comptech-admin.github.io/password-generator/)

### Offline Usage (Air-Gapped)
1.  Download the `index.html` file from this repository.
2.  Transfer it to your secure machine.
3.  Open in any modern browser (Chrome, Edge, Firefox).

---

## ⚙️ Customization

**Default Length:** 16 Characters
**Theme:** Automatically syncs with your OS (Dark/Light mode) with a manual toggle.

---

**Maintained by [Comptech-Admin](https://github.com/Comptech-Admin)**
