# markitdown-mcp

**Category:** File Management MCP Servers  
**Tags:** markdown, document-conversion, llm, mcp

## Description
markitdown-mcp is a lightweight MCP (Model Context Protocol) server for accessing MarkItDown, a library that converts various file formats to Markdown for use with large language models (LLMs). It provides a simple interface for converting files accessible via HTTP(S), file, or data URIs to Markdown via a single tool: `convert_to_markdown(uri)`.

## Features
- Provides a lightweight MCP server with STDIO (default) and SSE (Server-Sent Events) modes.
- Exposes the `convert_to_markdown(uri)` tool, which accepts URIs (http:, https:, file:, data:) and converts the referenced file to Markdown.
- Can be run directly as a command-line tool, or as a Docker container.
- Supports mounting local directories into the Docker container for access to local files.
- Recommended for integration with Claude Desktop via its MCP server configuration.
- Can be debugged using the `mcpinspector` tool, supporting both STDIO and SSE transports.
- No authentication provided; when using SSE, it is recommended to bind the server to localhost for security.

## Installation
- Install via pip: `pip install markitdown-mcp`
- Alternatively, build and run the Docker image using the provided Dockerfile.

## Usage
- Run the MCP server using STDIO: `markitdown-mcp`
- Run with SSE: `markitdown-mcp --sse --host 127.0.0.1 --port 3001`
- In Docker: `docker run -it --rm markitdown-mcp:latest`
- Mount local files in Docker: `docker run -it --rm -v /home/user/data:/workdir markitdown-mcp:latest`
- Configure for Claude Desktop by editing `claude_desktop_config.json` to use the Docker-run MCP server.

## Security Considerations
- No authentication is provided.
- Runs with user privileges; recommended to bind to localhost in SSE mode.

## Source
[GitHub: markitdown-mcp](https://github.com/microsoft/markitdown/tree/main/packages/markitdown-mcp)

## Pricing
- No pricing information provided; appears to be open source.