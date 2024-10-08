---
uid: Strm-Files
title: STRM Files
legacyUrl: /support/solutions/articles/44001159147-strm-files
---

Various internet video and audio streams can be played back in Emby as if they were locally stored on your media center by using STRM files. As long as the format and streaming-method (network-protocol) is supported by Emby, the stream can be used. These are basic text files named to look like <name>.strm and contain a URL to the internet stream. This can also be used for locally stored and shared media where instead of a URL, the strm file contains the path to the media file.
 
### Usage

Create a normal text file and rename the .txt extension to .strm. Then open it up with a text-editor (like Notepad in Microsoft Windows) and input the the direct URL-link of the stream or path to the file if locally stored / shared.

This should look like:

```
http://host/path/stream
```

or 

```
mms://host/path/stream
```

or 

```
rtsp://host/path/stream
```

or

```
F:/Movies/Topgun (1986)/Topgun.mp4
```

or

```
\\EMBYSERVER\Movies\Topgun (1986)\Topgun.mp4
```


## Examples

An strm file as a movie:

```
\Movies
   \300 (2006)
      300 (2006).strm
```

Strm files can be used for any kind of video, such as movies, episodes, music videos, home videos, etc.

The naming convention of the .strm file name should follow the convention used for the associated content type (movies, episodes, etc).  Then just place the .strm file where you would as if it were a video file.

