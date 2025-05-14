# server-filesystem

**Category:** file-management-mcp-servers  
**Tags:** mcp, filesystem, file-access, open-source

A Node.js MCP (Model Context Protocol) server for direct local file system access, designed as part of the official Model Context Protocol servers suite. It allows controlled programmatic access to the file system for operations such as reading, writing, editing, moving, and searching files and directories, restricted to specified allowed directories.

**Source:** [GitHub - modelcontextprotocol/servers/src/filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)

---

## Features

- **Read/write files:** Read the complete contents of a file or write/overwrite files.
- **Read multiple files:** Read several files at once; failed reads do not halt the operation.
- **Edit files:** Make selective edits using advanced pattern matching and formatting (supports dry-run preview, line/multi-line matching, whitespace normalization, indentation preservation, git-style diffs).
- **Create/list/delete directories:** Create new directories (including parent directories as needed), list contents with file/dir distinction, or delete directories.
- **Move files/directories:** Move or rename files and directories; operation fails if the destination exists.
- **Search files:** Recursively search for files/directories with support for glob exclude patterns and case-insensitive matching; returns full paths to matches.
- **Get file/directory metadata:** Retrieve size, creation/modification/access times, type, and permissions for files/directories.
- **List allowed directories:** See all directories the server is permitted to access.
- **Access restrictions:** All operations are strictly limited to directories specified at server startup (for sandboxing and security).
- **Deployment options:**
  - **Docker:** Run the server in a Docker container, mounting allowed directories to `/projects`.
  - **npx:** Run the server locally via npx, specifying allowed directories as arguments.
- **MIT License:** Free to use, modify, and distribute under the MIT License.

---

## Usage

- **Docker:** Mount desired directories to `/projects` and run the container.
- **npx:** Specify allowed directories as arguments to the npx command.
- **Integration:** Can be integrated with Claude Desktop and other MCP-compatible tools.

---

## Pricing

This project is open-source and free to use under the MIT License. No paid plans or pricing tiers are mentioned.
