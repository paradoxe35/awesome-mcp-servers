# qiniu-mcp-server

A Model Control Protocol (MCP) server built on Qiniu Cloud products, enabling AI model clients to access Qiniu Cloud Storage and media processing services.

- **Source:** [GitHub Repository](https://github.com/qiniu/qiniu-mcp-server)
- **Category:** cloud-devops-mcp-servers
- **Tags:** mcp, qiniu, cloud, storage, media-processing

## Features

### Storage
- Retrieve list of Buckets.
- List files within a Bucket.
- Upload local files or file content.
- Read file content from storage.
- Generate and retrieve file download links.

### Intelligent Media Processing
- Image resizing.
- Apply rounded corners to images.

### CDN Operations
- Refresh CDN files by URL.
- Pre-fetch CDN files by URL.

### Integration & Configuration
- Built on Python 3.12+; uses the `uv` package manager for environment and dependency management.
- Supports configuration via environment variables for Qiniu access credentials, region, endpoint, and Bucket list (up to 20 Buckets recommended).
- Can be integrated with the Cline plugin in VSCode for interactive usage with AI models.
- Flexible server start modes: stdio (default), SSE (for web applications), with customizable port.

### Extensibility & Development
- Modular codebase allows extension by adding new business logic packages under the core directory.
- Supports custom resource and tool registration via Python modules.
- Provides example configurations and environment setup for local development.
- Includes instructions for testing with Model Control Protocol Inspector (requires Node.js v22.4.0).

## Installation & Usage

- Requires Python 3.12+ and the `uv` package manager.
- Clone the repository, create a virtual environment, install dependencies, and configure environment variables as described in the [README](https://github.com/qiniu/qiniu-mcp-server#readme).
- Example configuration for integration with Cline and AI chat clients is provided.

## Licensing

- Licensed under the MIT License.

## Pricing

- No pricing information is provided; the project is open source under MIT license.