---
<p align="center">
  <img src="https://img.shields.io/badge/API-24%2B-yellow.svg?style=flat-square" alt="API">
  <img src="https://img.shields.io/badge/Kotlin-2.4.0-blue.svg?style=flat-square" alt="Kotlin">
  <img src="https://img.shields.io/github/commit-activity/m/2dust/v2rayNG?style=flat-square" alt="Commits">
  <img src="https://img.shields.io/github/downloads/2dust/v2rayNG/latest/total?logo=github&style=flat-square" alt="Downloads">
  <img src="https://img.shields.io/badge/Chat%20on-Telegram-brightgreen.svg?style=flat-square" alt="Telegram">
</p>

## THIS IS A FORKED REPOSITORY
---

# 🚀 v2rayNG | Hamed VPN | حـــامد VPN

**v2rayNG** is a feature-rich V2Ray client for **Android**, designed to provide secure and flexible network tunneling. It seamlessly supports both the [Xray core](https://github.com/XTLS/Xray-core) and the [v2fly core](https://github.com/v2fly/v2ray-core).

> [!IMPORTANT]
> This is the **Mobile** version.  
> Looking for the desktop client? Check out [**v2rayN**](https://github.com/2dust/v2rayN).

---

## 📥 Download

Get the latest stable release from GitHub:

### 👉 [Download v2rayNG Latest Release](https://github.com/2dust/v2rayNG/releases)

---

## 🌍 Geoip & Geosite Configuration

Managing routing rules is straightforward. Here’s how the data files work:

- **📍 File Location**  
  `geoip.dat` and `geosite.dat` are stored in:  
  `Android/data/com.v2ray.ang/files/assets`  
  *(Note: The exact path may differ slightly depending on your Android device.)*

- **⚡ Auto-Update Feature**  
  The built-in downloader fetches enhanced rule sets from the [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) repository.  
  > [!CAUTION]
  > This functionality requires an **active proxy connection** to work.

- **📂 Manual Import**  
  You can manually import the latest official datasets:
  - [Domain List (Geosite)](https://github.com/Loyalsoldier/v2ray-rules-dat)
  - [IP List (Geoip)](https://github.com/Loyalsoldier/geoip)

- **🔧 Third-party Support**  
  Feel free to use custom `.dat` files (e.g., [h2y](https://guide.v2fly.org/routing/sitedata.html#%E5%A4%96%E7%BD%AE%E7%9A%84%E5%9F%9F%E5%90%8D%E6%96%87%E4%BB%B6)) by placing them in the same directory.

> 📖 For more in-depth information, please visit our **[Official Wiki](https://github.com/2dust/v2rayNG/wiki)**.

---

## 🛠️ Development Guide

Interested in building or contributing? Follow these pointers:

### 📱 Building the Android App
The Android project resides in the `V2rayNG` folder. You can compile it directly using:
- **Android Studio** (recommended)
- **Gradle Wrapper** (command line)

> [!WARNING]
> The v2ray core bundled within the provided AAR file may be outdated. It is highly recommended to compile a fresh core.

### ⚙️ Compiling the Core (AAR)
To generate an updated AAR, you must compile from the GoLang projects:
- [AndroidLibV2rayLite](https://github.com/2dust/AndroidLibV2rayLite)
- [AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite)

**Quickstart Resources:**
- [Go Mobile Guide](https://github.com/golang/go/wiki/Mobile)
- [Makefiles for Go Developers](https://tutorialedge.net/golang/makefiles-for-go-developers/)

### 🖥️ Running on Emulators & WSA
- **Android Emulators**: v2rayNG runs without issues on standard Android emulators.
- **Windows Subsystem for Android (WSA)**: You must manually grant VPN permissions via ADB:
  ```bash
  appops set [your.package.name] ACTIVATE_VPN allow
  ```

---

## 🔐 GPG Verification

All release files are cryptographically signed with GPG to ensure **authenticity** and **integrity**. This protects against tampering by malicious mirrors, ISPs, or CDN providers.

**Public Key Fingerprint:**

```text
7694 5E9F 3E9A 168F 8070 F195 805D 661C
134D FAF6 8903 C199 463C 31E5 AE90 3AE0
```

---

## 💬 Community & Support

Stay connected, report issues, or chat with other users:

- **Telegram Group (Discussion & Help):**  
  [https://t.me/v2rayN](https://t.me/v2rayN)

- **Telegram Channel (Announcements & Updates):**  
  [https://t.me/github_2dust](https://t.me/github_2dust)

---

<p align="center">
  <sub>Made with ❤️ by the 2dust team</sub>
</p>

---

# Hamedvpns in Telegram
