# poem-mcpserver

[Source Code](https://github.com/RGGH/poemcp)

## Description
poem-mcpserver is an implementation of a Model Context Protocol (MCP) server in Rust, built using the Poem web framework. It supports efficient request handling for MCP and provides various tools accessible via Server-Sent Events (SSE) endpoints for real-time client interaction.

## Features
- **Counter Tool:** Manage and manipulate counters through the MCP server interface.
- **Adder Tool:** Add numbers using the provided tool endpoint.
- **IP Validator:** Validate IP addresses to check if they are well-formed.
- **CIDR Checker:** Check if an IP address belongs to a specified CIDR range.
- **SSE Endpoint:** All tools are exposed via a Server-Sent Events endpoint, enabling real-time interaction between clients and the server.
- **Built with Rust & Poem:** Leverages the safety and performance of Rust and the flexibility of the Poem web framework.

## Installation & Setup
- Clone the repository.
- Build the project using Cargo.
- Run the server; it listens on `http://127.0.0.1:8000` by default.

## License
MIT License

## Tags
rust, web, framework, mcp, open-source

## Category
development-tools-mcp-servers

## Pricing
This project is open-source and free to use under the MIT License.