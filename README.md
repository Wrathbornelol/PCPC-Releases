# PC Phone Connector

Use your Android phone's **camera and microphone on your Windows PC**, **share its screen**,
**send files both ways** and **scan documents**, over your home Wi-Fi. No cables, no accounts,
no cloud.

**[⬇ Download the latest version](https://github.com/Wrathbornelol/PCPC-Releases/releases/latest)**

## Features

- 📷 **Phone camera as a webcam.** Shows up as *OBS Virtual Camera* in Discord, Teams, Zoom,
  OBS and other apps. Quality from 720p up to 1080p 60 fps; 1440p and 4K are experimental.
- 🎤 **Phone microphone on the PC.** Usable as a microphone in any app (*CABLE Output*). It
  starts muted every time, and you unmute it on the phone.
- 📱 **Screen mirroring.** Show the phone's screen in its own window on the PC (view only).
  It never goes into the webcam picture, so it can't end up in a call by accident.
- 📁 **Files both ways.** Drag and drop on the PC, pick files in the phone app, or use
  **Send to PC** in Android's Share menu from any app (photos, documents, links). Each side
  asks before accepting files, and can always accept from phones you trust. Every file is
  checked for damage when it arrives. Right-click a file on the PC to open it, show it in
  its folder or see its properties.
- 📄 **Document scanner.** Photograph a page and get it straightened, cropped and cleaned up,
  as a PDF and/or images. The text is recognised on the phone (Czech and English), so you
  can select, copy and search it in the PDF, or get it as a plain `.txt`. Save scans on the
  phone, send them to the PC, or both. Works without the PC too.
- 🔍 **Finds your PC by itself.** Open the app on the same Wi-Fi and it connects.
- 🔒 **Paired and encrypted.** Each phone is paired once with a QR code or a 6-digit code.
  After that, everything between phone and PC is encrypted, and only paired phones get in.
- 🌙 **Streaming mode.** The phone dims its screen while streaming to save battery.
- 🔋 **Phone battery on the PC.** See the phone's battery on the PC, with a warning when
  it's running low during a call.
- 🔄 **Updates itself.** The PC app checks here for new versions. Each update is signed and
  checked before it installs. Phones get new versions of their app from the PC.
- 🖥 **Lives in the tray.** It can start with Windows and runs quietly in the background.
- 🌍 **English and Czech.**

## What you need

- A **Windows 10 or 11** PC (64-bit)
- An **Android 10 or newer** phone on the **same Wi-Fi**. The document scanner also needs
  Google Play services (standard on most phones).
- For the camera: **[OBS Studio](https://obsproject.com)** 28 or newer (free). It only needs
  to be installed and started once.
- For the microphone: **[VB-Cable](https://vb-audio.com/Cable/)** (free). Restart the PC after
  installing it.

The app works without OBS and VB-Cable; you just won't have the camera or microphone.

## Installing

1. **PC:** download `PC-Phone-Connector-Setup-<version>.exe` from the
   [latest release](https://github.com/Wrathbornelol/PCPC-Releases/releases/latest) and run
   it. It isn't code-signed, so Windows may say *"Windows protected your PC"*. Click
   **More info → Run anyway**.
2. **Phone:** in the PC app, open **Phones → Set up a new phone** and scan the QR code with the
   phone's camera. The phone downloads the app straight from your PC. (Or download
   `PCPhoneConnector-<version>.apk` from the release page on the phone.)
3. Open the app on the phone. When the PC asks, click **Show pairing code** and scan it on
   the phone. That's it.

## Files in each release

| File | What it is |
| --- | --- |
| `PC-Phone-Connector-Setup-<version>.exe` | Installer for Windows. It also updates an existing installation. |
| `PCPhoneConnector-<version>.apk` | The Android app |
| `release.json`, `release.json.sig` | Used by the app to check for and verify updates. You can ignore them. |

---

A hobby project made for friends. The source code isn't public.
