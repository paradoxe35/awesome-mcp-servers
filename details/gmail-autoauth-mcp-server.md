# Gmail AutoAuth MCP Server

**Category:** Data Access Integration MCP Servers  
**Tags:** mcp, gmail, workflow, automation, email  
**Source:** [GitHub Repository](https://github.com/rory4154154/Gmail-MCP-Server-n8n)

## Description
Gmail AutoAuth MCP Server is a Model Context Protocol (MCP) server for integrating Gmail with Claude Desktop. It provides automated Gmail authentication and enables AI assistants to perform Gmail operations via natural language, facilitating workflow automation such as converting emails into tasks, tickets, or CRM records.

## Features
- **Automated Gmail authentication:** Simple OAuth2 flow with automatic browser launch, supports both Desktop and Web app credentials.
- **Global credential storage:** Credentials are stored globally for convenience and can be accessed from any directory.
- **Send emails:** Supports subject, content (including international characters), attachments, and multiple recipients.
- **Read emails by ID:** Advanced MIME structure handling; extracts plain text or HTML content and handles attachments.
- **View attachment info:** Access filenames, types, and sizes of email attachments.
- **Search emails:** Use Gmail search syntax (from, to, subject, has:attachment, date range, label, etc.).
- **List Gmail labels:** Retrieve all system and user-defined labels.
- **List emails by label:** View emails in inbox, sent, or custom labels.
- **Mark emails read/unread.**
- **Move emails:** Move to different labels/folders.
- **Delete emails.**
- **Draft emails:** Create email drafts without sending.
- **Modify emails:** Add or remove labels (archive, move, etc.).
- **Integration with Claude Desktop:** Exposes tools for use in Claude workflows.
- **Docker support:** Run the server and authentication via Docker containers.
- **International character support:** Handles non-ASCII characters in subjects and bodies (Turkish, Chinese, Japanese, Korean, etc.).
- **Security:** Credentials are stored securely and only accessible by the current user; uses offline access for persistent authentication.
- **Advanced search:** Supports combining multiple Gmail search operators.
- **Email content extraction:** Handles complex multi-part MIME messages and preserves original headers.

## Available Tools (API Endpoints)
- **send_email:** Send a new email
- **draft_email:** Create a draft email
- **read_email:** Retrieve content of a specific email
- **search_emails:** Search using Gmail syntax
- **modify_email:** Add/remove labels, move emails
- **delete_email:** Permanently delete an email
- **list_email_labels:** List all Gmail labels

## Installation & Authentication
- Install via `Smithery` CLI or manually by creating a Google Cloud Project and obtaining OAuth credentials.
- Authenticate globally (recommended) or locally; credentials are stored in `~/.gmail-mcp/`.
- Docker-based deployment is supported for both authentication and server operation.

## Security Notes
- OAuth credentials are stored securely in the user's local environment.
- Offline access is used for persistent authentication.
- Credentials should not be shared or committed to version control.

## License
MIT License

## Pricing
No pricing information available; open source under MIT license.