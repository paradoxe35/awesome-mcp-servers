# mcp-kibela-server

A robust MCP server for interacting with the Kibela API, designed to enable powerful management and integration of Kibela data.

**Source:** [GitHub Repository](https://github.com/kiwamizamurai/mcp-kibela-server)

## Features
- **Kibela API Integration:** Provides an MCP server specifically for integrating with Kibela, enabling automation and interaction with Kibela content.
- **LLM Compatibility:** Enables large language models (LLMs) to interact with Kibela content.
- **Multiple Tools/Endpoints:**
  - `kibela_search_notes`: Search Kibela notes by query.
  - `kibela_get_my_notes`: Retrieve your latest notes.
  - `kibela_get_note_content`: Fetch content and comments for a specific note.
  - `kibela_get_groups`: List accessible groups.
  - `kibela_get_group_folders`: Show folders within a group.
  - `kibela_get_group_notes`: List notes in a group that are not attached to a folder.
  - `kibela_get_folder_notes`: Fetch notes within a folder.
  - `kibela_get_users`: Retrieve a list of users.
  - `kibela_like_note`/`kibela_unlike_note`: Like or unlike a note.
  - `kibela_get_recently_viewed_notes`: Get recently viewed notes.
  - `kibela_get_note_from_path`: Fetch note content by its path or URL.
- **Configuration:**
  - Supports configuration via environment variables.
  - Integration with Cursor via `~/.cursor/mcp.json`.
- **Docker Support:**
  - Includes a Dockerfile for containerized deployment.
  - SSE transport supported at `/sse` endpoint.
- **Development Tools:**
  - Local development setup instructions provided.
  - Compatible with MCP inspector for debugging.

## Category
Project Management / MCP Servers

## Tags
mcp, knowledge-base, api-integration, open-source

## Pricing
No pricing information provided; this appears to be an open-source project.