# Flowise

Integrates Flowise chatflows and assistants with the Model Context Protocol (MCP), enabling seamless integration of AI-powered conversational interfaces into systems compatible with MCP.

## Features
- Implements an MCP server in Python for integration with the Flowise API.
- Allows listing of available chatflows and assistants.
- Supports creation of predictions (interactions) via chatflows.
- Dynamically registers tools for Flowise chatflows or assistants.
- Two operation modes:
  - **FastMCP Mode (Simple Mode):** Enabled with `FLOWISE_SIMPLE_MODE=true`, provides a simplified integration.
  - **LowLevel Mode:** Default mode with more granular control and extended features.
- Supports filtering of accessible chatflows using environment variables (whitelists and blacklists).
- Can be installed and run via Smithery or directly using `uvx`.
- Provides detailed configuration options for integration into a larger MCP ecosystem (e.g., mcpServers configuration).
- Windows compatibility with specific configuration guidelines.

## Pricing
- Open-source and licensed under the MIT License. No pricing plans are mentioned.