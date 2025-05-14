# flux-schnell-mcp

Bridges Claude with Replicate's flux-schnell image generation model, enabling direct image creation from text prompts within conversations through MCP.

## Features
- MCP (Model Context Protocol) server for image generation
- Integrates with Replicate API to use the Flux Schnell model
- Provides a `generate_image` tool callable via MCP
- Returns full Replicate API response including generated image URL and metadata
- Can be configured for use with Claude Desktop and VSCode Roo
- Supports debugging via MCP Inspector, which provides a browser-accessible debugging interface

## Requirements
- Replicate API Token

## Setup
- Install the server from the repository
- Configure connection details for Claude Desktop or VSCode Roo

## Usage
- Call the `generate_image` tool on the server using MCP with appropriate parameters
- Review image output and metadata provided in the response

## Pricing
_No pricing information available; open source repository_

## Source
[https://github.com/ckz/flux-schnell-mcp](https://github.com/ckz/flux-schnell-mcp)