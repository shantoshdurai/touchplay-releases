# TouchPlay

<p align="center">
  <img src="screen1.png" width="48%" alt="TouchPlay Controller Screen" />
  <img src="screen2.png" width="48%" alt="TouchPlay Menu & Features" />
</p>

**Turn your Android phone into a real gamepad, trackpad, and second screen for any PC game.**

This repository hosts the official PC server releases for TouchPlay, the official website, and serves as our public issue tracker.

---

## 🚀 Quick Download & Setup

### 📱 Android Phone App
* **Play Store:** [Get TouchPlay on Google Play](https://play.google.com/store/apps/details?id=com.touchplay.app)
* **Direct APK:** Download from our [Latest Releases](https://github.com/shantoshdurai/touchplay-releases/releases/latest)

---

### 💻 PC Server (Windows & Linux)

| Platform | How to Run | Highlights |
| :--- | :--- | :--- |
| **🪟 Windows (10 / 11)** | Download and run [**TouchPlay-Server.exe**](https://github.com/shantoshdurai/touchplay-releases/releases/latest/download/TouchPlay-Server.exe) | Bundled ViGEmBus driver, GUI window with drag-and-drop, tray support |
| **🐧 Linux (Arch / Ubuntu / Fedora / Omarchy)** | Clone & run `./setup.sh` then `./TouchPlay-Server.sh` | Native `/dev/uinput` evdev, Wayland (`grim`) & X11 capture, rich terminal TUI & `touchplay-send` CLI |

---

## ⚖️ Platform Differences: Windows vs Linux

| Feature | 🪟 Windows | 🐧 Linux |
| :--- | :--- | :--- |
| **Server Interface** | Minimal GUI window with drag-and-drop | High-performance Terminal Dashboard (Rich TUI) |
| **Gamepad Driver** | Bundled ViGEmBus (Xbox 360 & DualShock 4) | Kernel `/dev/uinput` (evdev native, zero install) |
| **Screen Streaming** | DirectX Desktop Duplication (DXGI) | Wayland screencopy & X11 with GPU offload |
| **Virtual 2nd Display** | Virtual Display Driver (VDD) | Headless Wayland output (`phone-display` in Hyprland) |
| **Media / File Drop** | `%USERPROFILE%\Downloads\TouchPlay` (GUI drop-zone) | `~/Downloads/TouchPlay` + `touchplay-send` CLI tool |

---

## 🌐 Official Website
Visit our live download portal at [**shantoshdurai.github.io/touchplay-releases**](https://shantoshdurai.github.io/touchplay-releases/).

## 💬 Support & Feedback
- Have an idea or need help? Join the [Discussions](https://github.com/shantoshdurai/touchplay-releases/discussions).
- Found a bug? Open an [Issue](https://github.com/shantoshdurai/touchplay-releases/issues).
