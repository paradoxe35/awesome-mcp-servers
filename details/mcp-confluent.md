# mcp-confluent

[MCP-Confluent on GitHub](https://github.com/confluentinc/mcp-confluent)

## Overview
**mcp-confluent** is an MCP server implementation that allows AI assistants and tools to interact with Confluent Cloud REST APIs, including management of Kafka topics, connectors, and Flink SQL statements via the MCP protocol. It is designed to integrate with MCP clients such as Claude Desktop and Goose CLI, enabling natural language management of Confluent resources.

## Features
- **MCP Protocol Server:** Implements the MCP protocol to bridge AI assistants and Confluent Cloud REST APIs.
- **Kafka Integration:** Manage Kafka clusters, topics, and configurations.
- **Connector Management:** Interact with and manage Confluent connectors.
- **Flink SQL Support:** Manage and execute Flink SQL statements in Confluent Cloud.
- **Schema Registry:** Access and manage data schemas via Confluent's Schema Registry.
- **Multiple Client Support:** Compatible with various MCP clients, including Claude Desktop and Goose CLI/Desktop.
- **Environment Configuration:** Uses environment variables for secure configuration of API keys, endpoints, and cluster details.
- **Session Persistence (Planned):** Support for conversation-based configuration for session persistence (future feature).
- **OpenAPI Spec:** Includes OpenAPI specification for Confluent Cloud.
- **Developer Friendly:** TypeScript codebase, supports Node.js, and provides a clear project structure and developer guide.
- **Testing Tools:** Supports interactive testing and debugging via MCP Inspector.

## Configuration
- Requires a .env file with environment variables such as Kafka and Flink API keys, cluster IDs, endpoints, and Schema Registry credentials.
- Can be run from source or via `npx`.
- Supports configuration for integration with Claude Desktop and Goose CLI.

## Usage
- Build and run the server using Node.js (npm install, npm run build/dev, npm run start).
- Configure your MCP client (Claude Desktop, Goose CLI) to connect to the running MCP-Confluent server.
- Use the client interface to manage Confluent Cloud resources through natural language or command-line interactions.

## Developer Guide
- Modular project structure with clear separation for Confluent integration and tool implementations.
- Guidelines for adding new tools, generating types from OpenAPI, and contributing.

## License
MIT License

## Pricing
No pricing information is provided. The project is open source and available under the MIT license.

## Tags
`mcp`, `kafka`, `messaging`, `confluent`, `cloud`