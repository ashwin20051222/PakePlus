# WhatsApp for Linux

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" width="100" alt="WhatsApp logo">
</p>

<h1 align="center">WhatsApp for Linux</h1>

<p align="center">
  A dedicated desktop experience for WhatsApp Web on Linux.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-black?logo=linux">
  <img src="https://img.shields.io/badge/Architecture-x86__64-blue">
  <img src="https://img.shields.io/badge/Framework-Electron-47848F?logo=electron">
  <img src="https://img.shields.io/badge/Package-AppImage-green">
  <img src="https://img.shields.io/badge/Status-Personal%20Project-orange">
</p>

---

## Overview

**WhatsApp for Linux** is an unofficial desktop application that packages WhatsApp Web into a standalone Electron-based application.

It provides Linux users with a dedicated application window for messaging and communication without needing to keep WhatsApp open in a browser tab.

The application connects to the official WhatsApp Web service and uses WhatsApp's linked-device functionality.

## Features

- Dedicated WhatsApp desktop application.
- Access to WhatsApp Web.
- QR-code-based account linking.
- Messaging and conversation management.
- Photo and document sharing supported by WhatsApp Web.
- Standalone application window.
- Linux x86_64 AppImage distribution.
- Dedicated desktop launcher and application icon.

Feature availability depends on WhatsApp Web.

## Screenshots

Screenshots of the application can be added here.

## Download

Visit the GitHub Releases page to download the latest version.

**[Download WhatsApp for Linux](https://github.com/ashwin20051222/Whatsapp_for_linux/releases)**

### Available package

| Package | Platform | Architecture |
|---|---|---|
| AppImage | Linux | x86_64 |

## Installation

### Arch Linux and other AppImage-compatible distributions

Download the latest `.AppImage` file from Releases.

Make the downloaded file executable:

```bash
chmod +x WhatsApp-Web_0.0.1_amd64.AppImage
```

Launch the application:

```bash
./WhatsApp-Web_0.0.1_amd64.AppImage
```

### Optional application directory

```bash
mkdir -p ~/Applications/WhatsApp

cp WhatsApp-Web_0.0.1_amd64.AppImage \
   ~/Applications/WhatsApp/WhatsApp.AppImage

chmod +x ~/Applications/WhatsApp/WhatsApp.AppImage
```

Launch:

```bash
~/Applications/WhatsApp/WhatsApp.AppImage
```

Replace the example filename with the actual downloaded release filename when necessary.

## Account Setup

1. Launch WhatsApp for Linux.
2. Wait for the WhatsApp Web login screen.
3. Open WhatsApp on your smartphone.
4. Navigate to **Linked Devices**.
5. Select **Link a Device**.
6. Scan the QR code displayed in the desktop application.

Your existing WhatsApp account will be connected through WhatsApp's linked-device functionality.

## System Requirements

| Component | Requirement |
|---|---|
| Operating System | Linux |
| CPU Architecture | x86_64 / AMD64 |
| Application Framework | Electron |
| Distribution Format | AppImage |
| Internet Connection | Required |
| WhatsApp Account | Required |

## Project Information

| Property | Details |
|---|---|
| Project | WhatsApp for Linux |
| Version | 0.0.1 |
| Framework | Electron |
| Target Platform | Linux |
| Architecture | x86_64 |
| Repository | [Whatsapp_for_linux](https://github.com/ashwin20051222/Whatsapp_for_linux) |

## Privacy and Security

This application is a desktop wrapper around WhatsApp Web. It does not implement an independent messaging service or replace WhatsApp's infrastructure.

Authentication, conversations, messaging and linked-device functionality are provided by WhatsApp.

Never share your QR code, authentication session, or personal account information.

## Disclaimer

WhatsApp for Linux is an independent, unofficial community project.

It is not affiliated with, endorsed by, sponsored by, or officially supported by WhatsApp or Meta Platforms, Inc.

WhatsApp and its logo are trademarks of their respective owners.

## License

This repository's licensing terms should be followed when using or redistributing the project. Refer to the repository's LICENSE file where available.

## Links

- **Repository:** https://github.com/ashwin20051222/Whatsapp_for_linux
- **Releases:** https://github.com/ashwin20051222/Whatsapp_for_linux/releases
- **WhatsApp Web:** https://web.whatsapp.com/
- **Issues:** https://github.com/ashwin20051222/Whatsapp_for_linux/issues
