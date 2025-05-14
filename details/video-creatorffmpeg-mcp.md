# video-creator/ffmpeg-mcp

An open-source MCP server that utilizes ffmpeg to enable various multimedia operations through dialogue interfaces.

**Source:** [https://github.com/video-creator/ffmpeg-mcp.git](https://github.com/video-creator/ffmpeg-mcp.git)

## Features
- **Local Video Search:** Recursively search for video files in a directory by full or partial file name; returns full path.
- **Video Information Retrieval:** Obtain video metadata including duration, fps, codec, width, and height.
- **Video Clipping:** Trim videos by specifying file path, start time, end time or duration; returns the clipped file.
- **Video Concatenation:** Merge multiple videos into one; uses quick mode if all files have matching width, height, and frame rate.
- **Video Playback:** Play video or audio files with ffplay. Supports various formats (mov, mp4, avi, mkv, 3gp), adjustable speed, and loop count.
- **Video Overlay:** Overlay one video on top of another at specified position and offset (dx, dy).
- **Video Scaling:** Scale videos to specified width and height (with option to keep aspect ratio).
- **MCP Dialogue Integration:** All features accessible via MCP server dialogue commands.
- **Supported Platform:** macOS (ARM64 and x86_64 only).

## Installation
- Clone the repository: `git clone https://github.com/video-creator/ffmpeg-mcp.git`
- Enter the directory: `cd ffmpeg-mcp`
- Sync dependencies: `uv sync`

## License
MIT License

## Tags
`ffmpeg` `media-processing` `video-editing` `open-source`

## Pricing
- Open source, free to use under MIT license.
