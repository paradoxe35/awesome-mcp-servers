# Email MCP Server

[Email MCP Server](https://pypi.org/project/mcp-server-email/) is an open-source Model Context Protocol (MCP) server that provides email functionality and integration for AI-powered applications. It allows LLMs and other tools to compose, send, and manage emails, as well as search for attachments in specified directories.

## Features
- **Email Integration:** Supports sending emails via configurable SMTP servers.
- **AI-Powered Operations:** Enables large language models (LLMs) to compose and send emails programmatically.
- **Attachment Search:** Provides tools to search for files in specified directories based on pattern matching.
- **Supported Attachment Types:** The server supports searching and sending various file types as attachments (file types not specified in detail).
- **Prompts/Tools:**
  - `send_email`: Compose and send emails by specifying subject, body, and receiver.
  - `search_attachments`: Find files matching a pattern within a given directory.
- **Configurable:** Uses a `email.json` file for SMTP server configurations.
- **Extensible:** Encourages contributions for new tools and features.
- **Open Source:** Licensed under the MIT License.
- **Python Package:** Installable via pip (`pip install mcp-server-email`).

## Installation
- Install using pip: `pip install mcp-server-email`
- Configure SMTP settings in `email.json`.

## License
MIT License

## Pricing
The Email MCP Server is open-source and free to use.

## Links
- [PyPI Project Page](https://pypi.org/project/mcp-server-email/)
- [Other MCP Servers and Examples](https://github.com/modelcontextprotocol/servers)