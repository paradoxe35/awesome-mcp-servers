# Clojars MCP Server

A Model Context Protocol (MCP) server that provides tools for fetching dependency version information from [Clojars](https://clojars.org/), the Clojure community's artifact repository.

- **Source Code:** [GitHub Repository](https://github.com/Bigsy/clojars-mcp-server)
- **Category:** Data Access & Integration / MCP Servers
- **Tags:** clojure, dependency-management, mcp, open-source

## Features

- **Model Context Protocol (MCP) Server:** Implements the MCP protocol to integrate with tools like Cline, Roo Code, Cody, and Claude Desktop.
- **Clojars Integration:** Connects specifically to the Clojars repository to fetch dependency information for Clojure projects.
- **Two Main Tools Exposed:**
  - `get_clojars_latest_version`: Retrieve the latest version of a dependency from Clojars.
  - `check_clojars_version_exists`: Check if a specific version of a dependency exists on Clojars.
- **Automatic Detection:** Once configured in compatible clients (e.g., Claude Desktop), the server is automatically detected and its capabilities listed.
- **Multiple Installation Methods:**
  - Run directly with `npx`.
  - Global installation available.
  - Install via Smithery for seamless integration with Claude Desktop.
  - Manual configuration possible for VSCode Claude extension and Claude desktop app.
- **Open Source:** Source code is available under an open license.

## Pricing

No pricing information is provided. The project appears to be open source.
