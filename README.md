Mr. Video Downloader

A simple, user-friendly desktop application (GUI) built with Python and Tkinter for downloading videos from various online sources using the powerful yt-dlp utility.

The application allows users to analyze a video URL, select the desired format and quality, and track the download progress in real-time.

✨ Features

Single-File Download: The application is distributed as a single executable (EXE) for Windows, containing all necessary dependencies, including yt-dlp.

Format Analysis: Automatically analyzes video URLs and presents a list of available quality and format options.

Progress Bar: Real-time progress tracking of the download process.

Custom Directory: Easy selection of the download destination folder.

🚀 Getting Started (Using the Release EXE)

This is the fastest way to use the application, as it requires no external installation of Python or dependencies.

1. Download

Navigate to the Releases page of this repository.

Download the latest release file, typically named Mr. Video Downloader.exe.

2. Run

Simply double-click the Mr. Video Downloader.exe file.

Note: The application will create a folder named downloads in the same directory where the EXE is located to use as the default save location.

💻 Running from Source / Development

If you wish to modify the code, build the application yourself, or run it on a non-Windows environment, follow these steps.

1. Prerequisites

You must have Python 3.x installed.

2. Setup

Install the necessary Python package (yt-dlp is required for execution, though it is usually included in the system PATH or the compiled executable):

pip install yt-dlp


3. Execution

You can run the script directly using Python:

python your_script_name.py


(Replace your_script_name.py with the actual name of the file)

4. Compiling the Standalone EXE

To rebuild the single-file executable, you will need PyInstaller. This process automatically embeds the yt-dlp.exe binary into your final application.

Install PyInstaller

pip install pyinstaller


The Build Command

Ensure you have the latest yt-dlp.exe binary in the same folder as your Python script. Then, run the following command:

pyinstaller --onefile --windowed --add-data "yt-dlp.exe:." your_script_name.py


The --onefile flag creates a single EXE.

The --windowed flag prevents a console window from opening.

The --add-data "yt-dlp.exe:." flag is crucial—it embeds the external yt-dlp.exe binary so the app can run it via subprocess.

The final Mr. Video Downloader.exe will be located in the dist/ folder.

🤝 Credits

Developer: Mr.Video (DevX-Dragon)

Core Technology: This application is built around the excellent yt-dlp project.
