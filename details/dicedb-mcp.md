# dicedb-mcp

**Category:** database-messaging-mcp-servers  
**Tags:** mcp, database, key-value, ai-integration

## Description

dicedb-mcp is a Model Context Protocol (MCP) server implementation designed to enable AI applications to interact with DiceDB database servers for key-value operations. It acts as a middleware, allowing hosts or clients (such as AI agents) to access DiceDB without needing direct database credentials or managing connections. It utilizes the DiceDB Go SDK for communication with DiceDB servers.

## Features

- **MCP Server for DiceDB:** Allows AI applications to interact with DiceDB using the MCP protocol.
- **Key-Value Operations:** Supports standard key-value database operations:
  - `ping`: Check connectivity to a DiceDB server.
  - `echo`: Echo a message through the DiceDB server.
  - `get`: Retrieve a value from DiceDB by key.
  - `set`: Set a key-value pair in DiceDB.
  - `del`: Delete one or more keys from DiceDB.
  - `incr`: Increment the integer value of a key by one.
  - `decr`: Decrement the integer value of a key by one.
- **Integration with AI SDKs:** Can be used with Claude Desktop, Cursor, OpenAI Agents SDK, and other MCP-compatible clients.
- **Multiple Installation Options:**
  - Download binaries for various platforms.
  - Install via Go.
  - Build from source.
- **Open Source:** Licensed under the MIT license.

## Pricing

No pricing information is provided. dicedb-mcp is open source and available under the MIT license.

## Source

[GitHub Repository](https://github.com/pottekkat/dicedb-mcp)
