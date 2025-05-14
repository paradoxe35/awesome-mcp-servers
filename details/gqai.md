# gqai

[Source Code](https://github.com/fotoetienne/gqai)

## Category
Development Tools / MCP Servers

## Description
**gqai** is a lightweight proxy that exposes GraphQL operations as Model Context Protocol (MCP) tools for AI systems like Claude, Cursor, and ChatGPT. It enables users to define tools using standard GraphQL queries and mutations against a live GraphQL backend, and automatically generates an MCP server for those tools, facilitating seamless integration between GraphQL and MCP-compatible AI models.

## Features
- **GraphQL to MCP Tool Conversion:** Automatically turns GraphQL queries/mutations into MCP tools accessible by AI models.
- **No Code Required:** Define tools using regular GraphQL operations; no additional coding or infrastructure needed.
- **Live Backend Integration:** Connects directly to live GraphQL endpoints (does not support static schema files).
- **Configuration via YAML:** Uses `.graphqlrc.yml` for specifying GraphQL schema endpoints, operations, and headers.
- **Automatic Operation Discovery:** Scans specified directories for `.graphql` files and exposes them as tools.
- **Custom Headers Support:** Allows sending custom headers (e.g., for authentication) with each request to the GraphQL backend.
- **CLI Testing:** Provides a command-line interface to test tools and pass arguments to operations.
- **MCP Configuration:** Supports integration with MCP tools such as Claude Desktop via `mcp.json` configuration.
- **Open Source:** Released under the MIT license.
- **Lightweight Proxy:** Minimal overhead, designed to be easy to set up and run.

## Pricing
- **Open Source (MIT License):** Free to use, modify, and distribute.

## Tags
mcp, graphql, automation, open-source