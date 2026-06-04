# TsixomAIWatch Buddy v1.0 & v2.0

> **Premium ESP32-S3 AMOLED AI Smartwatch Firmware**  
>  [Get v2 here](https://ko-fi.com/s/7e4864a32d) ☕
---

## Preview
![Watch UI](assets/qkerj3a5024h1.png)

---

## Key Features

- **Custom no-LVGL AMOLED UI** – fast, smooth, developer-friendly  
- **Voice recording + STT** – Deepgram + AssemblyAI fallback  
- **OpenRouter AI Chat** – Smart / Fast / Creative modes  
- **WiFi Setup Portal** – Save up to **3 networks with fallback**  
- **Full-screen touch keyboard**  
- **Themes & brightness control** – battery-friendly  
- **Battery saver & screen sleep**  
- **Live progress & debug screens**  
- **Memory & diagnostics tools**  

---

## Demo

### Animated Clock
![Watch UI](assets/14934.gif)

### Settings Page
![Watch UI](assets/14935.gif)

### Soft Paper Theme
![Watch UI](assets/14936.gif)

### AI Feature
![Watch UI](assets/14937.gif)

### Theme Selection
![Watch UI](assets/14938.gif)

---

## What’s New in v2.0?

| **Area**              | **v1.0**                                         | **v2.0 Upgrade**                                                                 |
| --------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------- |
| **Display Rendering**  | Direct drawing – flickering issues             | PSRAM canvas / double-buffer – **zero flickering**                               |
| **Brightness**         | Software scaling RGB                           | Hardware brightness via CO5300 – **stable themes + improved battery life**      |
| **Clock / Time**       | No real-time clock                             | NTP sync, timezone support, 12/24h format, **saved time backup**                |
| **Hardware RTC**       | Not present                                   | PCF85063 RTC – keeps time across sleep/reboot                                   |
| **Power Management**   | Basic screen sleep & WiFi saver               | Screen sleep, light sleep, deep sleep, auto deep sleep, **manual sleep options**|
| **Wake Behavior**      | BOOT button only                               | PWR + BOOT deep wake, **triple-tap screen wake**                                 |
| **Touch System**       | Basic debounce / held-touch                    | Reliable gesture system – tap/swipe detection, **release timeout**               |
| **Settings Pages**     | Voice, AI, Display, WiFi, Debug, About        | Adds Time & Power settings, scrollable settings home                             |
| **Home Screen**        | Buddy/home only                               | Morphable Buddy → **large clock view**                                           |
| **Telemetry**          | Battery/heap/WiFi read live                   | Cached UI telemetry → smoother redraw, less stutter                               |
| **Debug/About UI**     | Raw diagnostics                               | Cleaner About page, diagnostics moved into Debug                                  |

---

## What You Get on Ko-fi
- Full **Arduino source code**  
- Step-by-step **setup instructions**  
- Complete **library list**  
- **Configuration guide**  
- Troubleshooting tips  
- Future update access  
- **Contact me on Instagram** for custom requests: [www.instagram.com/tsixom](https://www.instagram.com/tsixom)

---

## Supported Hardware
- [ESP32-S3 Touch AMOLED 2.06](https://www.waveshare.com/wiki/ESP32-S3-Touch-AMOLED-2.06)

---

## Required Cloud Services
- OpenRouter AI  
- Deepgram  
- AssemblyAI  

> **Note:** You need your own API keys. Internet connection is required for AI/STT.  
> Firmware is **developer-grade**, not a medical or safety device.

---

## Support me
[Get it on Ko-fi](https://ko-fi.com/tsixom) ☕  

**Why You’ll Love It:**
- AI smartwatch **ready-to-go**  
- Smooth AMOLED UI & animations  
- Full developer access to source  
- Easy integration with AI/STT services  

---

## License / Usage
- **Personal use only**  
- **No resale or redistribution**  
- Developer-friendly **open source firmware**  

---
