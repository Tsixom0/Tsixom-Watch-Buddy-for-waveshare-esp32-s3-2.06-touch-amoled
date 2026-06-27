#  TsixomAIWatch Buddy

> AI-powered smartwatch firmware for the **Waveshare ESP32-S3 Touch AMOLED 2.06"**, featuring voice interaction, cloud AI, a custom graphics engine, and advanced power management.

<p align="center">
  <img src="https://img.shields.io/badge/Platform-ESP32--S3-blue" alt="Platform">
  <img src="https://img.shields.io/badge/Framework-Arduino-green" alt="Framework">
  <img src="https://img.shields.io/badge/License-Personal%20Use-red" alt="License">
  <img src="https://img.shields.io/badge/Version-v2.0-orange" alt="Version">
</p>

<p align="center">
  <a href="https://www.patreon.com/tsixom/posts/tsixomaiwatch-v2-162243855?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=postshare_creator&utm_content=join_link">
    <strong>⭐ Get Version 2 on Patreon</strong>
  </a>
</p>

---

## Preview

<p align="center">
  <img src="assets/qkerj3a5024h1.png" width="350" alt="TsixomAIWatch Buddy Preview">
</p>

---

## Features

###  Custom Graphics Engine
- No LVGL
- Fast direct rendering
- Smooth AMOLED animations
- Double-buffered canvas in v2
- Zero flickering
- Optimized redraw system

###  AI Assistant
- Voice recording
- Speech-to-text
- OpenRouter AI chat
- Smart Mode
- Fast Mode
- Creative Mode

**Supported speech providers:**
- Deepgram
- AssemblyAI (automatic fallback)

###  Connectivity
- Wi-Fi setup portal
- Store up to **3 Wi-Fi networks**
- Automatic fallback
- Internet connectivity status

###  User Interface
- Full-screen touch keyboard
- Multiple themes
- Adjustable brightness
- Animated menus
- Live progress screens
- Debug utilities

###  Power Management
- Screen sleep
- Wi-Fi power saving
- Light sleep
- Deep sleep
- Auto deep sleep
- Triple-tap wake
- PWR and BOOT wake

---

## Demo

### Animated Clock
![Animated Clock](assets/14934.gif)

### Settings
![Settings](assets/14935.gif)

### Soft Paper Theme
![Soft Paper Theme](assets/14936.gif)

### AI Chat
![AI Chat](assets/14937.gif)

### Theme Selection
![Theme Selection](assets/14938.gif)

---

## What’s New in Version 2

| Feature | Version 1 | Version 2 |
|--------|-----------|-----------|
| Display | Direct rendering | PSRAM canvas + double buffering |
| Flickering | Present | Completely removed |
| Brightness | Software RGB scaling | Hardware CO5300 brightness |
| Clock | None | NTP synchronization |
| Time Backup | None | Persistent saved time |
| Hardware RTC | — | PCF85063 support |
| Sleep Modes | Basic | Light, Deep & Auto Deep Sleep |
| Wake | BOOT only | PWR + BOOT + Triple Tap |
| Touch | Basic | Improved gesture engine |
| Home Screen | Buddy only | Buddy + Large Clock |
| Settings | Basic | Time & Power settings |
| Telemetry | Live reads | Cached rendering |
| Debug UI | Mixed | Cleaner diagnostics |

---

## Supported Hardware

Currently supported:
- **Waveshare ESP32-S3 Touch AMOLED 2.06"**

---

## Cloud Services

You’ll need your own API keys for:
- OpenRouter
- Deepgram
- AssemblyAI

> Internet access is required for AI features.

---

## Repository Contents

```text
Firmware/
Libraries/
Assets/
Configuration/
Documentation/
```

---

## What You Receive

After purchasing, you’ll receive:
- Complete Arduino source code
- Configuration guide
- Library list
- Setup instructions
- Troubleshooting guide
- Future updates
- Direct support via Instagram

---

## Installation

1. Install Arduino IDE.
2. Install the ESP32 board package.
3. Install the required libraries.
4. Configure your API keys.
5. Select the correct board.
6. Compile and upload.

> Detailed instructions are included with the firmware.

---

## Requirements

- Waveshare ESP32-S3 Touch AMOLED 2.06"
- Wi-Fi connection
- OpenRouter API key
- Deepgram API key
- AssemblyAI API key

---

## Disclaimer

This firmware is intended for educational and development purposes.

It is **not** a medical device or a safety-critical system.

---

## License

This firmware is licensed for **personal use only**.

You may:
- Use it on your own device
- Modify it for personal projects

You may **not**:
- Redistribute
- Resell
- Reupload
- Share the source code publicly

---

## Support

Questions, bug reports, or custom firmware requests?

📩 Instagram: https://instagram.com/tsixom

---

## If You Like This Project

- ⭐ Star the repository
- ❤️ Support future development on Patreon
