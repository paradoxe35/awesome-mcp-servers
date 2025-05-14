# mcp-hfspace

MCP Server to access HuggingFace Spaces from Claude or other AI agents, supporting image, audio, and text uploads/downloads for versatile AI tasks.

**Source:** [GitHub - evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace)

## Features

- **Easy Integration with HuggingFace Spaces:** Connects Claude Desktop or other AI agents to any HuggingFace Space with minimal setup.
- **Media Handling:** Supports upload and download of images, audio, and text files.
- **Automatic Endpoint Configuration:** Automatically finds and configures the most appropriate endpoint for each HuggingFace Space provided.
- **Working Directory Management:** Allows setting a custom working directory for file uploads/downloads; supports both Windows and MacOS.
- **Support for Private Spaces:** Use HuggingFace tokens to access and interact with private Spaces.
- **Multiple Server Instances:** Can run multiple server instances with different working directories and tokens.
- **Claude Desktop Mode:** 
  - Images are returned in tool responses.
  - Other files are saved to the working directory, with file paths returned as messages.
  - Can be disabled to return files as embedded base64 resources.
- **URL Inputs:** Accepts URLs as inputs, passing content to the Space.
- **Available Resources Prompt:** Lists available files and mime types from the working directory to Claude.
- **API Endpoint Specification:** Allows specifying a specific API endpoint per Space if needed.
- **Recommended Spaces:** Pre-configured for image generation, chat, text-to-speech, speech-to-text, text-to-music, and vision tasks (with suggested HuggingFace Spaces).
- **Prompts Generation:** Generates prompts for each Space to facilitate interaction.
- **Resource Management:** Returns a list of files in the working directory for convenience.
- **Cross-Platform:** Works on Windows and MacOS.
- **MIT Licensed:** Open source under the MIT License.

### Example Use Cases
- Image generation and vision tasks (upload/download images for analysis or generation)
- Text-to-speech and speech-to-text (audio file handling)
- Chat and reasoning with advanced language models
- File management and resource sharing between Claude and HuggingFace Spaces

## Known Issues and Limitations
- Endpoints with unnamed parameters are not supported.
- Some complex Python types may not fully translate to MCP formats.
- Claude Desktop may have issues with error handling and timeouts for large jobs.
- HuggingFace ZeroGPU quotas may limit job runs; private Spaces recommended for production use.

## Pricing
No pricing information provided. The project is open source under the MIT license.
