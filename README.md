# ClipFlow

**Your personal, secure clipboard between Android and PC.**

Instant text synchronization. No third-party servers. 100% control over your data thanks to Zero-Knowledge architecture.

---

## ✨ What is ClipFlow?

ClipFlow is a cross-platform clipboard sync tool that lets you copy text on your Android device and instantly paste it on your Mac, Windows, or Linux PC — and vice versa.

Unlike other clipboard tools, ClipFlow **never stores your data on any third-party server**. All synchronization happens through your own personal Firebase account, and all data is encrypted locally on your device before it ever leaves.

---

## 🔐 Security

- **Zero-Knowledge Architecture** — your data is encrypted locally using **AES-256-GCM + scrypt** before sync
- **Your own Firebase** — sync goes through your personal Google Firebase account (free Spark plan is more than enough)
- **Password never leaves your device** — the encryption key is derived locally from your password and is never transmitted over the network
- Even the developer has **zero access** to your data

---

## 📦 Downloads

| Platform | File |
|----------|------|
| 🍎 macOS (Apple Silicon M1/M2/M3) | `ClipFlow-arm64.dmg` |
| 🍎 macOS (Intel x64) | `ClipFlow-x64.dmg` |
| 🪟 Windows (x64) | `ClipFlow-Setup-x64.exe` |
| 🪟 Windows (ARM64) | `ClipFlow-Setup-arm64.exe` |
| 🐧 Ubuntu / Linux (x64 DEB) | `ClipFlow-amd64.deb` |
| 🤖 Android (APK) | `app-release.apk` |

---

## 🚀 Quick Start

1. Go to [Firebase Console](https://console.firebase.google.com) and create a free project
2. Add an Android app with package name `com.clipflow.android` and download `google-services.json`
3. Open ClipFlow on each device, import `google-services.json`
4. Set the **same** encryption password on all devices
5. Press **Background Sync Start** — done!

> Full setup guide: [webclipflow.vercel.app/en/guide](https://webclipflow.vercel.app/en/guide)

---

## 🗺️ Roadmap

- ✅ **Stage 1** — Cross-platform clipboard sync with E2EE (completed)
- 🔄 **Stage 2** — Beta testing, bug fixes, stability improvements (current)
- 🔜 **Stage 3** — Encrypted file transfer between devices (Pro feature, planned)
- 🔜 **Stage 4** — Performance optimization and new platform support (planned)

---

## 🔗 Links

- 🌐 Website: [webclipflow.vercel.app](https://webclipflow.vercel.app/en)
- 📖 Guide: [webclipflow.vercel.app/en/guide](https://webclipflow.vercel.app/en/guide)
- 🔒 Privacy Policy: [webclipflow.vercel.app/en/privacy-policy](https://webclipflow.vercel.app/en/privacy-policy)

---

© 2026 Andrii Sobcheniuk. All rights reserved.
