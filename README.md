# Clipod: A Distraction-Free Offline Music Player

**Clipod** is a small, clip-on, open-source Linux audio player designed for athletes, minimalists, and anyone who wants to enjoy music without the constant distractions of a smartphone. Think of it as the spiritual successor to the iPod Shuffle, but modernized for the 2020s.

---

## 🚀 The Vision

Most people use smartphones for music, which brings notifications and social media distractions. Clipod fills the gap for a sub-$70 dedicated device with physical controls and zero subscriptions.

* 
**No Phone Required:** Once set up, it works completely independently.


* 
**Dual-Source Audio:** Play high-quality local files (MP3, FLAC, etc.) from a microSD card or stream audio from YouTube over Wi-Fi.


* **Distraction-Free:** No apps, no messages, no scrolling. Just your music.



---

## 🛠️ Hardware Specifications

The hardware is designed to be lightweight (under 25g) and durable.

| Component | Specification |
| --- | --- |
| **SoC** | Rockchip RK3128 (v1) / Allwinner V3s (v2 target) 

 |
| **Display** | 1.3" OLED (128×64 pixels), SSD1306/SH1106 

 |
| **Audio** | 3.5mm Headphone Jack (Wired-only philosophy) 

 |
| <br>**Storage** | microSD slot supporting up to 1TB 

 |
| **Battery** | 600mAh LiPo (10-14 hours playback) 

 |
| **Connectivity** | 2.4GHz 802.11n Wi-Fi (for streaming & setup) 

 |
| **Controls** | 6 physical dome tactile switches 

 |

---

## 💻 Software Architecture

Clipod runs a minimal, stripped-down Linux kernel (5.15 LTS) built using **Buildroot**.

* 
**Audio Engine:** Powered by **MPD (Music Player Daemon)** for local file management.


* 
**YouTube Client:** A custom daemon utilizing `yt-dlp` for stream URL extraction and `ffmpeg` for real-time audio playback.


* 
**UI/UX:** A lightweight Python-based UI using the `luma.oled` library.


* 
**Companion App:** An open-source Android/iOS app for easy Wi-Fi file transfers and Spotify playlist migration (metadata only).



---

## ⚖️ Legal & Open Source

Clipod is built on a foundation of transparency and user ownership.

* 
**Software:** Licensed under MIT/GPL.


* 
**Hardware:** Schematics and CAD files published under CERN-OHL-P.


* **Streaming:** The device is a personal-use client. It does not download or "rip" YouTube content to disk; it streams in real-time, which falls under "Fair Dealing" in many jurisdictions like India and the EU.



---

## 📅 Roadmap

1. 
**Phase 0 (Software Prototype):** Running the stack on a Raspberry Pi Zero 2W.


2. 
**Phase 1 (Custom PCB):** KiCad design and assembly of dedicated hardware.


3. 
**Phase 2 (Beta):** Field testing with runners and gym-goers.


4. 
**Phase 3 (Production):** Crowdfunding campaign to launch the first 500+ units.



---

