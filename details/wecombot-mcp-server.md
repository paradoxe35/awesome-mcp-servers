# wecombot-mcp-server

**Source:** [GitHub Repository](https://github.com/gotoolkits/mcp-wecombot-server.git)

**Category:** messaging-mcp-servers

**Tags:** mcp, messaging, wecom, integration

---

## Overview
`wecombot-mcp-server` is an MCP server application designed to send a variety of message types to WeCom (WeChat Work) group robots. It enables flexible integration and communication using the MCP server protocol.

---

## Features
- **Multiple Message Types:**
  - Send text messages to WeCom group robots.
  - Send markdown-formatted messages.
  - Send image messages.
  - Send news messages, which can include a title, description, URL, and image.
  - Send template card messages.
- **File Upload:**
  - Upload files directly to WeCom.
- **Flexible Installation:**
  - Install via Smithery CLI for Claude Desktop or manually via cloning/building the repository or using pre-compiled binaries.
- **Configurable Integration:**
  - Easily configure MCP server and WeCom bot webhook keys for secure message delivery.
- **Sample Prompts Provided:**
  - Example prompts for sending each message type are available to assist setup and usage.
- **Written in Go:**
  - High-performance and efficient implementation.
- **Open Source:**
  - Licensed under GPL-3.0.

---

## Usage
- Configure the WeCom bot webhook key (`WECOM_BOT_WEBHOOK_KEY`) for authentication.
- Use commands such as `send_text`, `send_markdown`, `send_image`, `send_news`, `send_template_card`, and `upload_file` to interact with WeCom groups.
- Refer to the [WeCom robot documentation](https://developer.work.weixin.qq.com/document/path/91770) for additional configuration details.

---

## Pricing
- No pricing information is provided. The project is open source and available under the GPL-3.0 license.

---

## License
- GPL-3.0