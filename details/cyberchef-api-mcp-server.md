# CyberChef API MCP Server

A server implementing the Model Context Protocol (MCP) to interface with the CyberChef Server API, enabling automated and programmatic access to CyberChef operations via MCP clients.

**Source:** [GitHub - slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server)

## Features

- **MCP Server for CyberChef:** Enables any LLM/MCP client to utilize CyberChef's tools and resources.
- **CyberChef Operations Categories:**
  - `get_cyberchef_operations_categories`: Retrieve updated CyberChef categories for context and operation selection.
  - `get_cyberchef_operation_by_category`: Retrieve a list of CyberChef operations for a selected category.
- **Recipe Execution:**
  - `bake_recipe`: Execute a sequence of CyberChef operations (a "recipe") on input data.
  - `batch_bake_recipe`: Execute a recipe on a batch of input data.
- **Magic Operation:**
  - `perform_magic_operation`: Automatically detect data encoding and suggest/perform appropriate decoding operations.
- **Environment Variable Configuration:**
  - Server requires the `CYBERCHEF_API_URL` environment variable to connect to a CyberChef API instance.
- **Client Configuration Support:**
  - Provides instructions and example JSON for configuring MCP clients to connect to the server.
- **Docker Support:**
  - Includes a Dockerfile for containerized deployment.
- **MIT Licensed**

## Usage

- Start the server using `uv run cyberchef_api_mcp_server` with the appropriate environment variable set.
- Development and testing supported via MCP inspector and CLI tools.
- Example configurations provided for client setup.

## Pricing

- **Free & Open Source** (MIT License)

## Tags

`cyberchef`, `api-integration`, `automation`, `mcp`