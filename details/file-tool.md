# File Tool

**Category:** File Management MCP Servers  
**Tags:** mcp, file-management, filesystem, ai-integration

## Description
File Tool is a Model Context Protocol (MCP) server that enables AI models, such as Claude AI, to perform file system operations (reading, creating, and listing files) on a local file system via a standardized interface.

**Source:** [GitHub Repository](https://github.com/smithery-ai/filesystem-mcp-server)

## Features
- **Read File:** Read the complete contents of a file.
- **Read Multiple Files:** Read multiple files simultaneously.
- **Write File:** Create new files or overwrite existing files.
- **Create Directory:** Create a new directory or ensure an existing one.
- **List Directory:** List directory contents, indicating files and directories.
- **Move File:** Move or rename files and directories.
- **Search Files:** Recursively search for files or directories.
- **Get File Info:** Retrieve detailed metadata about files or directories.
- **List Allowed Directories:** List all directories the server is permitted to access.
- **Security:** All operations are restricted to directories specified at server launch via command-line arguments.

## Installation & Usage
- Run the server with one or more allowed directories.
- Integrate with your MCP configuration.

## License
ISC

## Pricing
No pricing information provided. The project is open-source under the ISC license.