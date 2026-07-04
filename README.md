# DownMite — Free yt-dlp GUI & Universal Social Media Video Downloader

DownMite is a premium, lightweight, and ad-free media downloader that helps you download videos and audio from major social platforms like **YouTube, Instagram, Twitter/X, TikTok, Facebook, and LinkedIn**. 

Designed to be simple, fast, and secure, DownMite operates on-device to protect your privacy and ensure lightning-fast processing speeds.

🔗 **Try it online:** [downmite.vercel.app](https://downmite.vercel.app)

---

## Key Features

🚀 **Multi-Platform Support**
Download original video or audio streams from YouTube, Instagram, X (Twitter), TikTok, Facebook, and LinkedIn.

✂️ **In-App Video Trimming & Cropping**
Don't download long videos just for a 5-second clip. Crop the frame size and trim the duration of the media before saving it to your device.

🎵 **Shazam-Style Music Detection**
Hear a background track in a clip but don't know the name? DownMite uses advanced audio fingerprinting to identify the song before download.

📂 **Download History**
Keep track of all your past downloads in a simple, local interface (Desktop App only).

🍪 **Cookie Support (Bypass Restrictions)**
Easily import your browser cookies to bypass YouTube rate-limits or download age-restricted/explicit content securely.

🔔 **Push Notifications**
Get notified automatically on your desktop the second your download and conversion finish.

---

## How to Install the Desktop App

Because browsers often block `.exe` files to prevent false-positives, the installer is bundled inside a password-protected zip file.

1. **Download** the `DownMite.zip` file from this repository.
2. **Extract the ZIP file** using standard Windows Explorer (Double-click the ZIP).
3. Enter the password: **`123`**
4. Run `DownMite_Setup.exe` to install and launch the application.

---

## Technologies Used

* **Frontend:** React, Next.js, Tailwind CSS, Framer Motion
* **Desktop Shell:** Tauri, Rust
* **Downloader Engine:** yt-dlp (Python)
* **Media Processing:** FFmpeg
* **Music Recognition:** Shazam API / AudD

---

## Privacy First

DownMite's desktop and mobile applications run **entirely on your own computer**. No media is routed through external cloud servers—all extractions, conversions, and downloads occur locally on your machine.
