# mcp-memgraph

[Source Code](https://github.com/memgraph/mcp-memgraph)

## Overview
Memgraph MCP Server is a lightweight server implementation of the Model Context Protocol (MCP) designed to connect Memgraph (a graph database) with large language models (LLMs). It facilitates integration of Memgraph with AI tools and workflows, enabling query execution and schema access via MCP.

## Features
- **Lightweight MCP Server**: Implements the Model Context Protocol to enable communication between Memgraph and MCP-compatible clients.
- **Cypher Query Execution**: Provides a `run_query()` tool to run Cypher queries against a Memgraph database.
- **Schema Access**: Offers a `get_schema()` resource to retrieve schema information from Memgraph (requires `--schema-info-enabled=True` on Memgraph server).
- **Integration with LLMs**: Designed for use with AI tools like Claude for Desktop, allowing users to interact with Memgraph via chat interfaces.
- **Quick Start Setup**: Instructions provided for setting up the server, connecting it to Memgraph, and integrating with clients such as Claude Desktop.
- **Open Source**: The project is distributed under the MIT license and written in Python.
- **Planned Enhancements**: Roadmap includes a TypeScript version for JavaScript environments and migration to a central AI Toolkit repository for broader integrations (LangChain, LlamaIndex, MCP, etc.).

## Pricing
- **Open Source**: Free to use under the MIT license.

## Tags
`mcp`, `database`, `graph-database`, `memgraph`