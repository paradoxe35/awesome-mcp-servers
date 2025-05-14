# browser-control-mcp

[Source Code](https://github.com/eyalzh/browser-control-mcp)

## Description
browser-control-mcp is an MCP server paired with a browser extension that enables AI agents (such as Claude Desktop) to control and interact with a user's Firefox browser. It allows AI agents to manage browser tabs, perform research, and retrieve information from open browser tabs.

## Features
- MCP server integrated with a Firefox browser extension
- Enables AI agents to:
  - Manage open browser tabs
  - Search browser history
  - Access and use the browser for browsing and research tasks
- Provides the contents of each opened tab as an MCP resource, allowing selection and loading of tab content into the MCP client (e.g., Claude)
- Safe design: Does **not** allow arbitrary scripting or web page modification
- Extension preferences allow users to limit the actions the MCP server can perform
- Designed for use with Firefox (including Firefox Developer Edition)
- Integration instructions provided for Claude Desktop

## Installation
- Clone the repository and build both the MCP server and the browser extension
- Install the extension in Firefox or Firefox Developer Edition
- Configure for use with Claude Desktop by updating the configuration file with the extension secret

## Pricing
No pricing information is provided; the project appears to be open source.

## Tags
mcp, browser, automation, ai-integration

## Category
code-execution-automation-mcp-servers