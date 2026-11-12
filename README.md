# Potluck Android

> Peer-to-peer screen time pact for Android. Share daily app budgets, lock distracting apps, and stay accountable together without accounts or central servers.

Official distribution repository for **Potluck** Android APK releases. This repository contains only binary release artifacts and release documentation (no application source code).

---

## 📥 Download Latest Release

Get the latest signed APK directly from GitHub Releases:

- **[Download Latest APK (v1.0.6)](https://github.com/Imagiyy/Potluck-Android/releases/latest/download/app-release.apk)**
- **[All Releases & Changelog](https://github.com/Imagiyy/Potluck-Android/releases)**

---

## 🚀 Installation & Setup

1. **Download the APK** on your Android device (Android 8.0+ / Oreo or newer).
2. Tap the downloaded `.apk` file to install.
   - *If prompted, enable **Install unknown apps** for your browser or file manager.*
3. Open **Potluck** and grant required permissions:
   - **Usage Access**: To track screen time against your shared pact pool.
   - **Accessibility Service**: To actively enforce app locks when your budget expires or focus mode is active.
   - **Overlay (Display over other apps)**: To present the lock screen.
   - **Battery Optimization Exemption**: To allow peer-to-peer background sync over Iroh / QUIC without the OS killing the background transport.
4. **Create or Join a Pact**:
   - Create a new pact and share the invite QR code / string with friends.
   - Or join an existing pact via an invite from your friend.

---

## ✨ Key Features

- **P2P Direct Sync**: Operates entirely over direct peer-to-peer connections with end-to-end cryptographic signatures and local state verification. No central databases, tracking, or cloud accounts.
- **Shared Daily Pot**: Group members share an accountability pool of minutes for monitored apps.
- **Real-Time App Monitoring**: View breakdowns of member usage per monitored app.
- **In-Pact Chat & Feed**: Chat with pact members, monitor session logs, and keep each other motivated.
- **Strict Accountability**: Tamper-resistant enforcement designed to help you stay present and focused.

---

## 🔒 Privacy & Security

- **Zero Cloud Storage**: All pact events and messages are stored locally and exchanged peer-to-peer.
- **Cryptographic Envelopes**: Every event and state change is signed with your device's private key.
- **No Analytics / Telemetry**: No tracking SDKs or external advertising frameworks.

---

## 👤 Author

Developed by **[Imagiyy](https://github.com/Imagiyy)**.
