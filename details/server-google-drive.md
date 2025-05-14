# server-google-drive

An MCP server for Google Drive integration, supporting file listing, reading, and searching via the Model Context Protocol.

- **Category:** file-management-mcp-servers
- **Tags:** mcp, google-drive, file-management, integration
- **Source:** [GitHub Repository](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive)

## Features
- **Google Drive Integration:** Connects to Google Drive to access files and folders.
- **File Listing:** Lists all files available in the connected Google Drive account.
- **File Reading:** Reads files of any type from Google Drive.
- **File Searching:** Allows searching for files using query strings, returning file names and MIME types.
- **Automatic Export of Google Workspace Files:**
  - Google Docs → Markdown
  - Google Sheets → CSV
  - Google Presentations → Plain text
  - Google Drawings → PNG
- **Native Format Support:** Non-Google Workspace files are provided in their original format.
- **OAuth Authentication:** Supports Google OAuth 2.0 authentication for secure access.
- **Docker and NPX Support:** Can be run via Docker or NPX for flexible deployment.
- **Credential Management:** Stores and manages credentials securely for authenticated access.

## Usage
- **Setup:**
  - Requires a Google Cloud project, Drive API enabled, and OAuth consent/configuration.
  - Authentication can be performed interactively via browser or using Docker commands.
- **Integration:** Easily integrates with desktop apps or other MCP-compatible tools by configuring the server connection.

## License
- **MIT License** – free to use, modify, and distribute under the terms of the MIT License.

## Pricing
- The server is open source and free to use (MIT License). No pricing plans are specified.