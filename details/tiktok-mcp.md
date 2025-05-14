# tiktok-mcp

**Category:** Media Processing MCP Servers  
**Tags:** tiktok, media-processing, ai-integration, mcp, open-source

[Source code on GitHub](https://github.com/Seym0n/tiktok-mcp)

## Description

tiktok-mcp is an open-source Model Context Protocol (MCP) server that integrates TikTok access into AI models (such as Claude AI) and other apps via TikNeuron. It enables programmatic analysis and retrieval of TikTok video content for media processing and AI integration use cases.

## Features

- **Analyze TikTok Videos for Virality:** Tools to assess TikTok videos and determine factors contributing to their virality.
- **Retrieve TikTok Video Content:** Programmatically fetch content and context from TikTok videos.
- **Chat with TikTok Videos:** Enables conversational interaction with TikTok video content.
- **Available Tools:**
  - **tiktok_available_subtitles:** Checks and retrieves available subtitles (in various formats/languages) for a TikTok video.
  - **tiktok_get_subtitle:** Fetches subtitles for a TikTok video, optionally in a specified language (e.g., English, Spanish, French).
  - **tiktok_get_post_details:** Retrieves video details such as description, creator username, hashtags, like/share/comment/view/bookmark counts, creation date, and duration.
- **Integration with Claude AI and TikNeuron:** Easily add TikTok MCP as a server in compatible AI environments.
- **Open Source:** Source code is available for customization and self-hosting.

## Requirements

- NodeJS v18 or higher
- Git
- TikNeuron Account and MCP API Key

## Setup

1. Clone the repository from GitHub.
2. Install dependencies via `npm install`.
3. Build the project with `npm run build`.
4. Configure your MCP servers to include tiktok-mcp, providing the TikNeuron MCP API Key.

## Pricing

No pricing information is provided; tiktok-mcp is open source, but a TikNeuron account (which may have its own pricing) is required for API access.
