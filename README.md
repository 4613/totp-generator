# 🔐 Offline TOTP Generator

A **lightweight, privacy-first** TOTP (Time-based One-Time Password) generator that runs **entirely in your browser** — no servers, no tracking, and no external requests. Ideal for generating 6-digit 2FA codes using a shared secret.

### ⚙️ Primary Use Case

This tool was built with **Hotmail/Microsoft account 2FA** compatibility in mind — it works seamlessly as a **third-party TOTP authenticator** for generating login verification codes when you scan or input your **Base32 shared secret key**.

---

## 🌟 Features

- ✅ **Works 100% Offline** — never sends or receives data externally
- 🔒 **Perfect for privacy-conscious users**
- ⏱️ **Smooth 30-second progress bar** for code rotation
- 🧠 **Auto-formatting Base32 input** as `XXXX XXXX XXXX XXXX`
- 🧪 **Input validation** and length limiting to match RFC standard
- 👁️‍🗨️ **Toggle visibility** of your secret key with an eye icon
- 💾 **Local storage support** to save and restore your secret
- 📋 **One-click copy** for the current 6-digit code
- 🎨 **Minimal, clean UI** with modern CSS (glassmorphism inspired)
- 📦 **Zero dependencies** – plain HTML, CSS & JavaScript

---

## 🚀 How to Use

1. Open the [webpage](https://4613.github.io/totp-generator/)
2. Paste your **Base32 TOTP secret key**
3. Instantly receive a valid 6-digit TOTP code
4. Use it to log in to your Hotmail or any TOTP-compatible service

---

## 🛡️ Privacy Statement

This tool:
- Does **not** transmit any data
- Stores your secret **locally in your browser**
- Is completely **open-source** and auditable

Your secrets stay with **you**. Forever.

---


## 🧠 What is TOTP?

**TOTP (Time-based One-Time Password)** is an algorithm used by most 2FA systems, including Google Authenticator, Microsoft Authenticator, and others. It generates a temporary 6-digit code based on a shared secret and the current time.

This project implements it **in pure JavaScript** using the Web Crypto API.

---

## 📄 License

MIT — free to use, modify, and share.

