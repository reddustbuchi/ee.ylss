# ee.ydv
This console application can download a required part of YouTube live stream while it's streaming

[>> download version 2007](https://github.com/rytsikau/ee.Ydv/raw/master/ee.ydv_2007.7z)

## Program screenshot
<img src="https://raw.githubusercontent.com/rytsikau/ee.Ydv/master/screenshot.png">

## Quick Start
1. Unzip [this](https://github.com/rytsikau/ee.Ydv/raw/master/ffmpeg.7z) file, and put *ffmpeg.exe* to the folder with *ee.ydv.exe*
2. Open *ee.ydv.ini* file in a text editor, and fill it in according to an existing sample. Minimum required information - YouTube video ID and at least one time interval
3. After the ini file is saved, run *ee.ydv.exe*

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
* Ini-file can be specified as the argument when starting the program:
```
"c:\path\to\ee.ydv.exe" "c:\path\to\optional\file.ini"
```
* Only the first 5 valid intervals will be downloaded
* Maximum interval length is limited to 15 minutes
* Video is downloaded with the HD quality (if possible)
* The live stream interruptions can lead to a shift in the estimated time. For example, if the stream was interrupted for 1 hour, in this case 12-hour-old frames will be displayed as 11-hour-old

## Developer information
* C#
* .NET Core 3.1
* Visual Studio Community 2019

## Author
[(c) 2020 Yauheni Rytsikau](mailto:y.rytsikau@gmail.com)

---
[rytsikau.github.io](https://rytsikau.github.io)
