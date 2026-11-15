# Potluck Android 🍲🔒

> Peer-to-peer screen time pact for Android. Share daily app budgets, lock distracting apps, and stay accountable together without accounts or central servers.

[![Platform](https://img.shields.io/badge/Platform-Android%208.0+-3DDC84.svg?style=flat&logo=android)](https://www.android.com/)
[![Release](https://img.shields.io/github/v/release/Imagiyy/Potluck-Android)](https://github.com/Imagiyy/Potluck-Android/releases)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

Official distribution repository for **Potluck** Android APK releases. This repository contains only binary release artifacts and release documentation (no application source code).

---

## 📥 Download Latest Release

Get the latest signed APK directly from GitHub Releases:

- 🚀 **[Download Latest APK (v1.2.0)](https://github.com/Imagiyy/Potluck-Android/releases/latest/download/Potluck-v1.2.0.apk)**
- 📋 **[All Releases & Full Changelog](https://github.com/Imagiyy/Potluck-Android/releases)**

---

## 🚀 Installation & Setup

1. **Download the APK** on your Android device (Android 8.0+ / Oreo or newer).
2. Tap the downloaded  file to install.
   - *If prompted, enable **Install unknown apps** for your browser or file manager.*
3. Open **Potluck** and grant required permissions:
   - **Usage Access**: To track screen time against your shared pact pool accurately.
   - **Overlay (Display over other apps)**: To present the lock screen when your pact limit is reached.
   - **Battery Optimization Exemption**: To allow peer-to-peer background sync over Iroh / QUIC without the OS killing the background transport.
   - *(Note: Accessibility Service is **no longer required** as of v1.2.0, ensuring full compatibility with UPI & banking applications).*
4. **Create or Join a Pact**:
   - Create a new pact and share the invite QR code / string with friends.
   - Or join an existing pact via an invite from your friend.

---

## 🌟 What's New in v1.2.0

- 🛡️ **UPI & Banking Compatibility**: Removed Accessibility Service registration so your banking, GPay, PhonePe, and UPI apps function without restriction or security flags.
- ⚡ **Optimized Polling**: Tuned foreground usage polling (400ms) for responsive, battery-friendly tracking.
- 🚫 **Zero False Alerts**: Eliminated false enforcement warnings in UPI-safe mode.
- 🔓 **Rock-Solid App Unlocking**: Instantaneous hold-to-unlock guarantees.

---

## 🔒 Key Features

- **P2P Direct Sync**: Operates entirely over direct peer-to-peer connections with end-to-end cryptographic signatures and local state verification. No central databases, tracking, or cloud accounts.
- **Shared Daily Pot**: Group members share an accountability pool of minutes for monitored apps.
- **Real-Time App Monitoring**: View breakdowns of member usage per monitored app.
- **In-Pact Chat & Feed**: Chat with pact members, monitor session logs, and keep each other motivated.
- **Strict Accountability**: Tamper-resistant enforcement designed to help you stay present and focused.

---

## 🛡️ Privacy & Security

- **Zero Cloud Storage**: All pact events and messages are stored locally and exchanged peer-to-peer.
- **Cryptographic Envelopes**: Every event and state change is signed with your device's private key.
- **No Analytics / Telemetry**: No tracking SDKs or external advertising frameworks.

---

## 👤 Author

Developed by **[Imagiyy](https://github.com/Imagiyy)**.
