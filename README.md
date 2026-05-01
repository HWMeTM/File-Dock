# 📦 FileDock

**FileDock** is a local‑first browser extension that acts as your central hub for downloading, converting, and recording. It’s designed to be fast, user‑friendly, and privacy‑focused — everything runs on your device with no cloud dependencies.

---

## ✨ Features

### 🔽 Downloader
- Download videos (MP4, AVI, MKV, FLV, etc.)
- Download audio/music (MP3, AAC, WAV, FLAC, etc.)
- Download images (JPG, PNG, GIF, BMP, etc.)
- Download documents (PDF, DOCX, TXT, etc.)
- Pause, resume, and retry downloads
- Playlist support and metadata fetching
- Smart scheduling (manage concurrency without throttling)

### 🔄 Converter
- Convert between video, audio, image, and document formats using **FFmpeg WASM**
- Compress files for easier sharing
- Merge multiple PDFs into one
- **Quick Convert presets** (e.g., “Convert to MP4”, “Compress for Sharing”)
- **Dual Modes**:
  - *Simple Mode*: one‑click conversions
  - *Advanced Mode*: full codec/resolution/bitrate controls
- Background conversion so you can keep browsing
- Tooltips and presets instead of raw technical jargon

### 🎥 Recorder
- Record browser screen or tab using **MediaRecorder API**
- Capture with or without audio (microphone/system)
- Save recordings locally as MP4/WebM
- Background recording supported

### 🗂 Organizer
- Auto‑sort files into folders (Videos, Music, Images, Docs)
- Local history stored in **IndexedDB**
- Re‑convert or re‑download past files directly from history

---

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3, Tailwind/Shadcn UI
- **Logic:** JavaScript/TypeScript
- **Processing:** FFmpeg WASM, MediaRecorder API
- **Storage:** IndexedDB + File System Access API
- **State Management:** Zustand
- **Icons:** Lucide React

---

## 📥 Installation

Clone the repo:
```bash
git clone https://github.com/HWMeTM/File-Dock.git
cd File-Dock
