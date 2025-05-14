# Hfspace

**Category:** ai-integration-mcp-servers  
**Tags:** huggingface, ai-integration, image-generation, mcp, vision

## Description
Hfspace (mcp-hfspace) is a Model Context Protocol (MCP) server that bridges Claude Desktop with Hugging Face Spaces, allowing Claude to access a variety of AI capabilities available through Hugging Face with minimal configuration. It wraps Hugging Face Space endpoints as MCP tools and manages file operations, making advanced AI tasks such as image generation, vision processing, and text-to-speech accessible from Claude Desktop.

[Source & Documentation](https://deepwiki.com/evalstate/mcp-hfspace)

## Features
- **MCP Protocol Implementation:** Communicates with Claude Desktop using the Model Context Protocol.
- **Dynamic Endpoint Discovery:** Automatically discovers and wraps Gradio API endpoints from Hugging Face Spaces.
- **File Management:** Manages file storage, listing, reading, writing, and MIME type detection in a secure working directory.
- **Semantic Search:** Provides semantic search functionality to find relevant Hugging Face Spaces based on user queries.
- **Built-in Tools:**
  - `available-files`: Lists all files in the working directory with metadata, outputs as a markdown table.
  - `search-spaces`: Allows searching for relevant Hugging Face Spaces by query and returns formatted results.
  - `Available Resources` prompt: Displays available files and resources.
- **EndpointWrapper:** Bridges MCP tool calls to Gradio API calls and converts responses to MCP-compatible formats.
- **Operational Modes:**
  - Claude Desktop Mode: Optimized for Claude Desktop with direct image handling and file path returns for audio/files.
  - Standard Mode: Compatible with any MCP client, providing base64-encoded resources for all file types.
- **Supported Hugging Face Space Types:**
  - Image Generation (e.g., black-forest-labs/FLUX.1-schnell)
  - Vision Models (e.g., microsoft/OmniParser)
  - Text-to-Speech (e.g., styletts2/styletts2)
  - Speech-to-Text (e.g., hf-audio/whisper-large-v3-turbo)
  - Chat Models (e.g., Qwen/Qwen2.5-72B-Instruct)
- **Extensible Architecture:** Designed to demonstrate and support MCP server extensibility.

## Pricing
No pricing information provided.

## Source
[https://deepwiki.com/evalstate/mcp-hfspace](https://deepwiki.com/evalstate/mcp-hfspace)
