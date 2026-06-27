```markdown
# ⌚ TsixomAIWatch Buddy

> AI-powered smartwatch firmware for the **Waveshare ESP32-S3 Touch AMOLED 2.06"**, featuring voice interaction, cloud AI, a custom graphics engine, and advanced power management.

![GitHub](https://img.shields.io/badge/Platform-ESP32--S3-blue)
![Arduino](https://img.shields.io/badge/Framework-Arduino-green)
![License](https://img.shields.io/badge/License-Personal%20Use-red)
![Version](https://img.shields.io/badge/Version-v2.0-orange)

---

# ⭐ Get Version 2

👉 **Patreon**
https://www.patreon.com/tsixom/posts/tsixomaiwatch-v2-162243855?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=postshare_creator&utm_content=join_link

📩 **Need help or a custom build?**

Instagram:
https://instagram.com/tsixom

---

# Preview

<p align="center">
<img src="assets/qkerj3a5024h1.png" width="350">
</p>

---

# Features

## 🎨 Custom Graphics Engine

- No LVGL
- Fast direct rendering
- Smooth AMOLED animations
- Double-buffered canvas (v2)
- Zero flickering
- Optimized redraw system

---

## 🤖 AI Assistant

- Voice recording
- Speech-to-Text
- OpenRouter AI Chat
- Smart Mode
- Fast Mode
- Creative Mode

Supported providers:

- Deepgram
- AssemblyAI (automatic fallback)

---

## 🌐 Connectivity

- WiFi setup portal
- Store up to **3 WiFi networks**
- Automatic fallback
- Internet connectivity status

---

## ⌨ User Interface

- Full-screen touch keyboard
- Multiple themes
- Adjustable brightness
- Animated menus
- Live progress screens
- Debug utilities

---

## 🔋 Power Management

- Screen sleep
- WiFi power saving
- Light Sleep
- Deep Sleep
- Auto Deep Sleep
- Triple-tap wake
- PWR & BOOT wake

---

# Demo

## Animated Clock

![](assets/14934.gif)

---

## Settings

![](assets/14935.gif)

---

## Soft Paper Theme

![](assets/14936.gif)

---

## AI Chat

![](assets/14937.gif)

---

## Theme Selection

![](assets/14938.gif)

---

# What's New in Version 2

| Feature | Version 1 | Version 2 |
|----------|-----------|-----------|
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

# Hardware

Currently supported:

- Waveshare ESP32-S3 Touch AMOLED 2.06"

---

# Cloud Services

You'll need your own API keys for:

- OpenRouter
- Deepgram
- AssemblyAI

Internet connection is required for AI features.

---

# Repository Contents

```

Firmware/
Libraries/
Assets/
Configuration/
Documentation/

```

---

# What You Receive

After purchasing, you'll get:

- Complete Arduino source code
- Configuration guide
- Library list
- Setup instructions
- Troubleshooting guide
- Future updates
- Direct support via Instagram

---

# Installation

1. Install Arduino IDE.
2. Install ESP32 board package.
3. Install required libraries.
4. Configure your API keys.
5. Select the correct board.
6. Compile and upload.

Detailed instructions are included with the firmware.

---

# Requirements

- Waveshare ESP32-S3 Touch AMOLED 2.06"
- WiFi connection
- OpenRouter API key
- Deepgram API key
- AssemblyAI API key

---

# Disclaimer

This firmware is intended for educational and development purposes.

It is **not** a medical device or a safety-critical system.

---

# License

This firmware is licensed for **personal use only**.

You may:

- Use it on your own device
- Modify it for personal projects

You may **not**:

- Redistribute
- Resell
- Reupload
- Share source code publicly

---

# Support

Questions, bug reports, or custom firmware requests?

📩 Instagram:
https://instagram.com/tsixom

---

# If you like this project

⭐ Star the repository

❤️ Support future development on Patreon
```
