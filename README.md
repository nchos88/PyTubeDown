<h1 align="center">
	<br>
	<img src="https://raw.githubusercontent.com/ProHackTech/PyTubeDown/master/logo.png" alt="PyTubeDown Logo" width="450" height="250">
	<br>
	PyTubeDown
</h1>

<h3 align="center">
	Download YouTube videos & playlists using Python
</h3>

## Features
- [+] Multithreaded downloads
- [+] Download playlist
- [+] Download using video URL
- [+] Download using one keyword
- [+] Download using multiple keywords

## Requirements

### System
- Tested on Windows
- Python 3
- Selenium - Firefox gecko driver

## Usage

### Help Menu
`python3 down.py -h` or `python3 down.py --help`

### Commands

- **-t/--topic** = Download videos using query/topic
- **-scrl/--scroll** = Page scroll height for loading more videos
- **-upd/--update** = Update the script
- **-pl/--playlist** = Download playlist
- **-l/--link** = Download single video

### Examples

**Single video download**: `down.py -l "Video Url Here"`

**One Query/Word**: `down.py -t singleWord -scrl 2000`

**Multiple Search Query/Words**: `down.py -t "Multiple Words Here" -scrl 2000`

**Playlist Download**: `down.py -pl "Playlist Link Here"`

**Update script**: `down.py -upd`

## Contributions
Any code improvements, suggestions, issues and feature improvements are appreciated!
