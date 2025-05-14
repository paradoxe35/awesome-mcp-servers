# mcp-miro

**Description:**
mcp-miro is a Model Context Protocol (MCP) server that integrates with the Miro platform, exposing all functionalities available in the official Miro SDK via the MCP protocol. It enables AI assistants (such as Claude) and other tools to access and manage Miro boards and their contents through a standardized interface.

**Source:** [https://github.com/k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro)

**Category:** project-management-mcp-servers

**Tags:** mcp, miro, collaboration, api-integration

---

## Features

- **Full Miro SDK Integration:** Exposes all available Miro SDK functions via MCP protocol.
- **Board Management:**
  - List, create, update, delete, copy boards
  - Get specific boards
  - Export boards and manage export jobs
  - Share boards
  - Get board classification, content logs
- **Item Management on Boards:**
  - List and manage items on boards (cards, app cards, sticky notes, frames, documents, text, images, shapes, embeds, mindmap nodes, connectors)
  - Create, update, delete, and bulk-create items (including via file uploads)
  - Update item positions
- **Tag Management:**
  - Create, get, update, delete tags
  - Attach/detach tags to/from items
  - Get item tags
- **Group Management:**
  - Create, get, update, delete groups
  - Get group items, ungroup items
- **Member & Organization Management:**
  - Get all board members, specific members, update or remove members
  - Get organization info, members, and related data
  - Add/remove project members
- **Advanced Operations:**
  - Create board export jobs, get results and status
  - Access audit logs, legal holds, cases
  - Update board classification
  - Create items in bulk using files
- **Authentication:** Uses OAuth tokens for secure Miro API access.
- **Local Development Support:**
  - Node.js v16+ required
  - Setup via npm and environment configuration
  - TypeScript-based project
- **Open Source:** Licensed under Apache 2.0

## Pricing

No pricing information is provided. The project is open source and available under the Apache 2.0 license.

---

**License:** Apache 2.0