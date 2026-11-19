<div align="center">

# 🎬 ShortCliper2 — Stream Clipper Tool

**Turn long-form stream VODs into ready-to-post YouTube Shorts with automated Whisper subtitles in seconds.**

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FFmpeg](https://img.shields.io/badge/FFmpeg-Required-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)](https://ffmpeg.org/)
[![OpenAI Whisper](https://img.shields.io/badge/OpenAI-Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)](https://github.com/openai/whisper)

[⬇️ Download Latest Release](../../releases/latest) • [🛠️ Prerequisites](#1-prerequisites) • [⚙️ Setup](#2-one-time-setup) • [🚀 Usage](#3-how-to-make-a-clip)

</div>

---

## 📦 Download & Extract

1. Click **[Releases](../../releases)** on the right sidebar of this GitHub page (or use the download link above).
2. Under **Assets**, click the `.zip` archive to download the tool.
3. Extract the `.zip` folder anywhere on your computer.

---

## 1. Prerequisites

Install these two free tools on your computer before running the script:

| Requirement | Installation | Important Notes |
| :--- | :--- | :--- |
| **Python** | Download from [python.org](https://www.python.org/) | ⚠️ **Windows:** Check **"Add Python to PATH"** during installation. |
| **FFmpeg** | **Windows:** `winget install Gyan.FFmpeg`<br>**Mac:** `brew install ffmpeg` | Restart your terminal after installing so the command is recognized. |

---

## 2. One-Time Setup

1. Open your terminal or Command Prompt inside the extracted folder.
2. Run this command to install the OpenAI Whisper subtitle dependencies:
   ```bash
   pip install -r requirements.txt
