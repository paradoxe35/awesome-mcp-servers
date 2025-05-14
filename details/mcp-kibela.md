# mcp-kibela

**Source:** [https://github.com/kj455/mcp-kibela](https://github.com/kj455/mcp-kibela)

**Category:** Project Management MCP Servers

**Tags:** mcp, knowledge-base, api-integration, open-source

---

## Description

mcp-kibela is an open-source Model Context Protocol (MCP) server that enables AI assistants to search and reference content stored in Kibela via the Kibela API. It allows AI models (such as Claude) to securely access, search, and manage notes on the Kibela platform.

---

## Features

- **Note Search:** Search Kibela notes by keywords.
- **My Notes:** Fetch your latest notes from Kibela.
- **Note Content:** Retrieve note content and comments by note ID.
- **Note by Path:** Access note content by specifying the note path.
- **Create Note:** Create a new note in Kibela.
- **Update Note Content:** Update the content of existing notes by note ID.

---

## Prerequisites

- Node.js (v18 or higher)
- MCP Client (e.g., Claude Desktop, Cursor, VSCode)
- Kibela Access Token
- Git (if building from source)

---

## Installation & Usage

mcp-kibela can be run via Docker and integrated with various MCP clients such as Cursor, VSCode, and Claude Desktop. Example Docker setup requires environment variables `KIBELA_TEAM` and `KIBELA_TOKEN` for authentication.

---

## Environment Variables

- `KIBELA_TEAM`: Your Kibela team name (required)
- `KIBELA_TOKEN`: Your Kibela API token (required)

---

## License

MIT

---

## Pricing

mcp-kibela is open-source software and is free to use under the MIT license.