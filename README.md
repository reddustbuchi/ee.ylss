# ee.ylss
*ee.ylss* (Youtube Live Stream Saver) is a console utility to download the specified time interval of any YouTube livestream - even if it was hours ago. This is not a "current time" recorder - with *ee.ylss* you always have the DVR function, being able to "rewind" the livestream as many hours back as needed

### [>> download version 20.075](https://github.com/rytsikau/ee.ylss/raw/master/ee.ylss_20.075.zip)
  
## Program screenshot
<img src="https://raw.githubusercontent.com/rytsikau/ee.ylss/master/ee.ylss_screenshot.png">

## Quick Start
1. Unpack the downloaded archive
2. Open *ee.ylss.ini* in a text editor and fill in according to the existing sample. The minimum information required is the YouTube livestream URL and at least one time interval
3. Save the ini file and run *ee.ylss.exe*

## Usage information
* Ini file can be specified as an argument when starting the program:
```
"c:\path\to\ee.ylss.exe" "c:\path\to\alternative\file.ini"
```
* The number of intervals is limited to 10
* The maximum interval duration is limited to 60 minutes
* The stream is saved with the highest available resolution, but not higher than 1080p
* Time intervals are based on local computer time
* Live stream interruptions (streamer side) may cause a shift in estimated time. For example, if the stream was interrupted for 1 hour, then 12-hour frames will be displayed as 11-hour frames

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

## Developer information
* C#
* .NET Framework 4.0
* Visual Studio Community 2019

## Tags
youtube-dvr youtube-live youtube-live-stream youtube-live-stream-download youtube-live-stream-dvr youtube-live-stream-record youtube-live-stream-rewind youtube-live-stream-save youtube-livestream youtube-livestream-download youtube-livestream-dvr youtube-livestream-record youtube-livestream-rewind youtube-livestream-save youtube-record youtube-rewind youtube-stream

## Author
[(c) Yauheni Rytsikau, 2020](mailto:y.rytsikau@gmail.com)

---
[[program page]](https://rytsikau.github.io/ee.ylss) [[start page]](https://rytsikau.github.io)
