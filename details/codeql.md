# Codeql

[Codeql MCP Server](https://github.com/jordyzomer/codeql-mcp) is an implementation of a Model Context Protocol (MCP) server that wraps the CodeQL query server. It enables integration with tools like Cursor or AI agents to interact with the CodeQL static analysis engine through structured commands and doc search.

## Features
- Runs an MCP server providing an interface to the CodeQL query server.
- Allows interaction with CodeQL using structured commands (such as from AI agents or compatible tools).
- Supports doc search functionality.
- Implements the server using FastMCP (via `server.py`).
- Handles JSON-RPC commands via `codeqlclient.py` for communication with the CodeQL query server.
- Can be installed via pip or uv.
- Designed to be used as a backend for code analysis, security, and quality assurance workflows.

## Installation
- Can be installed with pip or uv (see repository for details).

## Usage
- Run the MCP server to expose CodeQL tools and allow external tools or agents to interact with CodeQL.
- Configuration for integration with tools like Cursor is provided in the repository.

## Pricing
No pricing information is provided; this appears to be an open-source project.

## Tags
mcp, code-analysis, security, quality-assurance