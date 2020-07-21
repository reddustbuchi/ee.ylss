# ee.ylss
ee.ylss - YouTube Live Stream Saver. This console app can download and save required previous part of any YouTube live stream

[>> download version 20.073](https://github.com/rytsikau/ee.ylss/raw/master/ee.ylss_20.073.7z)

## Program screenshot
<img src="https://raw.githubusercontent.com/rytsikau/ee.ylss/master/ee.ylss_20.073_screenshot.png">

## Quick Start
1. Unzip [this](https://github.com/rytsikau/ee.ylss/raw/master/ffmpeg.7z) file, and put *ffmpeg.exe* to the folder with *ee.ylss.exe*
2. Open *ee.ylss.ini* file in a text editor, and fill it in according to an existing sample. Minimum required information - YouTube stream URL and at least one time interval
3. After the ini file is saved, run *ee.ylss.exe*

## Requirements
* Windows 7+ or Windows Server 2012 R2+
* Google Chrome 60+
* FFmpeg executable library

## Tested Configuration
* Microsoft Windows 10 Pro x64 build 1903
* Google Chrome 62 x86 (portable)
* Google Chrome 83 x64 (installed)
* FFmpeg 4.3 x86 ([Zeranoe static build](https://ffmpeg.zeranoe.com/builds))

## Usage information
* Ini-file can be specified as argument when starting the program:
```
"c:\path\to\ee.ylss.exe" "c:\path\to\optional\file.ini"
```
* Number of intervals is limited to 10
* Maximum interval length is limited to 60 minutes
* Stream is saved with maximum available quality
* The live stream interruptions can lead to a shift in the estimated time. For example, if the stream was interrupted for 1 hour, in this case 12-hour-old frames will be displayed as 11-hour-old

## Developer information
* C#
* .NET Core 3.1
* Visual Studio Community 2019

## Tags
livestream stream youtube youtube-download youtube-downloader youtube-downloader-app youtube-live-stream youtube-livestream youtube-livestreams youtube-saver youtube-stream

## Author
[(c) Yauheni Rytsikau, 2020](mailto:y.rytsikau@gmail.com)

---
[[program page]](https://rytsikau.github.io/ee.ylss) [[start page]](https://rytsikau.github.io)
