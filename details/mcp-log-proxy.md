# mcp-log-proxy

A web logging proxy for MCP (Message Communication Protocol) client-server communication. It provides a web interface to visualize and monitor the entire message flow of the MCP protocol, aiding in debugging and development.

**Source:** [https://github.com/emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy)

## Features
- Proxies and logs messages between MCP clients and servers.
- Provides a web UI (accessible at `http://localhost:5656` by default) to view real-time message flow.
- Supports only the STDIO interface for MCP communication.
- Allows customization via command-line flags:
  - `-command`: Specify the full command line to start the MCP server.
  - `-title`: Set a custom browser page title for the web UI.
  - `-port`: Change the HTTP port (default is 5656).
  - `-log`: Specify the log file location for the proxy's internal errors.
- Can be used to proxy and monitor different MCP servers (examples provided for `melrose-mcp` and `browsermcp`).
- Written in Go and easy to install with `go install`.
- Open source under the MIT license.

## Pricing
- **Free and open source** (MIT License).

## Tags
mcp, proxy, debugging, monitoring

## Category
Testing & Debugging Tools