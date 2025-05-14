# ndthanhdev/mcp-browser-kit

An open-source MCP server that enables AI assistants to interact with your local browsers using manifest v2 compatible extensions.

**Source:** [GitHub Repository](https://github.com/ndthanhdev/mcp-browser-kit)

## Features
- **MCP Server for Browser AI Integration:** Allows AI assistants to control and interact with your local browser.
- **Manifest v2 (M2) and Manifest v3 (M3) Extension Support:**
  - M2 build offers broader functionality (recommended when supported).
  - M3 build provides compatibility for browsers only supporting manifest v3.
- **Cross-Browser Extension Compatibility:**
  - Chrome: M3 only
  - Brave: M2 and M3
  - Edge: M2 and M3
  - Firefox: M2 only
  - Safari: M2 only
- **Easy Extension Loading:**
  - Step-by-step instructions for loading unpacked extensions in Chrome/Brave/Edge, Firefox, and Safari.
- **Separation of Profiles for Security:** Recommended to use a separate browser profile or instance to prevent unintentional exposure of sensitive data to AI model providers.
- **Keep-Alive Mechanism:** Implements a keep-alive mechanism for stable communication.
- **Error Handling:** Enhanced error handling in server operations.
- **Open Source:** Codebase primarily in TypeScript.

## Usage
- Add `mcp-browser-kit` as an MCP server in your MCP client configuration.
- Download the appropriate extension build (M2 or M3) for your browser from the [Releases page](https://github.com/ndthanhdev/mcp-browser-kit/releases).
- Load and enable the extension in your browser.
- Use your MCP client to send commands that control your browser through the kit.

## Pricing
- **Free and open-source** (MIT License).

## Tags
`mcp` `browser` `integration` `open-source`