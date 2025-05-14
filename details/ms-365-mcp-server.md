# ms-365-mcp-server

**Category:** Data Access Integration MCP Servers  
**Tags:** mcp, microsoft-365, enterprise, api-integration

## Description
ms-365-mcp-server is a Model Context Protocol (MCP) server for interacting with Microsoft 365 services via the Microsoft Graph API. It enables broad enterprise integration with Microsoft 365, providing access to mail, files, Excel, calendar, and other services.

[Source on GitHub](https://github.com/softeria/ms-365-mcp-server)

## Features
- **Authentication:** Uses Microsoft Authentication Library (MSAL) for secure authentication
- **Excel file operations:** Read, write, and manage Excel files in Microsoft 365
- **Calendar event management:** Create, update, and manage calendar events
- **Mail operations:** Access and manage mailboxes
- **OneDrive file management:** Manage files stored in OneDrive
- **OneNote notebooks and pages:** Access and manage OneNote content
- **To Do tasks and task lists:** Interact with Microsoft To Do tasks
- **Planner plans and tasks:** Manage Microsoft Planner plans and tasks
- **Outlook contacts:** Access and manage Outlook contacts
- **User management:** Manage users in Microsoft 365
- **Dynamic tools:** Tools are powered by Microsoft Graph OpenAPI spec, allowing dynamic endpoint support
- **Built on Model Context Protocol:** Integrates with MCP-compatible clients and tools
- **Token caching:** Authentication tokens are securely cached in the OS credential store (with file fallback)
- **CLI and programmatic integration:** Can be used via CLI or integrated into other tools (e.g., Claude Desktop, Claude Code CLI)

## Prerequisites
- Node.js version 14 or higher

## Licensing
- MIT License

## Pricing
- Open source (free to use under MIT License)