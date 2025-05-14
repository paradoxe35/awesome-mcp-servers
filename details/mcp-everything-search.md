# mcp-everything-search

A cross-platform MCP server that provides fast file searching capabilities by integrating with platform-specific search tools (Everything SDK on Windows, mdfind on macOS, locate/plocate on Linux).

**Source:** [GitHub - mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search)

## Features
- **Cross-platform support:**
  - **Windows:** Uses Everything SDK for comprehensive and fast file searches.
  - **macOS:** Uses built-in `mdfind` for filename and content search via the Spotlight database.
  - **Linux:** Uses `locate` or `plocate` for basic filename searches.
- **Flexible search parameters:**
  - `query` (required): Search query string, supports platform-specific syntax.
  - `max_results` (optional): Limit number of results (default: 100, max: 1000).
  - `match_path` (optional): Match against full path (default: false).
  - `match_case` (optional): Case-sensitive search (default: false).
  - `match_whole_word` (optional): Match whole words only (default: false).
  - `match_regex` (optional): Regex search (default: false).
  - `sort_by` (optional): Multiple sort options (by filename, path, size, extension, creation/modification date, ascending/descending).
- **Result details:**
  - File/folder path
  - File size in bytes
  - Last modified date
- **Platform-specific search syntax support.**
- **Installation flexibility:**
  - Install via Smithery CLI, pip, or run directly with `uvx`.
- **Integration:**
  - Can be integrated with Claude Desktop via configuration file.
- **Debugging tools:**
  - Supports MCP inspector for debugging.
  - Server log access for troubleshooting.
- **Open source:**
  - Licensed under the MIT License.

## Prerequisites
- **Windows:**
  - Install Everything search utility and Everything SDK.
- **Linux:**
  - Install and initialize `locate` or `plocate`.
- **macOS:**
  - No extra setup needed.

## Installation
- **Smithery CLI:**
  - `npx -y @smithery/cli install mcp-server-everything-search --client claude`
- **pip:**
  - `pip install mcp-server-everything-search`
- **uvx:**
  - Run directly using `uvx mcp-server-everything-search`

See the repository for detailed configuration and usage instructions.

## Pricing
- **Open Source:** Free to use under the MIT License.
