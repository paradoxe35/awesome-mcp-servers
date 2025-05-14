# File Operations Server

A Model Context Protocol (MCP) server for enhanced file system operations, including support for streaming, patching, and change tracking.

[Source Code on GitHub](https://github.com/bsmi021/file-operations-server)

## Features
- **Basic File Operations:** Reading, writing, copying, and moving files.
- **Directory Management:** Operations for creating, listing, and managing directories.
- **Change Tracking:** Ability to track changes in files and directories.
- **Streaming Support:** Handles file operations with streaming for efficient data handling.
- **Patching:** Supports patching files for incremental updates.
- **Watch Operations:** Monitor files and directories for changes.
- **Progress Reporting:** Provides progress updates for long-running operations (e.g., directory copying), deliverable via progress tokens.
- **Rate Limiting:** Built-in rate limiting to prevent abuse, with error messages including retry-after periods.
- **Security Features:**
  - Path validation to prevent directory traversal attacks.
  - Resource protection to secure file operations.
- **Error Handling:**
  - Detailed error information via custom FileOperationError class and MCP error codes.
  - Standard and custom error types with detailed messages.
- **Configurable:** Server settings can be adjusted for different environments.
- **Static Resources & Templates:** Support for serving static resources and using resource templates.

## Category
file-management-mcp-servers

## Tags
mcp, file-management, filesystem, ai-integration

## Pricing
No pricing information provided; the project is open source under the MIT License.