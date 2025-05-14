# baseline-mcp-server

**Category:** data-access-integration-mcp-servers  
**Tags:** mcp, web, api-integration, reference-implementation

## Overview
baseline-mcp-server is a Model Context Protocol (MCP) server that provides Baseline status information for specific Web APIs using the Web Platform Dashboard API. It is designed to fit into the MCP server directory and be used as a reference implementation for accessing and searching Web Platform API support status.

## Features
- **Search Web Platform API Support:** Uses the Web Platform Dashboard API to retrieve support status for web APIs.
- **Baseline Status Reporting:** Provides Baseline status for features, categorized as:
  - `widely`: Widely supported web standard features.
  - `newly`: Newly standardized web features, beginning to be supported.
  - `limited`: Features with limited support or requiring flags in some browsers.
  - `no_data`: Features not included in Baseline; support needs to be checked individually.
- **Browser Implementation Information:** Reports browser version and implementation date for web features.
- **Usage Data:** Supplies usage data for web features where available.
- **MCP Integration:** Can be connected to various AI models and MCP clients (such as Claude Desktop or Visual Studio Code) for enhanced querying and automation.
- **Multiple Deployment Options:**
  - Run directly with Deno (recommended), using only network access to api.webstatus.dev.
  - Integrate with MCP clients by adjusting settings (examples provided for Claude Desktop and Visual Studio Code).
  - Deploy and run using Docker, with provided Dockerfile and usage instructions.
- **Open Source:** Licensed under the MIT License.

## Pricing
- The project is open source and available under the MIT License. There is no cost to use or deploy baseline-mcp-server.

## Source
[GitHub Repository](https://github.com/yamanoku/baseline-mcp-server)
