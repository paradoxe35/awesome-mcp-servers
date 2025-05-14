# translated/lara-mcp

**MCP Server for Lara Translate API**

Lara Translate MCP Server is an open-source Model Context Protocol (MCP) server that provides language detection and context-aware translation capabilities by interfacing with the Lara Translate API. It enables AI applications to utilize advanced translation features via a standardized protocol.

- **Source:** [GitHub Repository](https://github.com/translated/lara-mcp)
- **Category:** ai-integration-mcp-servers
- **Tags:** mcp, translation, language-models, open-source

---

## Features

- **Language Detection:** Automatically detects the source language if not specified.
- **Context-Aware Translations:** Accepts contextual hints to improve translation quality.
- **Custom Instructions:** Allows fine-tuning of translation behavior with specific instructions (e.g., tone, formality).
- **Multi-Language Support:** Supports translation between numerous language pairs.
- **Structured Input/Output:** Maintains the structure of input text blocks in the translated output.
- **Flexible Installation:**
  - Docker image for containerized deployments.
  - NPX for quick usage with Node.js.
  - Build from source for development and customization.
- **API Credential Management:** Requires secure storage of Lara Translate API credentials.
- **MCP Integration:** Easily integrates with MCP-compatible AI applications, such as Claude Desktop.

### Available Tools
- **translate:**
  - Translates text between languages.
  - Supports language detection, contextual translation, custom instructions, and hints for language detection.
  - Input: Array of text blocks, source/target language codes, context, instructions, source hints.
  - Output: Translated text blocks matching the input structure.

---

## Installation & Setup

Three main installation options:
1. **Docker (recommended):** Run the server as a container with your API credentials.
2. **NPX:** Run directly using Node.js and NPX.
3. **Build from Source:** Clone the repository, install dependencies, and run the server manually. Optionally, build your own Docker image.

Configuration is done via the MCP configuration file of your AI application. Credentials for Lara Translate API are required.

---

## Usage Examples
- **Basic Translation:**
  - Provide source text, target language, and optional context.
- **With Instructions:**
  - Add custom instructions (e.g., "Use a formal tone") to control translation style.

---

## Licensing
- **MIT License**

---

## Pricing
- **Lara Translate MCP Server:** Open-source (MIT License)
- **Lara Translate API:** Requires a Lara account and subscription (free tier available for API credentials).