# replicate-flux-mcp

An advanced Model Context Protocol (MCP) server that enables AI assistants to generate high-quality images and SVG vector graphics using Replicate's API. It integrates Black Forest Labs' Flux Schnell model for raster images and Recraft's V3 SVG model for vector graphics, streamlining visual asset creation for developers and designers.

## Features
- **Image Generation:** Generate high-quality raster images from text prompts using the Flux Schnell model.
- **Batch Image Generation:** Generate multiple images at once from an array of prompts.
- **Image Variants:** Generate multiple variants of a single image from a single prompt (useful for exploring different interpretations or styles).
- **SVG Generation:** Generate SVG vector images from text prompts using the Recraft V3 SVG model.
- **Prediction Management:**
  - Retrieve a list of recent predictions.
  - Get detailed information about specific predictions.
- **Image and SVG History:**
  - Browse history of generated images (imagelist).
  - Browse history of generated SVGs (svglist).
  - Browse all Replicate prediction history (predictionlist).
- **Integration Options:**
  - Available as a hosted service on Smithery and Glama.ai (no local setup required).
  - Supports integration with various AI assistants and tools (e.g., Cursor, Claude Desktop, Smithery, Glama.ai).
- **Configurable Server:** Server configuration is available by editing the config file, allowing customization for different environments.
- **API Token Authentication:** Requires Replicate API token for authentication.
- **Open Source and Extensible:** Licensed under MIT, contributions welcome.

## Pricing
No pricing information is provided in the available content. The project is open source and available for self-hosting. Hosted integration options (Smithery, Glama.ai) may have their own pricing—refer to their respective documentation for details.

## Links
- [Source Code](https://github.com/awkoy/replicate-flux-mcp)
