# Nokk ToolSet

A premium desktop application designed for high-performance media downloading, video/audio conversion, and targeted file compression. Built with **Electron**, **HTML5/CSS3**, **Vanilla JavaScript**, and powered locally by **yt-dlp** and **FFmpeg**.

Features a highly refined, hardware-accelerated **dark glassmorphism user interface** (Acrylic/Mica on Windows).

![Nokk Toolset Showcase](showcase.gif)

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

### 3. 🎬 Video to GIF with Advanced Editor & Optimizer
- Convert local video files (`.mp4`, `.mov`, `.mkv`, `.avi`) to high-quality animated GIFs.
- **Local Video Frame Preview:** Displays a live video preview and dynamically seeks (`currentTime`) to the exact frame as you drag trimmer handles.
- **Advanced Editing & Filtering:**
  - **Speed Adjustments:** Playback controls for 0.5x (Slow Motion) to 2.0x (Double Speed).
  - **Rotation & Flips:** Rotate 90° CW / 180° / 90° CCW, and mirror horizontally or vertically.
  - **Visual Filters:** Grayscale, Sepia, Negative, Vignette, and dynamic Rainbow rolling colorize effects.
- **Replace Color with Transparency (Chroma Key):** Select any color (White, Black, Green, or custom HEX code) to make transparent with adjustable similarity fuzz sliders.
- **GIF Optimization & Compression:**
  - **Palette Reduction:** Restrict color tables (256, 128, 64, or 32 max colors) to compress files.
  - **Frame Dropping:** Drop every 2nd or 3rd frame to reduce GIF size by up to 50%.
  - Custom width scales and targeted framerates.

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

## 💻 Running the Application (Portable Version)

Nokk Toolset is distributed as a portable, zero-install application for Windows:

1. **Extract the ZIP:**
   Extract the downloaded `Nokk_Toolset_Portable.zip` file to any folder on your computer.
2. **Launch the Application:**
   Double-click **`Nokk Toolset.exe`** to run the utility suite.
3. **SmartScreen Warning:**
   Since it is a portable unsigned binary, Windows Defender SmartScreen might show a warning on the first launch. Simply click **"More Info"** and then **"Run anyway"** to proceed.
