# File Context Server

[Source Code](https://github.com/bsmi021/file-context-server)

## Description
File Context Server is a Model Context Protocol (MCP) server that provides file system context to Large Language Models (LLMs). It enables LLMs to read, search, and analyze code files, featuring advanced caching and real-time file watching capabilities. It is designed for cross-platform compatibility (Windows, macOS, Linux).

## Features
- **File Operations:** Enables LLMs to interact with code files, including listing and reading files in context directories.
- **Code Analysis:** Provides tools for analyzing code within files.
- **Smart Caching:** Uses advanced caching mechanisms to optimize performance and reduce redundant file operations.
- **Advanced Search:** Supports searching through code files for relevant content.
- **Real-Time File Watching:** Monitors file changes to keep context up to date in real time.
- **Available Tools:**
  - `list_context_files`: List files in the context directory.
  - `read_context`: Read the contents of context files.
  - `search_context`: Search within context files.
  - `analyze_code`: Analyze code in files.
  - `cache_stats`: View statistics about the cache.
- **Detailed Error Handling:** Provides specific error codes and messages for troubleshooting.
- **Environment Variable Configuration:** Supports customization through environment variables.
- **Cross-Platform Path Handling:** Improved compatibility for file and directory paths across all major operating systems.

## Category
file-management-mcp-servers

## Tags
mcp, file-management, file-search, real-time

## Pricing
No pricing information provided. The project is open source and licensed under the MIT License.