# mcp-obsidian

**Source:** [GitHub - MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian)

## Description
mcp-obsidian is an MCP (Model Context Protocol) server that enables integration with Obsidian via its REST API community plugin. It is designed to facilitate AI-powered knowledge management and automation by providing programmatic access to Obsidian vaults.

## Features
- **Obsidian REST API Integration:** Connects to Obsidian using the Local REST API community plugin.
- **File and Directory Listing:**
  - `list_files_in_vault`: Lists all files and directories in the root directory of the Obsidian vault.
  - `list_files_in_dir`: Lists all files and directories in a specified directory within the vault.
- **File Content Operations:**
  - `get_file_contents`: Retrieves the content of a specified file.
  - `patch_content`: Inserts content into an existing note relative to a heading, block reference, or frontmatter field.
  - `append_content`: Appends content to a new or existing file.
- **Search:**
  - `search`: Searches for documents matching a specified text query across all files in the vault.
- **Batch Operations:** Ability to get contents of multiple files in a batch operation.
- **Configurable API Key:** Supports configuration of the Obsidian REST API key via environment variables or `.env` files.
- **Development and Debugging Tools:**
  - Integration with MCP Inspector for debugging.
  - Server logs accessible for troubleshooting.
- **Cross-platform Support:** Instructions provided for both MacOS and Windows environments.
- **Open Source:** Distributed under the MIT license.

## Installation & Setup
- Requires the [Obsidian Local REST API community plugin](https://github.com/coddingtonbear/obsidian-local-rest-api).
- API key configuration via environment variable or `.env` file.
- Detailed setup for development and published server environments provided in the documentation.

## Pricing
- **Open Source:** Free to use under the MIT license.

## Tags
mcp, obsidian, knowledge-base, ai-integration

## Category
Documentation & Learning Resources