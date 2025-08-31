# Beetle

**Beetle** – Air-gapped, simple, and secure Bitcoin seed creator & signing device.

## Overview

Beetle is a **minimalist, open-source hardware device** designed to make Bitcoin self-custody accessible to everyone. It allows users to:

- **Create Bitcoin seeds** safely offline, without storing private keys.
- **Sign Bitcoin transactions** via QR codes, keeping private keys air-gapped.
- **Use simple input controls** (buttons only) for intuitive navigation.
- **Learn self-custody best practices** including seed creation and backup.

Beetle focuses on **simplicity, security, and usability**:

- **Air-gapped:** No Wi-Fi or Bluetooth, completely offline.
- **User-friendly:** Minimal interface, intuitive controls, and visual feedback.
- **Secure:** Private keys never leave the device; all operations are offline.
- **Open source:** All hardware schematics, software, and documentation are freely available.

## Hardware Requirements

- ESP32 T-Display (with 2 programmable buttons)
- ESP32-CAM module (any compatible model)
- Optional: SD card for backups
- USB-C for power

## Software Requirements

- Arduino IDE
- TFT_eSPI library
- BIP39 library
- SHA256 library
- QR code generator library

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/BeetleSeed/Beetle.git
