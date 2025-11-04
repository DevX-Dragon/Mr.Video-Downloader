# **Mr. Video Downloader**

## 🚀 **Overview**

This is the source code repository for Mr. Video Downloader, a user-friendly Graphical Interface (GUI) built with Python and Tkinter. This application acts as a front-end wrapper for the powerful command-line tool, yt-dlp, making it simple and intuitive to download videos by URL.

## ✨ Key Features

GUI Interface: Easy-to-use desktop application built with Tkinter.
Fully Bundled (in Releases): The compiled Windows executable (found in the Releases section) includes the yt-dlp core utility.
Quality Analysis: Analyze video URLs to fetch a full list of available formats and quality options.
Real-time Progress: Track your downloads with a responsive progress bar.

## 💻 Local Setup (Running from Source)

If you wish to run the application directly from the source code, you must have Python installed and install the required dependencies.
Prerequisites

- Python 3.x
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) (The core video downloader utility)

Installation Steps

Clone the Repository:
```cmd
git clone [https://github.com/DevX-Dragon/Mr.Video-Downloader.git](https://github.com/DevX-Dragon/Mr.Video-Downloader.git)
cd Mr.Video-Downloader
```

Install yt-dlp:
```python
pip install yt-dlp
```
(Note: If you run into issues, ensure yt-dlp is installed and accessible in your system's PATH.)

Run the Application:
```python
python your_script_name.py
```

## 📝 How to Use the Application

Once the application is running (either from source or via the standalone EXE):

Analyze: Paste a video URL into the input field and click "Analyze" to fetch available quality options.

Select: Choose your desired video format/quality from the dropdown menu.

Download: Click "Start Download".

The application will automatically create a downloads folder next to the executable/script to save your videos.

🚀 Standalone EXE (For End Users)

For the easiest experience, end-users should download the compiled, self-contained Windows executable from the Releases page. No external dependencies are required for the EXE version.

Quick Start

Download: Get the Mr. Video Downloader.exe from the [Releases](https://github.com/DevX-Dragon/Mr.Video-Downloader/releases/tag/Windows) section.

Run: Double-click the EXE file to start the application immediately.

Use: Follow the simple steps outlined in the How to Use the Application section above.

## ⚖️ License and Usage

This project is open-source and released under the MIT License.

Private Use: You are free to use this application for personal, private purposes.

Attribution Required: If you redistribute, modify, or use this source code in any way, you must include clear attribution to the original author (DevX-Dragon) and link back to this repository.

No Rebranding: You may not distribute the application and claim it as your own original product. All derivative works must clearly distinguish themselves from the "Mr. Video Downloader" name and branding.
