# M3U8_Player

A simple web application that allows users to play videos from an M3U8 playlist. The player supports HLS (HTTP Live Streaming) and can dynamically load and play video files listed in an M3U8 playlist file.

## Features
* Load and parse M3U8 playlist files.
* Play selected videos from the playlist.
* Supports HLS streaming with fallback for browsers that support native HLS playback.
* Interactive playlist with video selection and active item highlighting.
## Requirements
* A modern web browser that supports HLS.js or native HLS playback.
## Installation

To use the Video Playlist Player, simply open the `m3u8_player.html` file in your web browser.

## Usage
1. Load an M3U8 Playlist:
   * Click the file input button (Choose File) to select an M3U8 playlist file from your local filesystem.
2. Play Videos:
   * Once the playlist is loaded, the videos will appear in the playlist section.
   * Click on any video item in the playlist to start playback.
## Dependencies
* HLS.js: Included via CDN for handling HLS streams.
## License

This project is licensed under the Unlicense - see the [LICENSE](LICENSE) file for details.
