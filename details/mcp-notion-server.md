# mcp-notion-server

**Source:** [GitHub - suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server)

**Category:** Project Management MCP Servers

**Tags:** Notion, Integration, Project Management, MCP, Open Source

---

## Description

`mcp-notion-server` is an open-source MCP (Model Context Protocol) server that enables AI models (such as Claude) to interact programmatically with Notion workspaces using the Notion API. It allows reading, updating, and managing Notion data via MCP, making it possible to automate and integrate Notion operations in various workflows.

---

## Features

- **Supports Notion API Integration:** Allows AI models to access Notion workspaces with proper authentication via integration tokens.
- **Flexible Setup:** Can be run using `npx` or directly via Node.js with environment variables for configuration.
- **Environment Variable Configuration:**
  - `NOTION_API_TOKEN`: Required for authentication.
  - `NOTION_MARKDOWN_CONVERSION`: Optional, enables experimental Markdown conversion for responses.
- **Response Format Control:**
  - Choose between JSON and Markdown response formats per request.
  - Markdown format is more human-readable and reduces token consumption (experimental).
- **Comprehensive Notion Operations:**
  - **Block Operations:** Append, retrieve, list children, and delete blocks.
  - **Page Operations:** Retrieve and update page properties.
  - **Database Operations:** Create, query, retrieve, update databases, and create new database items.
  - **Search:** Search pages or databases by title with optional filters and sorting.
  - **User Management:** List all users, retrieve specific users, and retrieve bot user info (some features require Notion Enterprise and Organization API key).
  - **Comments:** Create comments on pages/discussions and retrieve unresolved comments (requires appropriate integration permissions).
- **Pagination and Filtering:** Most list and query operations support pagination (via `start_cursor` and `page_size`) and filtering/sorting options where applicable.
- **MIT License:** Free to use, modify, and distribute under the MIT license.

---

## License

MIT License

---

## Pricing

This project is open source and free to use under the MIT license. No pricing plans are required.

---

## Links

- [Repository](https://github.com/suekou/mcp-notion-server)
- [English setup guide](https://dev.to/suekou/operating-notion-via-claude-desktop-using-mcp-c0h)
- [Japanese setup guide](https://qiita.com/suekou/items/44c864583f5e3e6325d9)
