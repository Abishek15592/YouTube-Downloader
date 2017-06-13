# YouTube Downloader

_Yet another tool to download youtube videos (and more, coming soon)._
 
## Description

Download videos from Youtube using this simple tool, right from the command line. Supports downloading multiple videos.

Contributions are welcome :)


## Installation
There is no stable version at the moment.
```
cd folder_name
git clone https://github.com/Amal-RX/youtube-downloader.git
cd youtube-downloader
python3 ytdl.py
```

## Usage
```
usage: main.py [-h] [-m] [-o OUTPUT] type url

positional arguments:
  type                   single/multple/playlist/profile
  url                    link to the original video on YouTube, or 
                         complete path to the text file

optional arguments:
  -h, --help             show this message and exit
  -m, --maxquality       download video(s) in the best quality available
  -a, --audio            audio only mode
  -o OUTPUT, --output OUTPUT
                         download location
```


## Requirements
* Python 3x
* pafy

## Version and Status

`Version 0.3.0`

**Status**: Work in progress.


## License
`MIT License`

