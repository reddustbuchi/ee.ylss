# ee.ydv ("Youtube Deep Viewer")
This console application can download any part (interval) of any Youtube live stream between point at 7 days ago and current time.
<br><br>

## Quick Start
1. Unpack *ee.ydv_fullpack.zip*.
2. Open *ee.ydv.ini* file in a text editor, and fill it in according to an existing sample. Minimum required information - YouTube video ID and at least one interval.
3. After the ini file is saved, run *ee.ydv.exe*.
<br>

## Version
1.2 (20200706)<br>
<br>

## Requirements
* Windows 7+ or Windows Server 2012 R2+
* Google Chrome 60+
* FFmpeg executable library (*ee.ydv_fullpack.zip* contains [Zeranoe static build](https://ffmpeg.zeranoe.com/builds) version 4.3 x86)
<br>

## Tested Configuration
* Microsoft Windows 10 Pro x64 build 1903
* Google Chrome 62 x86 (portable)
* Google Chrome 83 x64 (installed)
* FFmpeg 4.3 x86
<br>

## Usage information
* Ini-file can be specified as the argument when starting the program:
```
"c:\path\to\ee.ydv.exe" "c:\path\to\optional\file.ini"
```
* Only the first 5 valid intervals specified in the ini-file will be downloaded
* Maximum interval length is limited to 15 minutes
* Video is downloaded with the HD quality (if possible)
* 168 past hours of live stream are usually available, regardless of how much is available in the web version in browser (12 hours, 4 or zero).
Also, sometimes video available between 168 and 169 hours ago, but at a very low download speed.
* The live stream interruptions can lead to a shift in the estimated time.
For example, if the broadcast was interrupted for 1 hour, in this case 24-hour-old frames will be displayed as 23-hour-old.
<br>

## Developer information
* C#
* .NET Core 3.1
* Visual Studio Community 2019 (Version 16.1.6)
<br>

## Author
* [**Yauheni Rytsikau (Eugen Rytikov)**](https://github.com/rytsikau)
<br>
