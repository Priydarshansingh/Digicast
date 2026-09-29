# Digicast Extensions Guide

This guide explains how to install and use official `.dcast` extensions in the Digicast mobile ecosystem.

---

### 📦 Available Extensions

1. **YouTube Video Downloader (`com.digicast.ext.youtubedl`)**
   - High-quality video & audio extraction (1080p60 / 1440p / 4K).
   - Enables offline stream caching directly on your device.

2. **FFmpeg Video Trimmer (`com.digicast.ext.ffmpeg`)**
   - Lossless precision trimming without re-encoding quality loss.
   - Fast frame-accurate cuts for highlight clips.

3. **Digicast Clip Engine - Full Suite (`com.digicast.ext.clipengine`)**
   - All-in-one automated pipeline combining downloader and trimmer.

---

### 📲 How to Install Extensions

#### Method 1: In-App Extensions Catalog (Recommended)
1. Open the **Digicast App** on your device.
2. Navigate to **Settings → Extensions Catalog**.
3. Tap **Install** next to any extension.
4. The extension will automatically download and activate.

#### Method 2: Direct 1-Tap Installation (`.dcast` file)
1. Download any `.dcast` package from the [Releases](https://github.com/Priydarshansingh/Digicast/releases) or the [`extensions/`](extensions/) folder.
2. Tap the downloaded `.dcast` file in your device's file manager or browser.
3. The Digicast App will open and register the extension instantly.

---

### 🛡️ Security & Sandboxing

All `.dcast` extensions run locally inside a sandboxed environment on your device. Extensions do not transmit any video or personal data to external servers.
