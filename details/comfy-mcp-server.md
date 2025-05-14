# Comfy MCP Server

[Visit MCP](https://creati.ai/mcp/comfy-mcp-server/)

## Overview
Comfy MCP Server is a specialized server built using the FastMCP framework to automate image generation tasks. It interacts with a remote Comfy server, allowing users to submit text prompts and receive generated images through an API. The server is designed for developers, AI researchers, digital artists, and content creators who require scalable and efficient image creation workflows.

## Features
- Automates image generation from text prompts via API
- Integrates with remote Comfy server for high-quality image creation
- Supports custom workflows exported from Comfy UI (via JSON files)
- Environment variable configuration for server and workflow parameters (COMFY_URL, COMFY_WORKFLOW_JSON_FILE, PROMPT_NODE_ID, OUTPUT_NODE_ID, OUTPUT_MODE)
- Supports custom models, including those hosted on Ollama or local setups
- Batch processing: supports processing multiple prompts simultaneously
- Flexible prompt generation (supports both natural language and custom templates)
- Output configuration: images can be returned as URLs or files, depending on OUTPUT_MODE
- Compatible with Python 3.x, requires the `uv` package
- MIT License (open source, modifiable)
- Logging and monitoring via logs and activity feeds

## Use Cases
- Automated art and design creation
- Batch image generation for research projects
- AI-powered content creation workflows
- Integration into creative production pipelines

## How to Use
1. Install dependencies (Python 3.x, `uv` package)
2. Set required environment variables: COMFY_URL, COMFY_WORKFLOW_JSON_FILE, PROMPT_NODE_ID, OUTPUT_NODE_ID, OUTPUT_MODE
3. Export your workflow JSON file from Comfy UI
4. Run the server with `uvx comfy-mcp-server`
5. Submit prompts via API to generate and retrieve images

## Pricing
No pricing information provided. The server is open source under the MIT License.

## Tags
`generative-ai` `image-generation` `fastmcp` `automation`