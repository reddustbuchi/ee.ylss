# ee.ylss
ee.ylss - YouTube LiveStream Saver. This console app can download and save required previous part of any YouTube live stream

[>> download version 20.074](https://github.com/rytsikau/ee.ylss/raw/master/ee.ylss_20.074.7z)

## Program screenshot
<img src="https://raw.githubusercontent.com/rytsikau/ee.ylss/master/ee.ylss_screenshot.png">

## Quick Start
1. Unzip [this](https://github.com/rytsikau/ee.ylss/raw/master/ffmpeg.7z) archive, and put *ffmpeg.exe* to the folder with *ee.ylss.exe*
2. Open *ee.ylss.ini* in a text editor, and fill it in according to an existing sample. Minimum required information - YouTube stream URL and at least one time interval
3. After the ini file is saved, run *ee.ylss.exe*

## Requirements
* FFmpeg executable library
* Google Chrome 60+
* Windows XP or later / Windows Server 2003 or later

## Tested Configuration
* FFmpeg 4.3 x86 ([Zeranoe static build](https://ffmpeg.zeranoe.com/builds))
* Google Chrome 62 x86 (portable)
* Google Chrome 83 x64 (installed)
* Microsoft Windows 10 Pro x32 version 1909
* Microsoft Windows 10 Pro x64 version 1903

## Usage information
* Ini-file can be specified as argument when starting the program:
```
"c:\path\to\ee.ylss.exe" "c:\path\to\optional\file.ini"
```
* Number of intervals is limited to 10
* Maximum interval length is limited to 60 minutes
* Stream is saved with maximum available quality
* Live stream interruptions (on the side of the streamer) can lead to a shift in the estimated time. For example, if the stream was interrupted for 1 hour, in this case 12-hour-old frames will be displayed as 11-hour-old

## Developer information
* C#
* .NET Framework 4.0
* Visual Studio Community 2019

## Tags
livestream stream youtube youtube-download youtube-downloader youtube-downloader-app youtube-live-stream youtube-livestream youtube-livestreams youtube-saver youtube-stream

## Author
[(c) Yauheni Rytsikau, 2020](mailto:y.rytsikau@gmail.com)

---
[[program page]](https://rytsikau.github.io/ee.ylss) [[start page]](https://rytsikau.github.io)
