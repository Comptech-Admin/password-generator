# 🔐 Secure Client-Side Password Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Security: Client-Side](https://img.shields.io/badge/Security-Client--Side-success)](https://github.com/Comptech-Admin/password-generator)
[![Ambiguity: Zero](https://img.shields.io/badge/Ambiguity-Zero-blueviolet)](https://github.com/Comptech-Admin/password-generator)

> **A professional-grade password generator that strictly excludes ambiguous characters (I, l, 1, O, 0).** > Runs 100% in your browser. No data ever leaves your device.

[**🔴 Launch Generator**](https://comptech-admin.github.io/password-generator/)

---

## ⚡ Key Features

* **🚫 Zero Ambiguity:** We permanently removed `I`, `l`, `1`, `O`, and `0`. Passwords are easy to read and type manually.
* **🔒 100% Client-Side:** No server calls. No database. No API. It works offline.
* **🎲 True Randomness:** Uses the `window.crypto` API for cryptographically secure entropy (not `Math.random`).
* **🌗 Dark Mode:** Automatically detects your system preference.
* **📱 Responsive:** Works perfectly on desktop and mobile.

---

## 🛡️ Security Audit

We believe tools for IT professionals must be transparent. Here is why this generator is safe:

### 1. No "Phone Home"
The entire application is a single HTML file. There are no tracking scripts, no analytics, and no external API calls. You can verify this by inspecting the `Network` tab in your browser's developer tools.

### 2. Supply Chain Security
This project has **zero dependencies**. 
- No npm packages.
- No external CDNs (like jQuery or Bootstrap).
- No Google Fonts.
Everything is self-contained in `index.html`. This eliminates the risk of a third-party supply chain attack.

### 3. Memory Safety
Passwords are generated on-the-fly and are not stored in `localStorage` or `cookies`. Once you close the tab, the data is gone forever.

---

## 🚀 Quick Start

You can use the hosted version or run it locally.

### Option 1: Use the Web Version
Click here: [**https://Comptech-Admin.github.io/password-generator/**](https://comptech-admin.github.io/password-generator/)

### Option 2: Run Locally (Offline)
1.  Download the `index.html` file from this repository.
2.  Disconnect your internet (optional, for paranoia).
3.  Double-click `index.html` to open it in your browser.

---

## 🛠️ Customization

Want to change the default length? Open `index.html` and look for:

```html
<input type="range" id="lengthRange" min="6" max="64" value="16">
