# VRC-NexusChat

<div align="center">

![Version](https://img.shields.io/badge/version-0.0.1-e94560?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Windows-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-Proprietary-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/status-Early%20Access-green?style=for-the-badge)

**The ultimate VRChat OSC companion — built for the community, by the community.**  
Send messages, display your time, control your HUD, and more — all from one sleek desktop app.

[Download](#installation) · [Features](#features) · [Support](#support) · [Legal](#legal-notice)

</div>

---

> [!IMPORTANT]
> Please make sure to **[enable OSC](https://youtu.be/OHjN_q6RqGY?t=80)** inside VRChat before using VRC-NexusChat.  
> Without OSC enabled, the app will not be able to communicate with VRChat.

---

## What is VRC-NexusChat?

VRC-NexusChat is a free, lightweight desktop application that connects your PC directly to VRChat via OSC (Open Sound Control).  
It allows you to send chatbox messages, display real-time information like your local time, and control various VRChat features — without ever leaving your desktop.

Built with **Electron**, **React**, and **TypeScript** for a fast, modern experience.

---

## Installation

> [!NOTE]
> VRC-NexusChat requires **Windows 10 or 11** to run.

- 🔳 Download the latest **[Release](../../releases)** ZIP file
- 🔳 Extract the ZIP into a folder of your choice
- 🔳 Run `VRC-NexusChat.exe`
- 🔳 Enable OSC in VRChat *(Action Menu → Options → OSC → Enable)*
- 🔳 Done — enjoy! 🎉

---

## Features

> [!NOTE]
> VRC-NexusChat is actively developed. New features are added regularly!

| Feature | Status | Description |
|---|---|---|
| 💬 Chatbox | ✅ Available | Send custom messages to your VRChat Chatbox |
| ⏱️ Local Time | ✅ Available | Automatically display your local time in VRChat |
| 🎵 Spotify | 🚧 Coming Soon | Show your currently playing song in VRChat |
| 🥽 HUD Settings | 🚧 Coming Soon | Customize your VR HUD display |
| 🌤️ Weather | 🔜 Planned | Display local weather in your Chatbox |
| 💤 AFK Module | 🔜 Planned | Automatically set AFK status |

---

## How It Works

```
VRC-NexusChat  →  OSC (UDP Port 9000)  →  VRChat Chatbox
```

VRC-NexusChat sends OSC messages directly to VRChat running on your PC.  
No internet connection required — everything runs locally.

---

## Built With

| Technology | Purpose |
|---|---|
| [Electron](https://www.electronjs.org/) | Desktop App Framework |
| [React](https://react.dev/) | UI Framework |
| [TypeScript](https://www.typescriptlang.org/) | Type-safe JavaScript |
| [osc.js](https://github.com/colinbdclark/osc.js/) | OSC Communication |

---

## Support

> [!NOTE]
> Need help? More support options are coming soon!

If you run into any issues:
- 🐛 **Bug?** Open an **[Issue](../../issues)** on GitHub
- 💡 **Feature Request?** Open a **[Discussion](../../discussions)** on GitHub

---

## Roadmap

- [x] Chatbox messaging
- [x] Local time display
- [ ] Spotify integration
- [ ] HUD customization
- [ ] Weather display
- [ ] AFK module
- [ ] Auto-updater

---

## Legal Notice

> [!IMPORTANT]
> VRC-NexusChat is released under a **custom proprietary license**.  
> The source code is publicly visible for transparency, but **no permission is granted** to copy, modify, redistribute, or create derivative works without explicit written permission from the author.

By downloading or using VRC-NexusChat, you confirm that you have read and agreed to these terms.

---

## Disclaimer

VRC-NexusChat is an independent project and is **not affiliated with VRChat Inc.** in any way.  
All product names, logos, and brands are property of their respective owners.  
VRChat is a trademark of VRChat Inc.

---

<div align="center">

Made with ❤️ by **Juicy**  
© 2026 VRC-NexusChat — All Rights Reserved

</div>
