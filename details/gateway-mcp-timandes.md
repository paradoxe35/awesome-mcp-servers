# gateway-mcp-timandes

**Category:** mcp-middleware-orchestration  
**Tags:** mcp, api-integration, gateway, tool-discovery

## Description

gateway-mcp-timandes is a server that translates Model Context Protocol (MCP) tool calls into traditional HTTP API requests. It enables the integration of existing HTTP APIs into MCP environments via configurable mappings.

[Source Code on GitHub](https://github.com/Timandes/mcp-gateway)

## Features

- **Translates MCP tool calls to HTTP API requests:** Acts as a gateway to bridge MCP tool calls with traditional HTTP APIs.
- **Configurable Mappings:** Uses a YAML configuration file to map MCP tools to HTTP API endpoints, including specifying arguments, request/response templates, and headers.
- **Flexible Server Control:**
  - Change server port using a command-line parameter (`--port=<port_no>`).
  - Supports different transport types, including SSE (default) and stdio (`--transport=stdio`).
- **Tool Mapping:**
  - Define multiple tools with names, descriptions, and argument specifications for LLM (Large Language Model) usage.
  - Each tool specifies:
    - Arguments (with name, description, and requirement status)
    - Request templates (HTTP method, URL, headers)
    - Response templates (body mapping)
- **Dynamic Configuration:**
  - Server section for basic gateway server information and key/value configs.
  - Tools section for mapping MCP tool calls to HTTP requests.
- **Integration with Other Tools:** Can be configured for use with environments like Cursor, Cline, or MCP Inspector.
- **Open Source:** Contributions are welcomed.

## Pricing

No pricing information provided. The project appears to be open-source.

## Links

- [GitHub Repository](https://github.com/Timandes/mcp-gateway)