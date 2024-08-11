# TikTok Video Manager + YouTube Uploader API V3 or Classic Upload

TikTok Video Manager is a Python-based tool that allows users to search, download, and manipulate TikTok videos. It provides functionalities such as adding text overlays, extracting audio, and adding background music to videos, youtube upload videos.

:money_with_wings: **Note:** Our project is a paid service. If you are interested in purchasing, please contact us at [tylngkhn@gmail.com](mailto:tylngkhn@gmail.com) for more details. :email:

⚠️ 12. YouTube Uploader (Classic) (NEW) added! ⚠️


![TIKTOKVIDEOMANAGER](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3oxdTVoMTYwbWtvZWhqZHZtanc4M3djY3RzYmdxamphNThncjN3NiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/gD7oLtEq0F4p9L0A6h/giphy.gif)

![Tiktok Manager Image](https://github.com/gkhantyln/TikTokVideoManager/blob/main/screen_menu.png)


## Features

- Search TikTok videos based on keywords, date, and category
- Download TikTok videos
- MP4 video trimming Short ```(NEW)```
- Add text overlays to videos with customizable fonts, colors, and positions
- Extract audio from videos
- Add background music to videos
- Save and load settings for text overlays
- Save and load video links
- YouTube Uploader API V3 ```(NEW)```
- YouTube Uploader Classic ```(NEW)```

## MP4 Video Trimming Features
- Precise Clipping: Trim specific segments of MP4 videos with high precision by defining exact start and end times.
- Flexible Input: Accepts user-defined start and end times, allowing for tailored video edits.
- Output Options: Save the trimmed video to a user-specified file path in MP4 format.
- Audio Extraction: Optionally extract audio from the trimmed video and save it as an MP3 file.
- Easy Integration: Simple interface for incorporating video trimming into larger workflows or applications.

## For the YouTube uploader:
-Prompt the user for the MP4 file path.
-Ask for the title, description, and hashtags.
-Request the date and time information for scheduled publishing.


## Requirements

- Python 3.7+
- Required Python packages (install using `pip install -r requirements.txt`):
  - tiktok_API (custom module)
  - yt-dlp
  - opencv-python
  - Pillow
  - moviepy
  - numpy
  - ffmpeg
  - playwright  `(NEW)` for classic upload youtube --headless or not 

## Requirements Youtube Api
- google-auth
- google-auth-oauthlib
- google-auth-httplib2
- google-api-python-client

## INSTALL Library
```pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client```

## Installation

1. Clone this repository: 
```git clone https://github.com/gkhantyln/TikTokVideoManager.git```
2. Navigate to the project directory:
```cd TikTokVideoManager```
3. Install the required packages:
```pip install -r requirements.txt```


## Usage
Run the main script: `python main.py`

Follow the on-screen prompts to use various features of the TikTok Video Manager.

![Tiktok Manager Image](https://github.com/gkhantyln/TikTokVideoManager/blob/main/screen2.png)

## Menu Options

1. Search TikTok Videos
2. Download TikTok Video
3. MP4 video trimming Short  `NEW`
4. Add Text to Video
5. Add Music to Video
6. Extract Audio from Video
7. Save Settings
8. Load Settings
9. Save Links
10. Load Links
11. YouTube Uploader API V3 `(NEW)`
12. YouTube Uploader (Classic) `(NEW)`
13. Exit

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

:money_with_wings: **Note:** Our project is a paid service. If you are interested in purchasing, please contact us for more details. :email:


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
