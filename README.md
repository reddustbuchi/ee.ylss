# ee.Ydv
This console application can download any part of YouTube live stream between point at 7 days ago and current time

[>> download version 1.2 (20200706)](https://github.com/rytsikau/ee.Ydv/archive/master.zip)

## Quick Start
1. Unzip files from *ee.ydv.7z* and *ffmpeg.7z* into one folder
2. Open *ee.ydv.ini* file in a text editor, and fill it in according to an existing sample. Minimum required information - YouTube video ID and at least one time interval
3. After the ini file is saved, run *ee.ydv.exe*

## Requirements
* Windows 7+ or Windows Server 2012 R2+
* Google Chrome 60+
* FFmpeg (file *ffmpeg.7z* contains [Zeranoe static build](https://ffmpeg.zeranoe.com/builds), version 4.3 x86)

## Tested Configuration
* Microsoft Windows 10 Pro x64 build 1903
* Google Chrome 62 x86 (portable)
* Google Chrome 83 x64 (installed)
* FFmpeg 4.3 x86

## Usage information
* Ini-file can be specified as the argument when starting the program:
```
"c:\path\to\ee.ydv.exe" "c:\path\to\optional\file.ini"
```
* Only the first 5 valid intervals will be downloaded
* Maximum interval length is limited to 15 minutes
* Video is downloaded with the HD quality (if possible)
* 168 past hours of live stream are usually available, regardless of how much is available in the web version in browser (12 hours, 4 or 0). Also, sometimes video available between 168 and 169 hours ago, but at a very low download speed
* The live stream interruptions can lead to a shift in the estimated time. For example, if the stream was interrupted for 1 hour, in this case 24-hour-old frames will be displayed as 23-hour-old

## Developer information
* C#
* .NET Core 3.1
* Visual Studio Community 2019

## Author
[(c) 2020 Yauheni Rytsikau](mailto:y.rytsikau@gmail.com)

---
[rytsikau.github.io](https://rytsikau.github.io)
