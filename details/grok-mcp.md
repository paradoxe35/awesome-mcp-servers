# Grok Mcp

A server connecting to the xAI/Grok image generation API, enabling text-to-image creation and integration into creative workflows. It acts as a representative MCP (Media Control Protocol) server for generative AI tasks.

**Source:** [https://github.com/8bitsats/grok-mcp](https://github.com/8bitsats/grok-mcp)

## Features
- Connects to xAI/Grok image generation API
- Text analysis using Grok-2
- Image analysis using Grok Vision
- Simple REST API interface
- Built-in error handling and validation
- Lazy API key initialization (server can start without an API key set, can be provided at runtime)
- Supports generating multiple images per request (up to 10)
- Supports different response formats (URL or base64-encoded JSON)
- Docker support (includes Dockerfile for containerization, supports environment variable configuration for API key, efficient build caching)
- MCP tools:
  - `generate_image`: Generate images using Grok-2-image model
  - `set_api_key`: Set the xAI API key at runtime if not provided via environment variable

## Category
media-processing-mcp-servers

## Tags
image-generation, generative-ai, mcp, creative, api-integration

## Pricing
No pricing information is provided.