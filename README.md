# Lava-P7-Custom-Rom-and-Custom-Recovery
`Lava P7 Custom ROM` `Lava P7 TWRP Recovery` `Lava P7 Root` `Lava P7 MT6580 Scatter File` `Lava P7 SP Flash Tool` `Lava P7 Unbrick Firmware` `MT6580 Custom ROM` `Lava P7 Marshmallow ROM` `Lava P7 Lollipop Stock Firmware` `Lava P7 CWM Recovery` `Lava P7 PhilZ Touch` `MediaTek MT6580 Custom Recovery`
# Lava P7 Custom ROMs & Recovery Archive (MT6580)

[![Device](https://img.shields.io/badge/Device-Lava%20P7-blue.svg)](https://github.com/karansinghbhardwaj/Lava-P7-Custom-Rom-and-Custom-Recovery/)
[![Chipset](https://img.shields.io/badge/Chipset-MediaTek%20MT6580-orange.svg)](https://wiki.postmarketos.org/wiki/MediaTek_MT6580)
[![Architecture](https://img.shields.io/badge/Architecture-32--bit%20(armv7l)-red.svg)](https://support.arm.com/documentation/dui0471/m/key-features-of-arm-architecture-versions/arm-architecture-v7-m)
[![Read More](https://img.shields.io/badge/Read-More-red.svg)](https://mrksbdev.blogspot.com/p/blog-page_74.html)


A complete archive of custom recoveries, custom ROMs, and flashing resources for the **Lava P7** (MediaTek MT6580). This repository serves as a permanent preservation project for Android enthusiasts, developers, and users looking to flash, root, or unbrick their Lava P7 smartphone.

If you want to read more about these roms and recovery, here is my OLD blog (Remember Links are broken on this blogs, so download all the files from release section of this blog): [![Read More](https://img.shields.io/badge/Read-More-red.svg)](https://mrksbdev.blogspot.com/p/blog-page_74.html)

---

## 📱 Device Specifications

| Parameter | Specification |
| :--- | :--- |
| **Device Model** | Lava P7 |
| **SoC / Chipset** | MediaTek MT6580 |
| **CPU** | Quad-Core 1.3 GHz Cortex-A7 |
| **GPU** | Mali-400 MP2 |
| **Architecture** | 32-bit (`armv7l` / `ARMv7`) |
| **Stock OS** | Android 6.0 Marshmallow |
| **RAM / ROM** | 1 GB RAM / 8 GB Storage |

---

## 📦 Available Files & Downloads

All flashable binary `.zip` and `.img` files are hosted under the [Releases Page](https://github.com/karansinghbhardwaj/Lava-P7-Custom-Rom-and-Custom-Recovery/releases).

### 🛠️ Custom Recoveries
* **[TWRP]**
  * **File Name:** `recovery.img`
  * **Status:** Stable / Fully Functional
  * **Download Link:** [Get File from Releases](https://github.com/karansinghbhardwaj/Lava-P7-Custom-Rom-and-Custom-Recovery/releases)

### 🚀 Custom ROMs
* **[CyanogenMod 13, Resurrection Remix OS ]**
  * **Build Type:** Custom / Unofficial
  * **Working Features:** Wi-Fi, Bluetooth, RIL (Calls/SMS), Camera, Audio,Use Audio Fix Patches
  * **Known Bugs:** None
  * **Download Link:** [Get File from Releases](https://github.com/karansinghbhardwaj/Lava-P7-Custom-Rom-and-Custom-Recovery/releases)

---

## ⚡ Prerequisite Tools

Before flashing, make sure you have downloaded the following required MTK tools:
1. **MediaTek USB VCOM Drivers** (Required for PC detection in SP Flash Tool).
2. **SP Flash Tool (v5.x)** (For flashing recovery `.img` and scatter files).
3. **Scatter File:** `MT6580_Android_scatter.txt` (You can find that in your device specific firmware).

---

## 🛠️ Installation Instructions

### Method 1: Flashing Custom Recovery via SP Flash Tool
1. Install **MTK VCOM Drivers** on your PC.
2. Open **SP Flash Tool** (`flash_tool.exe`).
3. Click on **Scatter-loading** and select the `MT6580_Android_scatter.txt` file.
4. Uncheck all partitions except **`RECOVERY`**.
5. Click on the location path for `RECOVERY` and select the custom `recovery.img` downloaded from this repo.
6. Click **Download** in SP Flash Tool.
7. Power off your Lava P7, remove the battery (if removable), and connect it to your PC via USB cable.
8. Wait for the green **Download OK** checkmark.

---

### Method 2: Flashing Custom ROM via Recovery
1. Copy the downloaded ROM `.zip` file (and GApps if needed) to an external MicroSD Card.
2. Boot into Custom Recovery: Press and hold **Volume Up + Power Button** simultaneously.
3. In Recovery, perform a full wipe:
   * **Wipe Data / Factory Reset**
   * **Wipe Cache & Dalvik Cache**
   * **Wipe System**
4. Select **Install ZIP** -> Choose ZIP from SD Card.
5. Select the ROM `.zip` file and swipe to confirm flash.
6. *(Optional)* Flash OpenGApps (ARM / Android version corresponding to the ROM).
7. Reboot System. *(First boot may take 5–10 minutes).*

---

## ⚠️ Disclaimer
*I am not responsible for anything you do with/using these files!!*
