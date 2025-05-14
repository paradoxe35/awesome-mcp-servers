# mcp-filesystem-server

A Go server implementing the Model Context Protocol (MCP) for performing file system operations via an API. It allows for direct local file system access and management, with access restricted to directories specified at server startup.

**Source:** [https://github.com/mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server)

## Features
- **Read/write files:** Read the complete content of files and write (create/overwrite) files.
- **Read multiple files:** Simultaneously read multiple files; failed reads do not halt operation.
- **Create/list/delete directories:** Create directories (including parent directories), list directory contents, and delete directories.
- **Move files/directories:** Move or rename files and directories (fails if destination exists).
- **Search files:** Recursively search for files/directories by pattern (case-insensitive), returning full paths.
- **Get file metadata:** Retrieve detailed metadata (size, creation/modification/access time, type, permissions) for files/directories.
- **List allowed directories:** List all directories the server is permitted to access, as specified via startup arguments.
- **API-based access:** All operations are available via a structured API for integration with other tools (e.g., Claude Desktop).
- **Access restriction:** All file system operations are limited to user-specified directories for security.

## Usage Example
- Install via Go: `go install github.com/mark3labs/mcp-filesystem-server`
- Configure allowed directories when starting the server.
- Integrate with applications (e.g., Claude Desktop) by specifying the server command and allowed directories in configuration.

## License
MIT License.

## Pricing
This is an open-source project licensed under MIT. There is no cost to use, modify, or distribute the software.