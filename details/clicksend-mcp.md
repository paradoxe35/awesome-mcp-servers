# Clicksend MCP

[Source Code](https://github.com/j-gal02/clicksend-mcp)

**Category:** Messaging MCP Servers  
**Tags:** mcp, messaging, sms, api-integration

## Description
Clicksend MCP is a Model Context Protocol (MCP) server that integrates with ClickSend's API to provide programmatic SMS messaging and Text-to-Speech (TTS) call automation. It enables AI models and other automated clients to send SMS messages and initiate voice calls via ClickSend.

## Features
- **SMS Messaging:** Send SMS messages to specified phone numbers through ClickSend's API.
- **Text-to-Speech Calls:** Initiate automated voice calls with text-to-speech content.
- **API Integration:** Designed to work with AI models or any client supporting the MCP protocol.
- **Rate Limiting:** Enforces a rate limit of 5 actions per minute. Requests exceeding this limit receive an error with a suggested retry delay.
- **Error Handling:** Returns detailed error codes and messages for easier diagnosis and troubleshooting.
- **Configuration:** Requires configuration of API keys and build directory paths in the client settings.
- **Extensible Roadmap (TODO):**
  - Support for multiple recipients
  - Sender ID configuration
  - Email sending
  - Media uploading
  - Cost calculation and confirmation
  - Usage statistics
  - Message/call history
  - Contact management
  - Automation features

## Pricing
No pricing information is provided. The project is open-source and released under the MIT license.
