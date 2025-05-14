# whatsapp-mcp

**Category:** Messaging MCP Servers  
**Tags:** mcp, messaging, whatsapp, api-integration

## Description
WhatsApp MCP is an MCP server that bridges WhatsApp Web with AI assistants and MCP clients, enabling searching, sending, and reading WhatsApp messages and media through the WhatsApp web multi-device API. It allows seamless integration of WhatsApp communication features into AI workflows and automated systems using the Model Context Protocol (MCP).

## Features
- **Client-Server Architecture:** Securely connects WhatsApp Web to AI assistants (e.g., Claude, Cursor) via a Go-based bridge and a Python MCP server.
- **Local Data Storage:** All WhatsApp data is stored in a local SQLite database for privacy and optimized query performance.
- **Chat Search & Management:**
  - `search_contacts`: Search contacts by name or phone number.
  - `list_messages`: Retrieve messages from a specific chat with filtering and pagination.
  - `list_chats`: List all available chats, including groups and individuals.
- **Chat Analysis & Interaction:**
  - `get_chat`: Get detailed information about a chat (participants, creation date, statistics).
  - `get_direct_chat_by_contact`: Find a direct chat with a specific contact.
  - `get_contact_chats`: List all chats involving a specific contact.
  - `get_last_interaction`: View the most recent interaction with a contact.
  - `get_message_context`: Retrieve surrounding messages for context.
- **Message Sending & Automation:**
  - `send_message`: Send text, media files, documents, or location data.
  - `send_file`: Send images, videos, documents, or other files.
  - `send_audio_message`: Send WhatsApp voice messages.
  - `download_media`: Download media from WhatsApp messages.
- **Automated Workflow Support:**
  - Enables creation of auto-reply bots, intelligent message processors, and advanced AI-driven chatbots.
  - Supports sentiment analysis, topic extraction, and group management automation via AI integration.
- **Privacy and Security:** Messages never leave the device unless explicitly requested; authentication via WhatsApp QR code.
- **Cross-Platform Support:** Works on macOS and Windows (with specific setup for go-sqlite3 on Windows).
- **Extensive Command Reference:** Comprehensive set of commands for querying, managing, and automating WhatsApp interactions via MCP.

## Installation
- Requires Go (for the bridge), Python 3.6+ (for the MCP server), and the UV package manager.
- Windows users must enable CGO and install a C compiler (e.g., via MSYS2) for go-sqlite3 support.
- Authentication via WhatsApp QR code; periodic re-authentication may be required.
- Full installation and configuration steps are provided in the official guide.

## Advanced Application Scenarios
- Intelligent conversation analysis (sentiment, topics, key themes)
- Automated group management and message processing
- AI chatbot integration for customer service, community management, and more

## Pricing
_No pricing information is provided in the available content._

## Source
[Complete AI Integration Guide 2025 - DEV.to](https://dev.to/neo-cruz/whatsapp-mcp-complete-ai-integration-guide-2025-249c)