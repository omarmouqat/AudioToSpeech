# 🎙️ Speech-to-Text API with Subtitles (Autosub + Flask)

This project is a simple Flask API that allows you to upload an audio file and receive subtitles as JSON using [autosub](https://github.com/agermanidis/autosub), a Python-based tool for automatic speech recognition.

---

## 🚀 Features

- Accepts audio file uploads (e.g., `.mp3`, `.wav`)
- Transcribes speech to subtitles using `autosub`
- Parses the generated `.srt` file and returns JSON output
- Supports multiple languages (default: English)

---

## 📦 Requirements

- Python 3.8+
- `ffmpeg` installed and accessible
- Internet connection (for `autosub` to use Google Web Speech API)

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/speech-to-text-api.git
cd speech-to-text-api
