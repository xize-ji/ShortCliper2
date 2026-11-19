# Stream Clipper Tool

Here is your ready-to-use tool! Extract this ZIP folder to your computer.

## 1. Prerequisites
You need two free tools installed on your computer first:
1. **Python**: Download from python.org (Make sure to check "Add Python to PATH" during installation if you're on Windows).
2. **FFmpeg**: 
   - **Windows**: Open Command Prompt and type `winget install Gyan.FFmpeg`
   - **Mac**: Open Terminal and type `brew install ffmpeg`

## 2. One-Time Setup
1. Open your terminal or command prompt inside this extracted folder.
2. Run this command to install the OpenAI Whisper subtitle tool:
   `pip install -r requirements.txt`

## 3. How to Make a Clip!
1. Put your long stream video into this exact folder and rename it to `stream_vod.mp4`.
2. Open `make_short.py` in any text editor (like Notepad). Scroll to the very bottom and type in exactly what time you want the clip to start (`START_TIME`) and how long it should be (`DURATION`). 
3. Run the script:
   `python make_short.py`

Your final YouTube short will pop out in this folder as `youtube_short.mp4`!
"# ShortCliper2" 
