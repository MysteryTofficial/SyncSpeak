# SyncSpeak Professional v1.2.0

![SyncSpeak License](https://img.shields.io/badge/License-MIT-green.svg)
![Version](https://img.shields.io/badge/Version-1.2.0-blue.svg)
![Type](https://img.shields.io/badge/Build-Professional-00ff88.svg)

**SyncSpeak Professional** is a high-precision, browser-based tool designed to measure and calibrate audio-visual latency (lipsync offset). Primarily developed for high-end sound systems like the Logitech Z906, it provides millisecond-accurate data to ensure perfect harmony between your display and speakers.



## 🚀 Key Features

* **Dual-Unit Architecture:** Includes both a **Signal Source** (Transmitter) and an **Analyzer Unit** (Receiver) in a single portable file.
* **Hardware Flexibility:** Full support for selecting specific Camera and Microphone inputs.
* **Precision Targeting:** Center-frame crosshair focus for targeted light detection, minimizing background interference.
* **Professional Metrics:** Real-time visual feedback for light and acoustic intensity with adjustable threshold triggers.
* **Statistical Analysis:** Automatically calculates running averages to eliminate jitter and environmental noise.
* **Data Export:** Save your calibration results into professional `.txt` logs for later reference.
* **Multilingual:** Full support for English and Hungarian (HU/EN).

## 🛠️ How It Works

1.  **Source Mode:** Run this on your main display (PC/TV). It generates a synchronized white flash and a 1kHz audio "click" every second.
2.  **Analyzer Mode:** Run this on a mobile device or a laptop with a camera.
3.  **Alignment:** Point the camera crosshair at the flashing area on the screen.
4.  **Measurement:** The app detects the flash (Light) and the subsequent sound (Acoustic). The time difference between them is your **Latency Offset**.
5.  **Calibration:** Use the **Average Latency** value to adjust the delay settings on your Audio Console or Media Player.

## 📦 Installation

This is a standalone, single-file application. No installation required.

1.  Clone the repository: `git clone https://github.com/username/syncspeak.git`
2.  Open `index.html` in any modern, secure browser (Chrome/Edge/Firefox recommended).
3.  Ensure you have a `logo.ico` in the same directory for the professional branding experience.

## 🔧 Technical Details

* **Engine:** Pure HTML5, CSS3, and Vanilla JavaScript.
* **APIs:** Web Audio API (for zero-latency sound processing), MediaDevices API (for hardware access).
* **Deployment:** Can be packaged as a `.crx` extension for dedicated application use.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
**Developed by:** MysteryT
**Build:** Professional Grade
