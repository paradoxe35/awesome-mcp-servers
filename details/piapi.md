# PiAPI MCP Server

[PiAPI MCP Server Documentation](https://piapi.ai/docs/mcp-server)

## Overview
PiAPI MCP Server is a TypeScript implementation of a Model Context Protocol (MCP) server that integrates with PiAPI's API. It enables users to generate various types of media content (images, videos, music, 3D models, etc.) using tools like Midjourney, Flux, Kling, LumaLabs, Udio, Wanx, Trellis, and more, directly from Claude or any other MCP-compatible application.

## Features
- **Base Toolkits**
  - Base Image toolkit
  - Base Video toolkit
- **Image Generation**
  - Flux: generate images from text or image prompts, supports LoRA and ControlNet
  - Midjourney: imagine, upscale, variation, reroll, describe, seed, blend, inpaint, outpaint, pan
- **Video Generation**
  - Hunyuan: generate videos from text/image prompts
  - Kling: video and effects generation, motion brush, lipsync, virtual try-on
  - Luma Dream Machine: video generation
  - Skyreels: video generation from image prompts
  - Wan: video generation from text/image prompts
- **Music and Audio Generation**
  - MMAudio: music generation from video
  - Udio: music and lyrics generation, song extension
  - DiffRhythm: audio generation
  - TTS: zero-shot text-to-speech (F5-TTS)
- **3D Model Generation**
  - Trellis: 3D model generation from images
- **Face Swap**
  - Image faceswap
  - Video faceswap
  - Multi-face swap
- **Image & Video Processing Tools**
  - Video upscale
  - Remove background
  - Image super resolution (upscale)
  - Segmentation with prompt
- **API & Development Tools**
  - Unified API schema
  - Webhook support
  - Bulk generation service
  - File upload API
  - Output storage
  - Task management (get, create, cancel, track)
- **Workflow Planning**
  - Inside LLMs (e.g., Claude)
- **MCP Inspector** (development tool)
  - Interactive testing via web interface
  - Real-time feedback and error reporting
  - Request/response inspection
  - Browse available functions and parameters
  - Custom timeout and configuration options
  - History tracking of function calls

## Integration
- Direct integration with Claude Desktop and Cursor editor via MCP protocol.
- Configuration via JSON files and environment variables.
- Node.js based, requires Node.js 16.x or higher.

## Prerequisites
- Node.js 16.x or higher
- npm or yarn
- PiAPI API key

## Installation & Usage
- Clone the repository, install dependencies, build the project.
- Configure with Claude Desktop or Cursor as described in the documentation.
- Use MCP Inspector for development and debugging.

## Pricing
- A pricing update is referenced for January 1st, 2025, but specific plan/pricing details are not provided in the available content.

## Category
- Media Processing MCP Servers

## Tags
- media-generation, image-generation, ai-integration, mcp, open-source
