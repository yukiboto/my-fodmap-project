# 🎬 DIY Video Compilation & Shortener Tool

Welcome to your offline video compiler and shortener! This tool is perfect for making highlight reels, removing padding from educational videos, or compiling saved videos (like workouts, recipes, or tutorials) in your library.

---

## 🚀 Quick Start Guide

### 1. Structure
Your project has the following folders:
- **`Diet/`**: This is your library folder (e.g., for diet, workout, or other categorised videos). Put any local `.mp4`, `.mkv`, or `.webm` files you want to use here!
- **`downloads_cache/`**: A folder where YouTube URLs will automatically be downloaded and cached. It is gitignored to keep your repository clean.
- **`Untitled-1.ipynb`**: Your interactive Jupyter Notebook containing the tool.

### 2. How to Use
1. Open the Jupyter Notebook `Untitled-1.ipynb` in VS Code.
2. Under the **CONFIGURATION** block (Cell 2):
   - Add your local files or YouTube URLs.
   - For each video, specify the exact parts (start/end times) you want to include.
3. Run all cells in the notebook!
4. The script will automatically download necessary assets, cut out the precise clips, and merge them all into a single **`short_compilation.mp4`** file.

---

## 💡 Pro Tips

### 🕒 Timestamp Formats Supported
You can write your start and end times in any of these formats:
- **`"HH:MM:SS"`** (e.g., `"01:15:30"` for 1 hour, 15 minutes, 30 seconds)
- **`"MM:SS"`** (e.g., `"02:45"` for 2 minutes, 45 seconds)
- **Raw seconds** (e.g., `165` or `165.5`)

### ⚡ Smart Download Caching
If you use a YouTube URL and run the compiler multiple times, **it will not download the video again**. It remembers the video and uses the cached file, saving you lots of time and internet data!

### 🔒 Git Friendly
We have pre-configured a `.gitignore` file so that your massive video downloads, cached files, and Python virtual environment are never committed to your Git repository, keeping it fast and lightweight.
