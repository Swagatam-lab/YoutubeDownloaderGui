📄 README.md
markdown
Copy
Edit
# 🎬 YouTube Video & Audio Downloader (GUI with yt-dlp + Tkinter)

A simple yet powerful GUI tool to download YouTube videos or audio files using [`yt-dlp`](https://github.com/yt-dlp/yt-dlp) and Python's built-in `tkinter` library.

---

## 🧰 Features

✅ Paste YouTube URL directly  
✅ Choose download destination folder  
✅ Select video resolution (720p, 480p, 360p, Best)  
✅ Download audio-only in MP3 format  
✅ User-friendly GUI  
✅ Uses `yt-dlp` — actively maintained and robust

---

## 🖥️ Demo

![screenshot](screenshot.png) *(Add screenshot if available)*

---

## 📦 Requirements

- Python 3.7+
- `yt-dlp`
- `ffmpeg` (for audio conversion or merging video + audio)
- `tkinter` (comes preinstalled with most Python distributions)

### 🔧 Install Dependencies

```bash
pip install yt-dlp
🛠 Install FFmpeg
Windows

Download from: https://ffmpeg.org/download.html

Extract it and add the bin folder path to your system's PATH variable.

Linux (Debian/Ubuntu)

bash
Copy
Edit
sudo apt install ffmpeg
macOS (Homebrew)

bash
Copy
Edit
brew install ffmpeg
🚀 How to Run
bash
Copy
Edit
python yt_gui_downloader.py
📝 How It Works
Enter a valid YouTube video URL.

Click “Choose Download Folder” to select where the file will be saved.

Choose the desired quality:

Best: Best available resolution

720p, 480p, 360p: Specific resolutions

Audio Only: Extracts audio as MP3

Click “Download” — the video/audio will be downloaded and saved.

📂 Project Structure
graphql
Copy
Edit
yt_gui_downloader.py   # Main Python GUI script
README.md              # This file
screenshot.png         # (Optional) GUI screenshot
🚧 Known Limitations
No progress bar yet

No playlist support (but easily addable)

Doesn't auto-detect available resolutions (uses preset options)

💡 Future Ideas
Add progress bar

Support YouTube playlists

Add thumbnail preview

Resolution auto-detection dropdown

🙌 Credits
yt-dlp — the best YouTube downloader backend

Python's tkinter — for the simple GUI

📜 License
This project is free to use and modify. No warranties.
