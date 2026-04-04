<p align="center">
<img src="logo.png" alt="SaveMimi Logo" width="128"/>
</p>

<h1 align="center">SaveMimi v2.0 — Universal Downloader</h1>

<p align="center">
A modern, futuristic desktop application serving as a powerful YouTube video grabber and a high-speed, IDM-style software downloader.
<br />
<br />
<img src="https://github.com/faizanaauf/SaveMimi/blob/main/Screenshot%20(237).png" alt="Video Downloader UI" width="700">
<br />
<img src="https://github.com/faizanaauf/SaveMimi/blob/main/Screenshot%20(238).png" alt="Software Downloader UI" width="700">
</p>

## 🌟 About The Project

SaveMimi v2.0 is a powerful, standalone desktop tool for Windows that completely overhauls the downloading experience. It features a sleek, dual-mode interface designed to handle your two biggest needs: pulling high-quality media from YouTube, and downloading direct files (software, ISOs, ZIPs) at maximum speed. 

Built with a "smart" engine, SaveMimi checks your system's hardware capabilities before processing 4K/8K videos to prevent crashes, while its custom multi-connection file downloader mimics the blistering speeds of traditional download managers.

## ✨ Features

**🎬 Video Downloader Mode**
* **Total YouTube Support:** Download any video or audio from YouTube, from 144p all the way up to 8K (4320p) UHD.
* **Smart Hardware Check:** Automatically detects your system's hardware decoders (NVIDIA NVENC, Intel Quick Sync, AMD AMF).
* **Safe Quality Selection:** If you select a high-resolution format (4K/8K) that your system may struggle to process, the tool provides a clear, non-intrusive warning.
* **Thumbnail & Title Preview:** Instantly verifies your link with a rich UI preview before you commit to downloading.
* **Guaranteed Audio:** The smart merging engine fixes the notorious "no sound" error found in other downloaders by automatically handling advanced codec merging.

**💾 Software & File Downloader Mode**
* **IDM-Style Speeds:** Uses a multi-connection, chunk-based downloading engine to max out your internet bandwidth for direct file links (`.exe`, `.zip`, `.iso`, `.mp4`, etc.).
* **Pause & Resume:** Safely pause your large downloads and resume them later without data corruption.
* **Session Persistence:** Close the app, shut down your PC, and come back tomorrow. SaveMimi remembers your queue and picks up exactly where it left off.
* **Auto-Retry:** If your internet connection drops, the app won't crash. It simply waits for the connection to return and continues downloading.

**⚙️ Core Architecture**
* **Zero Dependencies:** The final `.exe` is a single, portable file. No Python, no command-line tools, and no manual FFmpeg installation required on the user's machine.

---

## 🚀 How to Use

### 1. Get the App
1. Go to the **[Releases Page](../../releases)** of this repository.
2. Download the latest `SaveMimi.exe` file.
3. Since the tool is entirely portable, **no installation is needed**. Just double-click the `.exe` to run it!

### 2. Downloading Videos
1. Click the **"Video Downloader"** tab at the top.
2. Paste your YouTube URL into the text box.
3. Click the **"Download"** (Fetch) button.
4. Wait a moment for the thumbnail and quality list to appear.
5. Select your desired resolution from the dropdown menu and proceed. A "Save As..." dialog will let you choose your destination.

### 3. Downloading Software / Direct Files
1. Click the **"Software Downloader"** tab at the top.
2. Paste a direct download URL (e.g., a link ending in `.zip` or `.exe`) into the text box.
3. Click **"Add Download"**.
4. Choose where to save the file. The download will appear as an elegant card in your queue below.
5. Use the controls on the card to pause, resume, or monitor your download speed and ETA.
