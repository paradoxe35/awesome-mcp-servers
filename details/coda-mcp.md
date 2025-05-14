# coda-mcp

**Category:** Project Management MCP Servers  
**Tags:** coda, integration, project-management, mcp, open-source

## Description
coda-mcp is an open-source Model Context Protocol (MCP) server that acts as a bridge for interacting with Coda documents and APIs. It enables MCP clients (such as AI assistants) to access and manipulate Coda documents programmatically, supporting integration of Coda functionality into AI-driven workflows.

## Features
- **List Pages:** List all pages within a specified Coda document.
- **Create Page:** Create new pages in the document, with optional initial markdown content.
- **Get Page Content:** Retrieve the content of a specified page (by ID or name) as markdown.
- **Replace Page Content:** Replace the content of a specified page with new markdown content.
- **Append Page Content:** Append markdown content to the end of a specified page.
- **Duplicate Page:** Create a copy of an existing page with a new name.
- **Rename Page:** Rename an existing page.
- **MCP Integration:** Exposes the above tools via MCP, allowing integration into AI workflows (e.g., Cursor, Claude Desktop).
- **OpenAPI Client Generation:** Supports regenerating the OpenAPI client if the Coda API specification changes.
- **Stdio Communication:** Communicates over standard input/output for compatibility with various AI clients.
- **Configurable via Environment Variables:** Requires `API_KEY` (Coda API key) and `DOC_ID` (Coda document ID) for operation.
- **TypeScript Codebase:** Built with TypeScript, with scripts for linting and formatting.

## Usage
- Add coda-mcp as an MCP server to compatible clients (e.g., Cursor, Claude Desktop) using the provided npm command.
- Configure with required environment variables: `API_KEY` and `DOC_ID`.
- Local development requires Node.js and pnpm.

## Pricing
- **Open Source:** Free to use under the MIT License.

## Source
[GitHub Repository](https://github.com/orellazri/coda-mcp)
