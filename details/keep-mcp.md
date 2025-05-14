# keep-mcp

MCP server for Google Keep, supporting reading, creating, updating, and deleting notes through the MCP protocol.

Source: [https://github.com/feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp)

## Features
- **find**: Search for Google Keep notes using a query string.
- **create_note**: Create a new note with a title and text. New notes are automatically labeled with `keep-mcp`.
- **update_note**: Update the title and text of an existing note.
- **delete_note**: Mark a note for deletion.
- By default, all destructive and modification operations are restricted to notes created by the MCP server (notes with the `keep-mcp` label).
- Option to enable `UNSAFE_MODE` to allow modification of all notes, not just those created by keep-mcp.
- Configurable via environment variables for Google account email and master token.

## Category
project-management-mcp-servers

## Tags
mcp, notes, google-workspace, open-source

## Pricing
- This project is open source and licensed under the MIT License. No pricing or paid plans.