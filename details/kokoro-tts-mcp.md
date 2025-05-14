# Kokoro TTS MCP

**Category:** Media Processing MCP Servers  
**Tags:** mcp, text-to-speech, media-processing, open-source  
**Source:** [GitHub Repository](https://github.com/mberg/kokoro-tts-mcp)

---

## Description
Kokoro TTS MCP is an open-source MCP server that uses Kokoro TTS models to convert text to speech, generating MP3 files with optional integration for uploading to Amazon S3 storage. It is designed to be configurable and can be run locally with support for multiple voices, languages, and speeds.

---

## Features
- Converts text to speech using Kokoro TTS models
- Outputs audio as MP3 files
- Optionally uploads generated MP3 files to AWS S3
- Supports configuration of:
  - Default voice (TTS_VOICE)
  - Speech speed (TTS_SPEED)
  - Language (TTS_LANGUAGE)
  - AWS S3 credentials, region, folder, and custom endpoint
  - Local MP3 storage folder (MP3_FOLDER)
  - MP3 file retention period (MP3_RETENTION_DAYS)
  - Automatic deletion of local files after S3 upload
  - Server host and port
  - Debug mode
- Includes a command-line client to send TTS requests to the server (`mcp_client.py`)
- Client supports:
  - Sending text directly or reading from a file
  - Customizing voice and speed per request
  - Disabling S3 upload per request
- Automatic cleanup of old MP3 files
- Requires ffmpeg for audio format conversion (wav to mp3)
- Open-source (Apache-2.0 license)

---

## Pricing
No pricing information is provided. The project is open-source and available under the Apache-2.0 license.

---

## Usage
- Clone the repository
- Download required Kokoro ONNX weights
- Configure environment variables as needed
- Install ffmpeg for audio conversion
- Run the server using `uv run mcp-tts.py`
- Use the provided client script to interact with the server

Refer to the [GitHub repository](https://github.com/mberg/kokoro-tts-mcp) for detailed setup and configuration instructions.