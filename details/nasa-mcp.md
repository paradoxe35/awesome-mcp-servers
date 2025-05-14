# NASA-MCP

**Category:** Data Access Integration MCP Servers  
**Source:** [GitHub Repository](https://github.com/AnCode666/nasa-mcp)

## Description
NASA-MCP is an MCP (Model Context Protocol) server that allows language models and compatible clients to interact with a wide range of NASA APIs. It enables retrieval of astronomical data, space weather, Earth imagery, and more, facilitating AI-driven science and space exploration applications. The server is designed for integration with clients such as Claude AI, Cursor, CODEGPT, and others.

## Features
- **Integration with Multiple NASA APIs:**
  - Astronomy Picture of the Day (APOD): Retrieve daily astronomical images and explanations.
  - Asteroids NeoWs: Query data about Near Earth Objects and asteroid information.
  - DONKI (Space Weather Database): Access space weather data, including solar flares and geomagnetic storms.
  - Earth Imagery: Get Landsat 8 satellite images for specific coordinates.
  - EPIC (Earth Polychromatic Imaging Camera): Access full disk Earth images.
  - Exoplanet Archive: Query for information about exoplanets (planets outside our solar system).
- **Secure API Key Management:** Handles NASA API keys securely via environment variables.
- **Error Management:** Provides error handling for all API requests.
- **MCP Protocol Support:** Allows LLMs and clients to query NASA APIs via the MCP protocol.
- **Client Compatibility:** Can be integrated with Claude for Desktop, Cursor, CODEGPT, Roo Code, and other MCP-compatible clients.
- **Open Source:** MIT licensed and available for community contributions.
- **Easy Installation:** Supports installation via Smithery or the `uv` Python package manager.

## Installation
- Install via Smithery CLI or with `uv` (Python 3.10+ required).
- Requires a NASA API key (free from https://api.nasa.gov/).
- Integrate by configuring the MCP server block in your LLM client config.

## Usage Examples
- Retrieve today's astronomy picture of the day.
- Find asteroids passing near Earth in the next week.
- Get information about recent solar flares.
- Access Earth imagery for specific coordinates.
- Query exoplanets in the habitable zone.

## Pricing
- **Free and open source** (MIT License)
- NASA API keys are free for limited usage (see NASA API terms for quotas).

## Tags
`mcp` `nasa` `open-data` `api-integration`