# iMessage Query MCP Server

An MCP (Model Context Protocol) server that provides secure, read-only access to iMessage databases, allowing LLMs (Large Language Models) to query and analyze iMessage conversations. Built using the FastMCP framework and imessagedb library, this server is designed specifically for macOS systems and enables robust, validated access to message data.

**Source:** [GitHub Repository](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server)

## Features

- **Read-only iMessage Database Access:** Grants secure, read-only access to the local iMessage database on macOS.
- **MCP Protocol Support:** Implements the Model Context Protocol for structured, LLM-friendly data access.
- **FastMCP Framework:** Built on the FastMCP framework for efficient MCP server development.
- **imessagedb Integration:** Uses the imessagedb Python library to access and query messages.
- **LLM Integration:** Designed to be used by LLMs for querying and analyzing iMessage conversations.
- **Exposed Tool: get_chat_transcript:**
  - Retrieve message history for a specific phone number
  - Optional date range filtering
  - Returns message text, timestamps, and attachment information
  - Validates phone numbers
  - Handles attachments safely and detects missing files
- **Phone Number Validation:** Uses Google's `phonenumbers` library for proper validation and formatting.
- **Date Filtering:** Supports filtering of messages by date range.
- **Safe Attachment Handling:** Ensures only safe, existing attachments are returned, with missing file detection.
- **Progress Output Suppression:** Ensures clean JSON responses by suppressing extraneous output.
- **No Environment Variables Required:** Automatically locates the iMessage database in the default macOS location.
- **Comprehensive Development Documentation:** Includes documentation about the iMessage database structure and imessagedb library.
- **Installation Options:**
  - Can be installed for Claude Desktop using FastMCP
  - Compatible with the Cline VSCode plugin

## System Requirements

- macOS (required for iMessage database access)
- Python 3.6+

## Dependencies

- `fastmcp` (Model Context Protocol server framework)
- `imessagedb` (access and query macOS Messages database)
- `phonenumbers` (phone number validation and formatting)

## Pricing

No information about pricing is provided. The project appears to be open-source and available for use via the GitHub repository.

## Category

database-messaging-mcp-servers

## Tags

imessage, database, mcp, read-only