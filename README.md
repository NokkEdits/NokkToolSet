# Nokk Toolset

A premium desktop application designed for high-performance media downloading, video/audio conversion, and targeted file compression. Built with **Electron**, **HTML5/CSS3**, **Vanilla JavaScript**, and powered locally by **yt-dlp** and **FFmpeg**.

Features a highly refined, hardware-accelerated **dark glassmorphism user interface** (Acrylic/Mica on Windows).

---

## 📥 Get Access & Download

Nokk Toolset is a subscription-based utility software. To download the application and activate your lifetime/active license:

1. **Subscribe on Buy Me a Coffee:**
   Go to [https://buymeacoffee.com/nokk/membership](https://buymeacoffee.com/nokk/membership) and subscribe to the active membership tier.
2. **Download the App:**
   Upon subscribing, you will instantly receive the secure **Google Drive download link** for the latest portable package (`Nokk_Toolset_Portable.zip`) in your welcome email or members-only posts.
3. **Activate & Run:**
   Extract the zip archive anywhere, launch **`Nokk Toolset.exe`**, enter the email associated with your Buy Me a Coffee subscription, and click **Activate Now**.

---

## 🚀 Key Features

### 1. 📥 Multi-Platform Media Downloader
- Download video and audio files from **YouTube, Twitch, Kick, TikTok, Twitter (X), Instagram, and Reddit**.
- Support for single-link downloading, quality preference matching, and **batch downloading** (multiple links, one per line).

### 2. ✂️ VOD Downloader & Visual Timeline Trimmer
- Analyzes URLs dynamically to retrieve streams/VOD metadata (Title, views, thumbnail, exact durations, and format options).
- Integrates a **custom double-ended range trimmer slider**.
- Drag start/end handles to select the segment of interest visually with floating time indicators (`hh:mm:ss`).
- **Fast Chunk Downloading:** Streams and downloads only the selected range using `yt-dlp --download-sections`. Saves gigabytes of bandwidth and crops VODs in seconds.

### 3. 🎬 Video to GIF with Range Trimmer
- Convert local video files (`.mp4`, `.mov`, `.mkv`, `.avi`) to high-quality animated GIFs.
- Trims the exact conversion window visually on a visual range slider.
- Generates high-fidelity 256-color custom palettes for clean, color-accurate GIF rendering.
- Selectable widths (`320px`, `480px`, `640px`, or original) and frame rates (`10`, `15`, `24`, or `30` FPS).

### 4. 🔄 MOV to WebM Converter
- Direct transcoder for Apple MOV files into modern, optimized WebM files using local VP9 and Opus encoding.
- Preset quality toggles: *Medium/Balanced*, *High Quality (Slower)*, or *Faster Encoding*.

### 5. 📉 Targeted Video Compressor
- Compresses large local video files down to a specific target file size (e.g., **25 MB** for Discord Free limits, 50 MB, 100 MB, or custom target size).
- Runs 1-pass fast H.264/AAC compression based on dynamically calculated target bitrates.

### 6. 🎵 Audio Converter & Extraction
- **Extractor:** Extract high-quality MP3 audio files directly from online videos (adjustable bitrates up to 320 kbps).
- **Converter:** Transcode local audio files between **MP3, WAV, FLAC, and M4A**.

### 7. 🖼️ Image Converter (includes Apple HEIC support)
- Batch transcode local image files between **WebP, JPEG, and PNG**.
- Integrates Apple `.heic`/`.heif` image formats support (powered by local Pillow scripts).

### 8. 🛡️ Licensing System
- Secured via Buy Me a Coffee active membership validation.
- Validates active licenses on-the-fly and permits offline developer trial bypass.

---

## 🛠️ Installation & Setup

1. **Prerequisites:**
   - [Node.js](https://nodejs.org/) installed on your machine.
   - Python installed (with `Pillow` and `pillow-heif` dependencies for HEIC conversion support: `pip install pillow pillow-heif`).

2. **Clone and Install:**
   ```bash
   npm install
   ```

3. **Start Development Server:**
   ```bash
   npm start
   ```

4. **Build Portable App:**
   Run the PowerShell build script:
   ```powershell
   .\build-portable.ps1
   ```
   This will package the app, bake in the window executable icons using `rcedit`, and generate the final portable package at:
   `C:\Users\furka\Desktop\Nokk_Toolset_Portable.zip`.
