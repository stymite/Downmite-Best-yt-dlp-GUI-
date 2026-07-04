# DownMite — Free yt-dlp GUI & Universal Social Media Video Downloader

DownMite is a premium, lightweight, and ad-free media downloader that helps you download videos and audio from major social platforms like YouTube, Instagram, Twitter/X, TikTok, Facebook, and LinkedIn. 

Because of connection and rate limits when running downloads on a cloud server, DownMite has both a Web version and a native Desktop App. They possess different features to optimize your downloading experience.

🔗 **Try it online:** [downmite.vercel.app](https://downmite.vercel.app)

---

## Features

1. **Rename Videos:** Change the file name of your video before the download starts.
2. **Trim Videos:** Trim the video to your desired length to save storage and download time.
3. **Crop Videos:** Crop the frame size of the video to focus on what matters.
4. **Music Detection:** Shazam-style audio fingerprinting to identify background songs playing in the video.
5. **Web PWA for Mobile:** Add DownMite to your mobile home screen (note: Web/PWA downloads are subject to YouTube server proxy limits; a mobile app is coming soon).
6. **Download History (App Only):** Keep local track of all your past downloads in a simple interface.
7. **Direct Import/Export (Website Only):** Instantly back up or restore your configuration settings.
8. **Push Notifications (App Only):** Get notified automatically on your desktop the second your download and conversion finish.
9. **Multiple Format Support (App Only):** Convert and save downloads in various video and audio formats.
10. **Easy Cookies Implementation (App Only):** Easily import cookies to bypass YouTube rate-limits, and download age-restricted or private content from YouTube, Instagram, and X.
11. **Multi-Video Detection:** Automatically detect and download multiple videos from a single Twitter/X post.
12. **Real-time Stats:** Shows estimated file size and download progress percentage dynamically.
13. **Auto-Updates:** The desktop application automatically checks for and applies updates on launch.
14. **Update Broadcasts:** In-app messages sent to all desktop application users for critical announcements and upgrades.

---

## How to Install the Desktop App

Because browsers often block `.exe` files to prevent false-positives, the installer is bundled inside a password-protected zip file.

1. Download the `DownMite.zip` file from this repository.
2. Extract the ZIP file using standard Windows Explorer (Double-click the ZIP).
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

DownMite's desktop and mobile applications run entirely on your own computer. No media is routed through external cloud servers—all extractions, conversions, and downloads occur locally on your machine.
