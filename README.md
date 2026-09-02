🌟 Hamed VPN | VPN حـــامد

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-brightgreen.svg?style=flat-square&logo=github" alt="Version">
  <img src="https://img.shields.io/badge/Build-Stable-success.svg?style=flat-square&logo=github" alt="Stable Build">
  <img src="https://img.shields.io/badge/API-24%2B-yellow.svg?style=flat-square&logo=android" alt="API">
  <img src="https://img.shields.io/badge/Kotlin-2.4.0-blue.svg?style=flat-square&logo=kotlin" alt="Kotlin">
  <img src="https://img.shields.io/badge/Platform-Android-brightgreen.svg?style=flat-square&logo=android" alt="Platform">
  <img src="https://img.shields.io/badge/License-GPLv3-blue.svg?style=flat-square&logo=gnu" alt="License">
  <img src="https://img.shields.io/badge/Telegram-Channel-blue?style=flat-square&logo=telegram" alt="Telegram">
  <img src="https://img.shields.io/badge/Powered%20By-V2RayNG-orange?style=flat-square&logo=v2ray" alt="V2RayNG">
</p>

---

🌐 Language Selection | انتخاب زبان
**[🇬🇧 English](https://github.com/hamedp-71/hamedvpn/blob/main/ReadmeFa.md)**
**[ 🇮🇷 فارسی](https://github.com/hamedp-71/hamedvpn/blob/main/ReadmeFa.md)**


</details>

---

🇬🇧 English

🚀 Welcome to Hamed VPN

Hamed VPN is a powerful and intelligent Android VPN client based on V2RayNG, designed specifically for users in countries with restricted internet access, such as Iran. It provides seamless, secure, and automated connectivity to the free internet using advanced proxy technologies.

---

✨ Key Features

Feature Description
🤖 Smart Auto-Connect Automatically fetches, tests, and connects to the best available configuration for optimal performance and stability.
⚡ One-Tap Connect Simply tap the cloud-shaped download button on the main screen to initiate the intelligent connection process.
🔐 Advanced Security Built on the robust V2Ray/Xray cores with support for VMess, VLESS, Trojan, and Shadowsocks protocols.
🌍 Optimized for Iran Specifically fine-tuned to bypass deep packet inspection (DPI) and network restrictions in the region.
🧠 Smart Core The intelligent core extracts and tests multiple configurations, automatically switching to the fastest and most reliable connection.
📱 User-Friendly Interface Clean, modern, and intuitive design for both beginners and advanced users.
🔄 Auto-Update Built-in updater for geoip.dat and geosite.dat from trusted sources to ensure accurate routing.
🛡️ Privacy First No logs, no tracking, and full encryption to protect your digital footprint.
📶 Seamless Switching Automatically switches between configurations if the current connection drops or becomes unstable.
🏎️ High Performance Optimized for speed and low latency, ensuring a smooth browsing experience.
🔒 GPG Verified All releases are cryptographically signed to guarantee authenticity and integrity.

---

📥 Download & Installation

🔽 Download Latest Version

Get the Hamed VPN v1.0.0 Stable release from our official GitHub repository:

<p align="center">
  <a href="https://github.com/hamedp-71/HamedVPN/releases/tag/v1.0.0">
    <img src="https://img.shields.io/badge/Download-Hamed%20VPN%20v1.0.0-blue?style=for-the-badge&logo=github" alt="Download Hamed VPN">
  </a>
</p>

📱 Installation Guide

1. Download the latest APK from the link above.
2. Enable "Install from Unknown Sources" in your device settings.
3. Install the APK on your Android device (API 24+).
4. Open the app and grant necessary permissions (VPN and notifications).
5. Tap the ☁️ cloud-shaped download button to start the smart auto-connect process.
6. Wait for the intelligent core to fetch, test, and connect to the best configuration.
7. Enjoy unrestricted, fast, and secure internet access!

---

🧠 How the Smart Auto-Connect Works

The intelligent core of Hamed VPN revolutionizes the way you connect to the internet:

```mermaid
graph TD
    A[User taps ☁️ Download Button] --> B[Smart Core fetches configurations]
    B --> C[Tests each configuration for speed and stability]
    C --> D[Selects the best-performing configuration]
    D --> E[Establishes secure VPN connection]
    E --> F[Display connected status with server info]
    F --> G[Monitors connection health]
    G --> H{Connection stable?}
    H -->|Yes| I[Maintain connection]
    H -->|No| B[Auto-switch to next best config]
```

🎯 Why It's Revolutionary

· No Manual Setup: You don't need to enter server addresses, ports, or UUIDs manually.
· Intelligent Testing: The core automatically ping-tests multiple configurations and selects the one with the lowest latency and highest throughput.
· Self-Healing: If the current connection fails, the system automatically switches to a backup configuration without interruption.
· Optimized for Iran: The configurations are specifically tailored to bypass Iranian network restrictions effectively.

---

🌍 Geoip & Geosite Configuration

📍 File Location

geoip.dat and geosite.dat are stored in:

```
Android/data/com.v2ray.ang/files/assets
```

⚡ Auto-Update Feature

The built-in downloader fetches enhanced rule sets from trusted repositories:

· Loyalsoldier/v2ray-rules-dat

[!CAUTION]
Auto-update requires an active proxy connection.

📂 Manual Import

You can manually import the latest official datasets:

· Domain List (Geosite)
· IP List (Geoip)

🔧 Third-party Support

Custom .dat files can be placed in the same directory for specialized routing rules.

---

🛠️ Development Guide

📱 Building the Android App

The Android project can be built using:

· Android Studio (Recommended)
· Gradle Wrapper (Command Line)

[!WARNING]
The bundled v2ray core in the AAR may be outdated. It's recommended to compile a fresh core.

⚙️ Compiling the Core (AAR)

To generate an updated AAR, compile from these GoLang projects:

· AndroidLibV2rayLite
· AndroidLibXrayLite

Quickstart Resources:

· Go Mobile Guide
· Makefiles for Go Developers

🖥️ Running on Emulators & WSA

· Android Emulators: Works perfectly on all standard Android emulators.
· Windows Subsystem for Android (WSA):
  Grant VPN permissions via ADB:
  ```bash
  appops set [your.package.name] ACTIVATE_VPN allow
  ```

---

🔐 GPG Verification

All release files are cryptographically signed to ensure authenticity and integrity.

Public Key Fingerprint:

```
7694 5E9F 3E9A 168F 8070 F195 805D 661C
134D FAF6 8903 C199 463C 31E5 AE90 3AE0
```

---

💬 Community & Support

Platform Link
📱 Telegram Group t.me/v2rayN
📢 Telegram Channel t.me/github_2dust
🐛 Issue Tracker GitHub Issues
📖 Official Wiki GitHub Wiki

---

🤝 Contributing

Contributions are always welcome! Here's how you can help:

1. 🍴 Fork the repository
2. 🌿 Create a new branch (git checkout -b feature/amazing-feature)
3. ✍️ Commit your changes (git commit -m 'Add amazing feature')
4. 📤 Push to the branch (git push origin feature/amazing-feature)
5. 🎉 Open a Pull Request

---

📜 License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

---

🙏 Acknowledgments

· V2RayNG - The foundation of this project
· V2Fly - Core proxy technology
· Xray - Enhanced core capabilities
· Loyalsoldier - Geoip and Geosite datasets
· All Contributors - For their invaluable contributions

---

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-❤️-red.svg?style=for-the-badge" alt="Made with love">
  <br>
  <sub>© 2026 Hamed VPN Team. All rights reserved.</sub>
  <br>
  <sub>💡 Freedom of information is a fundamental human right.</sub>
</p>

---

🇮🇷 فارسی

🚀 به Hamed VPN خوش آمدید

VPN حامد یک کلاینت قدرتمند و هوشمند اندرویدی بر پایه V2RayNG است که مخصوص کاربران کشورهایی با اینترنت محدود شده مانند ایران طراحی شده است. این برنامه با استفاده از فناوری‌های پیشرفته پراکسی، اتصال امن، پایدار و خودکار به اینترنت آزاد را فراهم می‌کند.

---

✨ ویژگی‌های کلیدی

ویژگی توضیحات
🤖 اتصال هوشمند خودکار به‌طور خودکار بهترین کانفیگ را استخراج، تست و متصل می‌شود.
⚡ اتصال با یک لمس با لمس دکمه دانلود ابری شکل در صفحه اصلی، فرآیند اتصال هوشمند آغاز می‌شود.
🔐 امنیت پیشرفته مبتنی بر هسته‌های قدرتمند V2Ray/Xray با پشتیبانی از پروتکل‌های VMess، VLESS، Trojan و Shadowsocks.
🌍 بهینه‌سازی برای ایران به‌طور ویژه برای دور زدن DPI و محدودیت‌های شبکه در ایران تنظیم شده است.
🧠 هسته هوشمند هسته هوشمند برنامه، کانفیگ‌های متعدد را استخراج و تست کرده و به بهترین و پایدارترین آنها متصل می‌شود.
📱 رابط کاربری زیبا طراحی مدرن، تمیز و کاربرپسند برای کاربران مبتدی و حرفه‌ای.
🔄 بروزرسانی خودکار بروزرسانی خودکار فایل‌های geoip.dat و geosite.dat از منابع معتبر.
🛡️ حریم خصوصی بدون لاگ، بدون ردیابی و با رمزنگاری کامل برای محافظت از حریم دیجیتال شما.
📶 سوئیچینگ هوشمند در صورت قطع یا ناپایداری اتصال، به‌طور خودکار به کانفیگ پشتیبان سوئیچ می‌کند.
🏎️ عملکرد بالا بهینه‌سازی شده برای سرعت و تأخیر پایین، تجربه مرور روان.
🔒 تأیید GPG تمامی فایل‌های انتشار با امضای GPG برای تضمین اصالت و یکپارچگی.

---

📥 دانلود و نصب

🔽 دانلود آخرین نسخه

نسخه پایدار Hamed VPN v1.0.0 را از مخزن رسمی گیت‌هاب دریافت کنید:

<p align="center">
  <a href="https://github.com/hamedp-71/HamedVPN/releases/tag/v1.0.0">
    <img src="https://img.shields.io/badge/دانلود-Hamed%20VPN%20v1.0.0-blue?style=for-the-badge&logo=github" alt="دانلود Hamed VPN">
  </a>
</p>

📱 راهنمای نصب

1. دانلود آخرین نسخه APK از لینک بالا.
2. فعال‌سازی نصب از منابع ناشناخته در تنظیمات دستگاه.
3. نصب فایل APK روی دستگاه اندروید (API 24+).
4. باز کردن برنامه و اعطای مجوزهای لازم (VPN و اعلانات).
5. لمس دکمه ☁️ ابر شکل دانلود برای شروع فرآیند اتصال خودکار هوشمند.
6. صبر تا هسته هوشمند کانفیگ‌ها را استخراج، تست و به بهترین آنها متصل شود.
7. لذت ببرید از اینترنت آزاد، سریع و امن!

---

🧠 عملکرد اتصال خودکار هوشمند

هسته هوشمند VPN حامد نحوه اتصال شما به اینترنت را متحول کرده است:

```mermaid
graph TD
    A[کاربر دکمه ☁️ دانلود را لمس می‌کند] --> B[هسته هوشمند کانفیگ‌ها را استخراج می‌کند]
    B --> C[هر کانفیگ را از نظر سرعت و پایداری تست می‌کند]
    C --> D[بهترین کانفیگ را انتخاب می‌کند]
    D --> E[اتصال VPN امن برقرار می‌کند]
    E --> F[وضعیت اتصال با اطلاعات سرور نمایش داده می‌شود]
    F --> G[وضعیت اتصال را پایش می‌کند]
    G --> H{اتصال پایدار است؟}
    H -->|بله| I[اتصال حفظ می‌شود]
    H -->|خیر| B[به کانفیگ بعدی سوئیچ می‌کند]
```

🎯 چرا این رویکرد انقلابی است؟

· بدون تنظیمات دستی: نیازی به وارد کردن آدرس سرور، پورت یا UUID نیست.
· تست هوشمند: هسته به‌طور خودکار چندین کانفیگ را پینگ تست کرده و کم‌ترین تأخیر و بیشترین پهنای باند را انتخاب می‌کند.
· خودترمیمی: در صورت قطع اتصال، سیستم به‌طور خودکار و بدون وقفه به کانفیگ پشتیبان سوئیچ می‌کند.
· بهینه‌سازی برای ایران: کانفیگ‌ها به‌طور ویژه برای دور زدن محدودیت‌های شبکه ایران تنظیم شده‌اند.

---

🌍 تنظیمات Geoip و Geosite

📍 محل فایل‌ها

geoip.dat و geosite.dat در مسیر زیر ذخیره می‌شوند:

```
Android/data/com.v2ray.ang/files/assets
```

⚡ ویژگی بروزرسانی خودکار

دانلودر داخلی، مجموعه قوانین به‌روز را از مخازن معتبر دریافت می‌کند:

· Loyalsoldier/v2ray-rules-dat

[!CAUTION]
بروزرسانی خودکار نیاز به اتصال پراکسی فعال دارد.

📂 ورود دستی

می‌توانید آخرین مجموعه‌های رسمی را به‌صورت دستی وارد کنید:

· لیست دامنه (Geosite)
· لیست IP (Geoip)

🔧 پشتیبانی از شخصی‌سازی

فایل‌های .dat سفارشی را می‌توانید در همان مسیر قرار دهید.

---

🛠️ راهنمای توسعه

📱 ساخت برنامه اندروید

پروژه اندروید با استفاده از:

· Android Studio (توصیه‌شده)
· Gradle Wrapper (خط فرمان)

[!WARNING]
هسته v2ray درون فایل AAR ممکن است قدیمی باشد. توصیه می‌شود هسته جدیدی کامپایل کنید.

⚙️ کامپایل هسته (AAR)

برای تولید AAR به‌روز، از پروژه‌های GoLang زیر کامپایل کنید:

· AndroidLibV2rayLite
· AndroidLibXrayLite

منابع سریع:

· راهنمای Go Mobile
· Makefiles برای توسعه‌دهندگان Go

🖥️ اجرا روی شبیه‌سازها و WSA

· شبیه‌سازهای اندروید: بدون مشکل روی تمام شبیه‌سازهای استاندارد اندروید کار می‌کند.
· Windows Subsystem for Android (WSA):
  مجوز VPN را از طریق ADB اعطا کنید:
  ```bash
  appops set [your.package.name] ACTIVATE_VPN allow
  ```

---

🔐 تأیید GPG

تمامی فایل‌های انتشار با امضای GPG برای تضمین اصالت و یکپارچگی امضا شده‌اند.

اثر انگشت کلید عمومی:

```
7694 5E9F 3E9A 168F 8070 F195 805D 661C
134D FAF6 8903 C199 463C 31E5 AE90 3AE0
```

---

💬 جامعه و پشتیبانی

پلتفرم لینک
📱 گروه تلگرام t.me/v2rayN
📢 کانال تلگرام t.me/github_2dust
🐛 پیگیری مشکلات مسائل گیت‌هاب
📖 ویکی رسمی ویکی گیت‌هاب

---

🤝 مشارکت

همیشه از مشارکت شما استقبال می‌کنیم! راه‌های کمک:

1. 🍴 فورک مخزن
2. 🌿 ایجاد شاخه جدید (git checkout -b feature/amazing-feature)
3. ✍️ ثبت تغییرات (git commit -m 'Add amazing feature')
4. 📤 پوش به شاخه (git push origin feature/amazing-feature)
5. 🎉 باز کردن درخواست Pull

---

📜 مجوز

این پروژه تحت مجوز GNU General Public License v3.0 منتشر شده است - برای جزئیات به فایل LICENSE مراجعه کنید.

---

🙏 قدردانی

· V2RayNG - شالوده این پروژه
· V2Fly - فناوری اصلی پراکسی
· Xray - قابلیت‌های هسته پیشرفته
· Loyalsoldier - مجموعه‌های Geoip و Geosite
· تمامی مشارکت‌کنندگان - برای مشارکت‌های ارزشمندشان

---

<p align="center">
  <img src="https://img.shields.io/badge/ساخته%20شده%20با-❤️-red.svg?style=for-the-badge" alt="ساخته شده با عشق">
  <br>
  <sub>© 2026 تیم VPN حامد. تمامی حقوق محفوظ است.</sub>
  <br>
  <sub>💡 آزادی اطلاعات یک حق اساسی بشر است.</sub>
</p>
